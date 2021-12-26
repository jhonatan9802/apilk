<template>
  <div class="container-fluid" id="app">
    <div class="row">
      <div class="col-12">
        <Main />
        <Navegacion />

        <div class="row">
          <div class="col-md-10 col-sm-12 mt-5 mx-auto">
            <div
              id="carouselExampleDark"
              class="carousel carousel-dark slide"
              data-bs-ride="carousel"
            >
              <div class="carousel-indicators">
                <button
                  type="button"
                  data-bs-target="#carouselExampleDark"
                  data-bs-slide-to="0"
                  class="active"
                  aria-current="true"
                  aria-label="Slide 1"
                ></button>
                <button
                  type="button"
                  data-bs-target="#carouselExampleDark"
                  data-bs-slide-to="1"
                  aria-label="Slide 2"
                ></button>
                <button
                  type="button"
                  data-bs-target="#carouselExampleDark"
                  data-bs-slide-to="2"
                  aria-label="Slide 3"
                ></button>
              </div>
              <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="2000">
                  <img
                    src="./../src/assets/img/banner/1639579150concurso fin de año BANNER (2) (1).jpg"
                    class="d-block w-100"
                    alt=""
                  />
                </div>
                <div class="carousel-item" data-bs-interval="2000">
                  <img
                    src="./../src/assets/img/banner/1639775085bannerejemplo (1).jpg"
                    class="d-block w-100"
                    alt=""
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="./../src/assets/img/banner/1637193899campañas nuevas diferenciales Camilo_Mesa de trabajo 1 copia 20 copy 2.png"
                    class="d-block w-100"
                    alt=""
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#carouselExampleDark"
                data-bs-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#carouselExampleDark"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
        </div>

        <div class="col-10 mx-auto mt-5">
          <h4 class="txt-purpel">Categorias</h4>
          <div
            class="
              row
              row-cols-1
              row-cols-sm-2
              row-cols-md-2
              row-cols-lg-6
              row-cols-xl-6
            "
          >
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-bone fa-3x"></i>
                    </div>
                    <div class="col-6">Snacks</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-home fa-3x"></i>
                    </div>
                    <div class="col-6">Accesorios</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-cat fa-3x"></i>
                    </div>
                    <div class="col-6">Higiene</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-cookie-bite fa-3x"></i>
                    </div>
                    <div class="col-6">Alimento</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-paw fa-3x"></i>
                    </div>
                    <div class="col-6">Juguetes</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body shadow-sm">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6 txt-purpel">
                      <i class="fas fa-capsules fa-3x"></i>
                    </div>
                    <div class="col-6">Farmapet</div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <h4 class="txt-purpel mt-5">Marcas destacadas</h4>
          <div
            class="
              row
              row-cols-2
              row-cols-sm-2
              row-cols-md-3
              row-cols-lg-6
              row-cols-xl-6
            "
          >
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/total_max_circulo2.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/hills_circulo4.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/eukanuba_circulo1.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/1624564683IMG_0153.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/1592410196_SALVAJE_FOOD_SAS__1226X1028.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card-body">
                <div class="row d-flex justify-content-center">
                  <img
                    class="w-50"
                    src="./../src/assets/img/marcas/1588258126_WHOLE_BARF_981X980.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
          <h4 class="txt-purpel mt-5">Un universo lleno de ofertas</h4>
          <div
            class="
              row
              row-cols-1
              row-cols-sm-2
              row-cols-md-3
              row-cols-lg-4
              row-cols-xl-4
            "
          >
            <div class="col mt-4" v-for="art in articulos" :key="art.id">
              <div class="card p-4">
                <div class="d-flex justify-content-between align-items-center">
                  <div class="mt-2">
                    <div class="row">
                      <img
                        src="./../src/assets/img/productos/10ea470d75cbb51a8bb86b925b53d885.jpg"
                        width="200"
                      />
                    </div>
                    <h5>{{ art.nombre }}</h5>
                    <div class="mt-3">
                      <div class="d-flex flex-row">
                        <div>
                          <i class="fa fa-star"></i> <i class="fa fa-star"></i>
                          <i class="fa fa-star"></i> <i class="fa fa-star"></i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="d-flex justify-content-between align-items-center mt-2"
                >
                  <span class="text-danger">$ {{ art.precio }}</span>
                  <span class="txt-gray"
                    ><small>Antes $ {{ art.precio_antes }}</small></span
                  >
                </div>
                <hr />
                <div class="d-flex justify-content-between align-items-start">
                  <span class="text-danger">$ {{ art.precio_member }}</span>
                  <div class="text-center">
                    <img
                      src="./../src/assets/img/laikamemeber.svg"
                      alt="laika memeber"
                      width="80"
                    /><br />
                    <button class="btn-member">Adquiérela Ya</button>
                  </div>
                </div>
                <div class="d-flex justify-content-center my-3">
                  <span
                    class="text-danger border border-1 p-2 rounded-2 text-black"
                    >{{ art.gramos }} GR</span
                  >
                </div>
                <button class="btn btn-add-to-cart mt-2 text-white">
                  <i class="fas fa-shopping-cart"></i> Añadir al Carrito
                </button>
              </div>
            </div>
          </div>
        </div>

        <Footer />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import axios from "axios";
import { Component, Vue } from "vue-property-decorator";
import Main from "./components/Main.vue";
import Navegacion from "./components/Navegacion.vue";
import Footer from "./components/Footer.vue";

@Component({
  components: {
    Main,
    Navegacion,
    Footer,
  },
  data() {
    return {
      articulos: null,
    };
  },
  mounted() {
    this.getArticulos();
  },
  methods: {
    getArticulos() {
      const url = "http://127.0.0.1:8000/api/articulos";
      axios
        .get(url)
        .then((res) => {
          console.log(res);
          this.articulos = res.data;
        })
        .catch((err) => console.log(err));
    },
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
  --yellow-claw: #f4bc0b;
  --sm: 14px;
  --md: 16px;
  --lg: 18px;
  --xl: 20px;
}

*,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: var(--Causten-SemiBold);
}

.txt-gray {
  color: var(--gray);
}

.txt-purpel {
  color: var(--bg_purpel);
  --semi_black: #212529;
}

.txt-s-black {
  color: var(--semi_black);
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

.content-search form div {
  width: 40vh;
}

.navbar-shoping-cart {
  position: relative;
}
.cart small {
  width: 18px;
  height: 18px;
  background-color: var(--bg_ultragray);
  border-radius: 50%;
  font-size: var(--sm);
  font-weight: bold;
  position: absolute;
  top: -10px;
  right: -7px;
  display: flex;
  justify-content: center;
}
.mega-menu {
  color: var(--bg_purpel);
  font-size: var(--md);
  box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
  -webkit-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
  -moz-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.09);
}

.mega-menu .dropdown-menu {
  width: 250px;
}

.menu-icon {
  margin-right: 16px;
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

.btn-add-to-cart {
  background-color: var(--bg_purpel) !important;
  color: var(--bg_white);
}

.btn-member {
  background-color: var(--yellow-claw);
  color: var(--bg_purpel);
  text-transform: uppercase;
  padding: 6px;
  border: none;
  border-radius: 4px;
  transition: 0.25s;
}
.btn-member:hover {
  box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.16);
  -webkit-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.16);
  -moz-box-shadow: 1px 3px 9px -1px rgba(0, 0, 0, 0.16);
}

.btn-accordion {
  color: var(--bg_purpel) !important;
}
.btn-accordion:not(.collapsed) {
  background-color: var(--bg_white) !important;
}
.accordion-item {
  border: none !important;
}

/* ============ mobile ============ */

@media (max-width: 640px) {
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

  .content-search ul li:nth-child(4) {
    position: absolute;
    top: 0;
    right: 24px;
    margin-top: 44px;
  }
  .content-search .account li span {
    display: none;
  }
  .content-search .account .user {
    position: relative;
    left: 205px;
    bottom: 90px;
  }
  .content-search .account .cart {
    position: relative;
    left: 10px;
    bottom: 90px;
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

  .mega-menu ul .nav-item {
    margin: 4px 10px;
  }

  .mega-menu ul {
    place-items: start;
  }
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