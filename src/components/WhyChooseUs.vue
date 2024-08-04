<template>
  <section class="why_choose_us">
    <div class="discription">
      <h2>Why Choose Us</h2>
      <p>Want to know why we stand out from the rest? Here’s why!</p>
    </div>
    <div class="details">
      <div>
        <img src="../assets/images/board.png" alt="clipboard" />
        <h3>Easy To Order</h3>
        <p>Our Meals are easy to order and readily available</p>
      </div>
      <div>
        <img src="../assets/images/globe.png" alt="globe" />
        <h3>Worldwide Delivery</h3>
        <p>We deliver to everywhere in the world for a fee</p>
      </div>
      <div>
        <img src="../assets/images/plant.png" alt="plant" />
        <h3>100% Organic</h3>
        <p>Organic meals are grown without use of chemicals</p>
      </div>
    </div>
    <div class="stats">
      <div>
        <h2>400+</h2>
        <p>Food Partners</p>
      </div>
      <div>
        <h2>500+</h2>
        <p>Trusted Clients</p>
      </div>
      <div>
        <h2>10K+</h2>
        <p>Orders Online</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.why_choose_us {
  display: grid;
  gap: 50px;
}

.discription {
  text-align: center;
  display: grid;
  gap: 20px;
}

.discription h2 {
  font-size: 40px;
  font-weight: 700;
  line-height: 52.01px;
  margin: 0 auto;
}

.discription p {
    font-size: 20px;
    font-weight: 500;
    line-height: 32.4px;
}

.details {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
    width: 100%;
    
}

.details div {
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: center;
    border: 1px solid #3A3A3A1A;
    padding: 20px 20px;
    width: 100%;
}

.details img {
    width: 100px;
}

.details h3, p {
    text-align: center;
    padding: 0;
    margin: 0;
    font-size: 20px;
}

.details h3 {
    font-weight: 700;
    
}

.details p {
    font-weight: 500;
    line-height: 32.4px;
}

.stats {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
}

.stats div h2 {
    font-size: 32px;
    font-weight: 700;
    text-align: center;
    align-self: center;
    margin: 0;
    padding: 0;
    margin: 0 auto;
}

.stats div p {
    font-size: 20px;
    font-weight: 500;
    line-height: 32.4px;
    text-align: center;
    align-self: center;
    margin: 0;
    padding: 0;
}

@media only screen and (max-width: 1024px) {
  .why_choose_us {
    padding: 30px 50px;
  }


  .details div {
    width: 100%;
  }

  .details img {
    width: 50%;
  }

  
}
@media only screen and (max-width: 768px) {
  .why_choose_us {
    padding: 30px 50px;
  }

  .details {
    flex-direction: column;
    gap: 50px;
  }

  .details div {
    width: 50%;
  }

  .details img {
    width: 20%;
  }



  .stats div {
    width: 100%;
  }
}


@media only screen and (max-width:426px) {
  .why_choose_us {
    padding: 0px 50px;
  }

  .stats div h2 {
    font-size: 20px;
  }

  .stats div p {
    font-size: 16px;
    
  }
}

</style>
