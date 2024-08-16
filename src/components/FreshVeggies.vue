<template>
  <section>
    <div>
      <img src="../assets/images/unsplash_NDyuR4Huig8.svg" alt="" />
    </div>
    <div>
      <h2>Fresh Vegetables Every Day</h2>
      <p>
        Healthy life can not be overemphasized. Our vegetables are organically
        grown without no added chemicals so users would live a healthy life.
      </p>
      <button>Learn More</button>
    </div>
  </section>
</template>

<script></script>

<style scoped>
section {
  display: grid;
  grid-template-columns: 50% 50%;
  width: 95vw;
  gap: 100px;
  margin-top: 100px;
}

img {
    width: 100%;
    height: 100%;
   
}

div:has(img) {
    width: 100%;
    height: 80dvh;

}

div:has(p) {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    width: 70%;
    gap: 20px;
}

div {
    width: 100%;
    height: 100%;
    
    & h2 {
        font-size: 40px;
        line-height: 52.01px;
        font-weight: 700;
        margin: 0;
    } 

    & p {
        font-size: 20px;
        font-weight: 500;
        color: #3A3A3A;
        margin: 0;
    }
}

@media only screen and (max-width:1024px) {
  section {
    width: 90dvw;
    margin-top: 0px;
  }

div {
  & h2{
    font-size: 35px;
  }

  & p {
    font-size: 18px;
  }
}

  h2 {
    font-size: 30px;
  }

  div:has(p) {
    width: 100%;
  }
}

@media only screen and (max-width:768px) {
  section{
    grid-template-columns: 1fr;
    gap: 50px;
    margin-top: 400px;
    width: 100%;
  }

  div {
    margin: 0 auto;
  }

  div:has(p) {
    align-items: center;
  }
}

@media only screen and (max-width:426px) {
  section{
    margin-top: 100px;
    gap: 10px;
    align-items: center;

  }

  div:has(img) {
    width: 100%;
    height: auto; 
}

div:has(p) {
    align-items: center;

    & h2 {
      font-size: 30px;
      line-height: 40px;
      text-align: center;
    }

    & p {
      text-align: center;
    }
  }

}
</style>
