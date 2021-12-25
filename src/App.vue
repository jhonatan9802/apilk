<template>
  <div id="app">
    <div class="row first-info">
      <div class="col-md-6 text-left d-flex justify-content-start">
        <ul>
          <li>Compras seguras online</li>
          <li>Pago Contra Entrega</li>
          <li>Entregas al mismo día</li>
        </ul>
      </div>
      <div class="col-md-6 text-right d-flex justify-content-end">
        <ul>
          <li>
            Llámanos <i class="fas fa-phone-square-alt mx-1"></i> | 3009108496
          </li>
          <li>
            Escribenos <i class="fab fa-youtube-square mx-1"></i>
            <i class="fab fa-facebook-square mx-1"></i>
            <i class="fab fa-instagram-square mx-1"></i>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Main from "./components/Main.vue";

@Component({
  components: {
    Main,
  },
})
export default class App extends Vue {}
</script>

<style>
@font-face {
  font-family: Causten-SemiBold;
  src: url("./../src/assets/fonts/Causten-Round/Causten-SemiBold.otf");
}

:root {
  --Causten-SemiBold: Causten-SemiBold;
  --bg_purpel: #603e85;
  --bg_white: #fff;
  --bg_ultragray: #242424;
  --semi_black: #212529;
  --very-light-gray: #c7c7c7;
  --gray: #616161;
  --sm: 14px;
  --md: 16px;
  --lg: 18px;
  --xl: 20px;
}

*,
body {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  box-sizing: border-box;
  font-family: var(--Causten-SemiBold);
}

.txt-gray {
  color: var(--gray);
}

.txt-purpel {
  color: var(--bg_purpel);
}

.first-info {
  background-color: black;
  color: var(--bg_white);
  font-size: var(--sm);
}

.text-left ul,
.text-right ul {
  display: flex;
  list-style: none;
  align-items: center;
  margin: 4px 12px;
}

.text-left ul li,
.text-right ul li {
  margin: 0 12px;
}

.content-search {
  background-color: var(--bg_purpel);
  padding: 10px 44px;
  border-bottom: 1px solid var(--very-light-gray);
}

.content-search ul {
  list-style: none;
  padding: 0;
  display: flex;
  align-items: center;
  height: 30px;
  margin-top: 18px;
}

.content-search ul li {
  margin: 0 20px;
}

.content-search form .search {
  width: 490px;
}

/*.navbar-shoping-cart{
         position: relative;
         }
         .navbar-shoping-cart div{
         width: 18px;
         height: 18px;
         background-color: var(--rusian-violet);
         border-radius: 50%;
         font-size: var(--sm);
         font-weight: bold;
         position: absolute;
         top: -8px;
         right: -6px;
         display: flex;
         justify-content: center;
         color: var(--white);
         }*/
.mega-menu {
  color: var(--bg_purpel);
  font-size: var(--md);
  box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
  -webkit-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
  -moz-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
}

#main_nav ul {
  place-items: center;
}

#main_nav ul .nav-item {
  margin: 4px 80px;
}

.mega-menu .nav-link {
  color: var(--bg_purpel);
  transition: 0.25s;
}

.mega-menu .nav-link:hover {
  background-color: var(--very-light-gray);
  border-radius: 5px;
}

.mega-menu .sub-menu a li i {
  margin-top: 8px;
}

/* ============ mobile ============ */

@media (max-width: 640px) {
  .first-info {
    display: none;
  }

  .content-search {
    padding: 0;
    height: 20vh;
  }

  .content-search ul {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    grid-gap: 16px;
  }

  .content-search ul li:nth-child(1) {
    display: flex;
    justify-content: center;
    margin-right: 90px;
  }

  .content-search ul li:nth-child(2) {
    display: flex;
    justify-content: center;
    margin-left: -170px;
  }

  .content-search ul li:nth-child(3) {
    width: 300px;
  }

  .content-search .btn-burger {
    background-color: var(--bg_white);
  }

  .content-search form .search {
    width: 259px;
  }

  .mega-menu {
    box-shadow: inherit;
  }

  #main_nav ul .nav-item {
    margin: 4px 10px;
  }

  #main_nav ul {
    place-items: start;
  }
}

.megasubmenu {
  padding: 1rem;
}

/* ============ desktop view ============ */
@media all and (min-width: 992px) {
  .megasubmenu {
    left: 100%;
    top: 0;
    min-height: 100%;
    min-width: 500px;
  }

  .dropdown-menu > li:hover .megasubmenu {
    display: block;
  }
}
</style>
