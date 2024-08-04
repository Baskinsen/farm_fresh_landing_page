<template>
  <footer>
    <div>
      <ul>
        <li>Home</li>
        <li>Menu</li>
        <li>About Us</li>
        <li>Contact Us</li>
      </ul>
      <ul>
        <li><img src="../assets/images/Linkedin.png" alt="Linkedin Logo" /></li>
        <li><img src="../assets/images/Facebook.png" alt="Facebook Logo" /></li>
        <li><img src="../assets/images/Twitter.png" alt="Twitter Logo" /></li>
        <li>
          <img src="../assets/images/Instagram.png" alt="Instagram Logo" />
        </li>
      </ul>
    </div>
    <div>
      <div>
<img src="../assets/images/Vector.png" alt="Copyright"><p>2022 FreshFarm</p>
      </div>
      
      <ul>
        <li>Privacy Policy</li>
        <li>Terms & Conditions</li>
        <li>Cookie Policy</li>
      </ul>
    </div>
  </footer>
</template>

<script></script>

<style scoped>
footer {
  background-color: #F5F5F5;
  padding:  50px 100px;
  display: grid;
  gap: 10px;
}

div {
     display: flex;
  justify-content: space-between;
  padding: 10px;
}

div:last-child{
  border-top: 1px solid #CDD0C8;
  display: flex;
  justify-content: space-between;

  & div {
    display: flex;
    gap: 10px;
    align-items: center;
    margin : auto 0;
    font-size: 16px;
  }

  & li {
    color: #11111180;
    font-size: 12px;
    font-weight: 400;
  }
}

div:has(img) p {
  font-size: 16px;
  font: 600;
  color: #11111180;
}

div:first-child > ul> li {
  color: #008000;
  font-size: 15px;
  font-weight: 500;
}

ul {
  margin: 0;
  padding: 0;
  margin : auto 0;
  list-style: none;
  display: flex;
  gap: 20px;

  & li {
    margin: 0;
    cursor: pointer;
  }
}
</style>
