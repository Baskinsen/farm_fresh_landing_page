<template>
  <section class="why_choose_us">
    <div class="discription">
      <h2>Special Dishes For All</h2>
      <p>Made with premium & 100% Organic vegetables</p>
    </div>
    <div class="details">
      <div>
        <img src="../assets/images/unsplash_mW0LIBBHNdE.png" alt="clipboard" />
        <h3>Green Salad</h3>
        <p>
          A salad combined with a delicious cut of bacon and mixed with tasty
          and fresh sesame oil
        </p>
      </div>
      <div>
        <img src="../assets/images/unsplash_bBzjWthTqb8.png" alt="globe" />
        <h3>Beef Salad</h3>
        <p>
          A salad combined with a delicious cut of bacon and mixed with tasty
          and fresh sesame oil
        </p>
      </div>
      <div>
        <img src="../assets/images/unsplash_kcA-c3f_3FE.png" alt="plant" />
        <h3>Nut Salad</h3>
        <p>
          A salad combined with a delicious cut of bacon and mixed with tasty
          and fresh sesame oil
        </p>
      </div>
    </div>
  <button>View All</button>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.why_choose_us {
  display: flex;
  flex-direction: column;
  gap: 50px;
  align-items: flex-start;
}

.discription {
  text-align: center;
  display: grid;
  gap: 20px;
  margin: 0 auto;
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
  gap: 100px;
  width: 100%;
}

.details div {
  display: flex;
  flex-direction: column;
  gap: 20px;
  align-items: center;
  border: 1px solid #3a3a3a1a;
  padding: 20px 50px;
  width: 100%;
}

.details img {
  width: 70%;
}

.details h3,
p {
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
  font-size: 14px;
  color: #3A3A3A;
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

button {
  margin: 0 auto;
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

@media only screen and (max-width: 426px) {
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
