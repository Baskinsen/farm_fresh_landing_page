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
  width: 100%;
  gap: 100px;
}

img {
    width: 100%;
    margin: 0 auto;
}

div:has(img) {
    width: 100%;
    margin: 0 auto;
    height: 100%;
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
</style>
