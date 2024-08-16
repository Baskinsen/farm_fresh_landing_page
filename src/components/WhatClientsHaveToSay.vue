<template>
  <section class="what_clients_have">
    <div class="discription">
      <h2>What Our Clients Have To Say</h2>
    </div>
    <div class="details">
      <div class="details_div">
        <div>
          <img src="../assets/images/Ellipse 1.png" alt="" />
          <div>
            <h3>Reykiya Ahmad</h3>
            <h4>CEO Brandkit</h4>
          </div>
        </div>
        <p>
          Getting organic healthy meals has been a chore for me until I started
          using FreshFarm. My meals are delivered on time and I don’t have to
          stress or worry. I totally recommend them.
        </p>
      </div>
      <div class="details_div">
        <div>
          <img src="../assets/images/Frame.png" alt="" />
          <div>
            <h3>Hope Raymonds</h3>
            <h4>CEO GrowthBank</h4>
          </div>
        </div>
        <p>
          Getting organic healthy meals has been a chore for me until I started
          using FreshFarm. My meals are delivered on time and I don’t have to
          stress or worry. I totally recommend them.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.what_clients_have {
  display: flex;
  flex-direction: column;
  gap: 50px;
  align-items: flex-start;
  width: 100%;
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

.details {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 100px;
  width: 100%;
}

.details_div {
  display: flex;
  flex-direction: column;
  gap: 20px;
  align-items: start;
  border: 1px solid #3a3a3a1a;
  padding: 20px 50px;
  width: 100%;
}

.details_div div {
    display: flex;
    gap: 20px;
    align-items: center;
    width: 100%;
    & div {
        display: flex;
        flex-direction: column;
        align-items: self-start;
        gap: 10px;

        & h4 {
            font-size: 16px;
            font-weight: 500;
            color: #3a3a3a;
            text-align: center;
            margin: 0;
        }
    }


}

.details img {
  width: 70%;
}

.details h3{
  padding: 0;
  margin: 0;
  font-size: 20px;
  font-weight: 700;
}

.details p {
  font-weight: 500;
  line-height: 32.4px;
  font-size: 14px;
  color: #3a3a3a;
  text-align: justify;
}


@media only screen and (max-width: 1024px) {
  .what_clients_have {
    padding: 0;
    width: 100%;
  }

  .details div {
    width: 100%;
  }

  .details img {
    width: 100%;
  }
}
@media only screen and (max-width: 768px) {
  .what_clients_have {
    padding:0;
    width: 100%;
  }

  .details {
    flex-direction: column;
    gap: 50px;
  }

  .details div {
    width: 75%;
  }

  .details img {
    width: 20%;
  }


}

@media only screen and (max-width: 426px) {

  .what_clients_have {
    padding: 0;
  
  }

  .discription h2 {
    font-size: 30px;
    line-height: 40px;
  }

  .details {
    width: 100%;

  }

  .details_div {
    width: 100%;
  }

  .details div {
    width: 100%;
  }

  
}
</style>
