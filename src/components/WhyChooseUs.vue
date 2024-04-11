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
    <div>
      <div>
        <h1>400+</h1>
        <p>Food Partners</p>
      </div>
      <div>
        <h1>500+</h1>
        <p>Trusted Clients</p>
      </div>
      <div>
        <h1>10K+</h1>
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
  padding: 30px 150px;
}

.discription {
  text-align: center;
}

.discription h2 {
  font-size: 40px;
  font-weight: 700;
  line-height: 52.01px;
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
}
</style>
