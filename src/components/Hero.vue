<template>
  <section class="hero">
    <div class="hero-discription">
      <h1>just <span>Eat healthy</span> food to live a healthier life</h1>
      <p>
        Enjoy a healthy life by eating healthy meals that have extraordinary
        flavors that make your life healthier for today and in the future
      </p>
      <button>
        <a href="#">Order Now</a>
      </button>
    </div>
    <div>
      <img src="../assets/images/hero_image.png" alt="hero_image" />
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
  display: grid;
  grid-template-columns: 40% 60%;
  width: 100%;
  overflow-x: hidden;
}

.hero-discription {
  display: flex;
  flex-direction: column;
  gap: 30px;
  align-items: flex-start;
  justify-content: center;
}

.hero h1 {
  font-size: 64px;
  font-weight: 700;
  line-height: 83.21px;
  text-align: start;
  padding: 0;
  margin: 0;
  text-transform: capitalize;
}

.hero span {
  color: #008000;
}

.hero p {
  font-size: 20px;
  line-height: 32.4px;
  margin: 0;
  width: 65%;
   text-align: justify;
}

img {
  width: 100%;
}

@media only screen and (max-width: 1046px) {
  .hero h1 {
    font-size: 50px;
    font-weight: 700;
    line-height: 60.21px;
    text-align: start;
    padding: 0;
    margin: 0;
    text-transform: capitalize;
  }

  .hero p {
    width: 100%;
  }

  div:has(img) {
    margin: 0;
    padding: 0;
    overflow: hidden;
  }

  img {
    height: 100%;
    width: 100%;
  }

}

@media only screen and (max-width: 768px) {
  .hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: auto;
    align-items: self-start;
  }

  .hero-discription {
    align-items: center;
    text-align: center;
    gap: 20px;
   
  }

  .hero h1 {
    font-size: 40px;
    line-height: 50px;
    text-align: center;
  }

  .hero p {
    font-size: 16px;
    line-height: 26px;
    width: 80%;
    text-align: center;
  }




}

@media only screen and (max-width: 427px) {
  .hero {
   display: block;
  
  }

  .hero h1 {
    font-size: 32px;
    line-height: 50px;
  }

}

@media only screen and (max-width: 376px) {
 
  .hero h1 {
    font-size: 28px;
    line-height: 40px;
  }

  .hero p {
    font-size: 14px;
    line-height: 20px;
  }

  button {
    font-size: 14px;
  }
}

@media only screen and (max-width: 320px) {
    .hero {
        width: 100%;
    }

  .hero h1 {
    font-size: 24px;
    line-height: 30px;
  }

  .hero p {
    font-size: 14px;
    line-height: 20px;
  }

  button {
    font-size: 14px;
  }
}
</style>
