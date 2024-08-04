<template>
  <section>
    <div>
      <h2>About Us</h2>
      <p>
        Organic food is grown without the use of synthetic chemicals, such as
        human-made pesticides and fertilizers, and does not contain genetically
        modified organisms (GMOs). Organic foods induce fresh produce, meats and
        dairy products as well as processed foods such as crackers, drinks, and
        frozen meals.
      </p>
      <button>Learn More</button>
    </div>
    <div>
      <img
        src="../assets/images/about_us/Rectangle 6.svg"
        alt="About us Imgae"
      />
      <img
        src="../assets/images/about_us/Rectangle 8.svg"
        alt="About Us Image"
      />
      <img
        src="../assets/images/about_us/Rectangle 7.svg"
        alt="About Us Image"
      />
    </div>
  </section>
</template>

<script></script>

<style scoped>
section {
  display: grid;
  grid-template-columns: 35% 60%;
  gap: 80px;
  height: 100vh;
 
}

div:first-child {
  display: flex;
  flex-direction: column;
  gap: 10px;
  align-items: flex-start;
  height: 100%;
  margin: auto 0;
  justify-content: center;
  & h2 {
    font-size: 40px;
    font-weight: 700;
    color: #000000;
    margin: 0;
    padding: 0;
  }

  & p {
    font: 16px 500;
    line-height: 32.4px;
    align-items: start;
  }
}

div:last-child {
  display: grid;
  grid-template-rows: 50% 50%;
  grid-template-columns: 45% 55%;
  column-gap: 30px;
  height: 100%;
  width: 100%;
}

img {
  width: 100%;
  height: 100%;
}

img:first-child {
  grid-column: span 1;
  grid-row: span -1;
  margin: auto 0;
}
img:nth-child(2) {
  grid-column: 1;
  grid-row: 1;
  margin: auto 0;
}

img:last-child {
  grid-column: span 1/-1;
  grid-row: span 2/2;
  margin: auto 0;
  width: 100%;
}
</style>
