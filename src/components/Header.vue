<template>
  <header>
    <nav>
      <img src="../assets/images/FreshFarm.svg" alt="Farmfreh logo" class="logo" />
      <div @click="toggleNav">
        <img v-if="!showMobileNav" src="../assets/images/menu.png" alt="menu" class="menu"  />
        <img  v-else src="../assets/images/icon-menu-close.svg" alt="close menu">
      </div>
      
      <div class="nav_container" id="nav" ref="nav">
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">About</a></li>
          <li><a href="">Contact Us</a></li>
          <li><a href="">Testimonials</a></li>
        </ul>
        <ul class="login_order">
          <li>
            <a href="#">Login</a>
          </li>
          <li class="order_button">
            <button>
              <a href="#">Order Now</a>
            </button>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script setup>
import { onMounted, ref } from "vue";

const showMobileNav = ref(false);
// const menu = ref(null);
// const nav = ref(null)
// onMounted(() => {
//   menu.value.addEventListener("click", () => {
//     console.log(menu.value.src)
//     menu.value.src =
//       nav.value.style.display == "none"
//         ? "../assets/images/icon-menu-close.svg"
//         : "../assets/images/menu.png";
//    nav.value.style.display == "none"
//       ? (nav.value.style.display = "block")
//       : (nav.value.style.display = "none");
//   });
// });

const toggleNav = () => {
  showMobileNav.value = !showMobileNav.value;
};
</script>

<style scoped>
body {
  margin: 0;
  padding: 0;
  font-family: "Inter", sans-serif;
  font-optical-sizing: auto;
}

header {
  padding: 30px 50px;
  width: 100%;
}

nav {
  display: flex;
  justify-content: space-between;
}

nav ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 50px;
  margin: 0;
  padding: 0;
}

.nav_container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 150px;
  margin: 0;
  padding: 0;
}

nav ul li {
  list-style: none;
}

.login_order {
  gap: 30px;
}

button {
  padding: 10px 30px;
  background-color: #008000;
  border: none;
  color: #ffffff;
  font-size: 18px;
  border-radius: 5px;
}

button a {
  color: #ffffff;
}

.order_button a {
  color: #ffffff;
}

a {
  text-decoration: none;
  margin: 0;
  color: #000000;
  font-size: 18px;
}

.menu {
  display: none;
  position: relative;
  z-index: 1;
  float: right;
  cursor: pointer;
}

@media only screen and (max-width: 1440px) {
  header {
    padding: 30px 50px;
  }

  nav {
    gap: 100px;
  }

  .nav_container {
    gap: 100px;
  }

  

}

@media only screen and (max-width: 1046px) {
    header {
        padding: 30px 50px;
        width: 100%;
    }

    .logo {
        width: 15%;
    }

    nav {
        gap: 30px;
        padding: 0;
    }

    .nav_container {
        gap: 30px;
    }
    
    
}

@media only screen and (max-width: 768px) {
  header {
    padding: 30px 50px;
    width: 100%;
  }
  nav {
    align-items: center;
    
    gap: 70dvw;
  }
  .menu {
    display: initial;
    float: right;
    left: 10dvw;
  }
  .nav_container {
    position: absolute;
    top: 0;
    right: 0;
    display: none;
    background: #008000;
    height: 100dvh;
    width: 40%;
    padding: 50px 30px;
  }

  nav {
    justify-content: flex-start;
  }

  nav ul {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    gap: 50px;
    margin: 0;
    padding: 0;
  }

  a {
    color: #ffffff;
  }

  .order_button {
    padding: 10px 30px;
    background-color: #ffffff;
    cursor: pointer;
    border-radius: 5px;
  }

  .order_button button {
     background-color: #ffffff;
     padding: 0;
     border-radius: 0;
  }

  .order_button a {
    color: #008000;
  }
}

@media only screen and (max-width: 426px) {
  .logo {
    width: 30%;
  }

  header {
    padding: 30px 50px;
  }

  nav {
    gap: 50dvw;
  }
  .nav_container {
    width: 40%;
  }
}

@media only screen and (max-width: 376px) {
    header {
        padding: 30px 30px;
    }
  .nav_container {
    width: 45%;
    right: -10dvw;
  }
}

@media only screen and (max-width: 321px) {
  header {
    padding: 30px 20px;
  }
  nav {
    justify-content: space-between;
  }

  .menu {
    display: initial;
    float: right;
    left: 0dvw;
  }

  .nav_container {
    width: 50%;
    right: -10dvw;
  }
}
</style>
