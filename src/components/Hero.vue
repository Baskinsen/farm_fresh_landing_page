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
        grid-template-columns: 50% 50%;
        padding: 30px 150px;
        justify-content: center;
        align-items: center;
    }

    .hero-discription {
        display: flex;
        flex-direction: column;
        gap: 50px;
        align-items: flex-start;
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
    }

    img {
        width: 100%;
    }

    @media only screen and (max-width: 1046px) {
        .hero {
            padding: 30px 50px;
        }
    }

    @media only screen and (max-width: 768px) {
        .hero {
            grid-template-columns: none;
            grid-template-rows: 50% 50%;
            padding: 30px 100px;
        }

        .hero-discription {
            align-items: center;
            text-align: center;
            gap: 20px;
        }

        .hero h1 {
            font-size: 40px;
            line-height: 52px;
            text-align: center;
            
        }

        .hero p {
            font-size: 16px;
            line-height: 26px;
        }
    }

    @media only screen and (max-width: 426px) {
        .hero {
            padding: 50px 50px;
            
        }

        .hero h1 {
            font-size: 32px;
            line-height: 50px;
        }
    }



</style>
