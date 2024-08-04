<template>
  <section>
    <h2>Subscribe to Our Newsletter</h2>
    <h4>Enter your Email Address below to get daily offers and news</h4>
    <div>
        <input type="text" placeholder="Enter your Email">
        <button>Join Our Mail List</button>
    </div>
  </section>
</template>

<script>

</script>

<style scoped>
    section {
        display: flex;
        flex-direction: column;
        gap: 20px;
        align-items: center;
        margin: 0 auto;
        width: 600px;
    }

    h2, h4 {
        margin: 0;
    }

    h2 {
        font-size: 40px;
        font-weight: 700;

    }

    h4 {
        font-size: 20px;
        font-weight: 500;
    }

    div {
        display: grid;
        grid-template-columns: 55% 30%;
        gap: 100px;
        width: 100%;
    }

    input {
        width: 100%;
        padding: 15px 30px;
        border: 1px solid #3A3A3A40;
        border-radius: 5px;
        font-size: 18px;
    }

    button {
        width: 100%;
        font-size: 18px;
        padding: 15px 20px;
    }
</style>