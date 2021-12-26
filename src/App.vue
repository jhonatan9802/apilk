<template>
  <div class="container-fluid" id="app">
    <div class="row">
      <div class="col-12">
        <!--Informacion de contacto-->
        <div class="row first-info d-none d-md-flex d-lg-flex">
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
                Llámanos <i class="fas fa-phone-square-alt mx-1"></i> |
                3009108496
              </li>
              <li>
                Escribenos <i class="fab fa-youtube-square mx-1"></i>
                <i class="fab fa-facebook-square mx-1"></i>
                <i class="fab fa-instagram-square mx-1"></i>
              </li>
            </ul>
          </div>
        </div>
        <!--Busqueda-->
        <div class="row content-search">
          <div class="col-md-6">
            <ul>
              <li class="d-md-none d-lg-none">
                <div class="navbar navbar-light">
                  <button
                    class="navbar-toggler btn-burger"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#main_nav"
                  >
                    <span class="navbar-toggler-icon text-white"></span>
                  </button>
                </div>
              </li>
              <li>
                <img src="./../src/assets/img/LaikaMascotas.svg" alt="logo" />
              </li>
              <li>
                <form class="d-flex">
                  <div class="input-group mb-sm-2">
                    <input
                      type="search"
                      class="form-control search"
                      placeholder="Encuentra lo mejor para tu mascota"
                    />
                    <button type="submit" class="input-group-text btn-search">
                      <i class="fas fa-search"></i>
                    </button>
                  </div>
                </form>
              </li>
            </ul>
          </div>
          <div class="col-md-6"></div>
        </div>
        <!--Navegación-->
        <div class="row">
          <div class="col-md-12">
            <nav class="navbar navbar-expand-lg mega-menu navbar-light">
              <div class="col-12">
                <div
                  class="
                    collapse
                    navbar-collapse
                    d-md-flex d-lg-flex
                    justify-content-evenly
                  "
                  id="main_nav"
                >
                  <ul class="navbar-nav">
                    <li class="nav-item dropdown">
                      <a
                        class="nav-link dropdown-toggle"
                        href="#"
                        data-bs-toggle="dropdown"
                      >
                        <img
                          src="./../src/assets/img/dog_mc.svg"
                          alt="Compra para Perro"
                        />
                        Perro
                      </a>
                      <ul class="dropdown-menu">
                        <li>
                          <a class="dropdown-item" href="#">
                            Dropdown item 1
                          </a>
                        </li>
                        <li>
                          <a class="dropdown-item" href="#">
                            Dropdown item 2
                          </a>
                        </li>
                        <li>
                          <a class="dropdown-item" href="#">
                            Dropdown item 3
                          </a>
                        </li>
                        <li class="has-megasubmenu">
                          <a class="dropdown-item" href="#">
                            Dropdown item 4 &raquo;
                          </a>
                          <div class="megasubmenu dropdown-menu">
                            <div class="row">
                              <div class="col-6">
                                <h6 class="title">Title Menu One</h6>
                                <ul class="list-unstyled">
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                </ul>
                              </div>
                              <!-- end col-3 -->
                              <div class="col-6">
                                <h6 class="title">Title Menu Two</h6>
                                <ul class="list-unstyled">
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                  <li><a href="#">Custom Menu</a></li>
                                </ul>
                              </div>
                              <!-- end col-3 -->
                            </div>
                            <!-- end row -->
                          </div>
                        </li>
                        <li class="has-megasubmenu">
                          <a class="dropdown-item" href="#">
                            Dropdown item 5 &raquo;
                          </a>
                          <div class="megasubmenu dropdown-menu">
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua. Ut enim ad minim veniam, quis
                            nostrud exercitation ullamco laboris nisi ut aliquip
                            ex ea commodo consequat. Duis aute irure dolor in
                            reprehenderit in voluptate velit esse cillum dolore
                            eu fugiat nulla pariatur. Excepteur sint occaecat
                            cupidatat non proident, sunt in culpa qui officia
                            deserunt mollit anim id est laborum. Lorem ipsum
                            dolor sit amet, consectetur adipisicing elit, sed do
                            eiusmod tempor incididunt ut labore et dolore magna
                            aliqua. Ut enim ad minim veniam, quis nostrud
                            exercitation ullamco laboris nisi ut aliquip ex ea
                            commodo consequat.
                          </div>
                        </li>
                        <li>
                          <a class="dropdown-item" href="#">
                            Dropdown item 6
                          </a>
                        </li>
                      </ul>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#"
                        ><img
                          src="./../src/assets/img/cat_mc_s.svg"
                          alt="Compra para Gato"
                        />
                        Gato
                      </a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#"> Ofertas </a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#"> Servicios </a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#"> Blog </a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">
                        <img
                          src="./../src/assets/img/membership_logo.png"
                          alt="membership"
                        />
                      </a>
                    </li>
                  </ul>
                </div>
                <!-- navbar-collapse.// -->
              </div>
              <!-- container-fluid.// -->
            </nav>
          </div>
        </div>
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

        <div class="col-10 mx-auto my-4">
          <h4 class="txt-purpel">Categorias</h4>
          <div class="row row-cols-1 row-cols-sm-2 row-cols-md-6">
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6"><i class="fas fa-bone fa-3x"></i></div>
                    <div class="col-6">Snacks</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6"><i class="fas fa-home fa-3x"></i></div>
                    <div class="col-6">Accesorios</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6"><i class="fas fa-cat fa-3x"></i></div>
                    <div class="col-6">Higiene</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6">
                      <i class="fas fa-cookie-bite fa-3x"></i>
                    </div>
                    <div class="col-6">Alimento</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6"><i class="fas fa-paw fa-3x"></i></div>
                    <div class="col-6">Juguetes</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col my-2">
              <div class="card">
                <div class="card-body">
                  <div class="row align-items-center text-center txt-gray">
                    <div class="col-6">
                      <i class="fas fa-capsules fa-3x"></i>
                    </div>
                    <div class="col-6">Farmapet</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <hr />
          <h4 class="txt-purpel">Marcas destacadas</h4>
          <div class="row row-cols-2 row-cols-sm-2 row-cols-md-6">
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
          <hr />
          <h4 class="txt-purpel">Un universo lleno de ofertas</h4>
          <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 row-cols-lg-4">
            <div class="col-md-2 mt-4" v-for="art in articulos" :key="art.id">
              <div class="card p-4">
                <div class="d-flex justify-content-between align-items-center">
                  <div class="mt-2">
                    <div class="row">
                      <img
                        src="./../src/assets/img/productos/10ea470d75cbb51a8bb86b925b53d885.jpg"
                        width="200"
                      />
                    </div>
                    <h5>{{ art.name }}</h5>
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
                  <span class="text-danger">$ 13.400</span>
                  <span class="txt-gray"><small>Antes $ 14.400</small></span>
                </div>
                <hr />
                <div class="d-flex justify-content-between align-items-start">
                  <span class="text-danger">$ 13.400</span>
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
                    >15GR</span
                  >
                </div>
                <button class="btn btn-add-to-cart mt-2 text-white">
                  <i class="fas fa-shopping-cart"></i> Añadir al Carrito
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import axios from "axios";
import { Component, Vue } from "vue-property-decorator";
import Main from "./components/Main.vue";

@Component({
  components: {
    Main,
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
      const url = "https://jsonplaceholder.typicode.com/users";
      axios
        .get(url)
        .then((res) => {
          console.log(res);
          this.articulos = res.data;
        })
        .catch((e) => console.log(e));
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
.btn-add-to-cart {
  background-color: var(--bg_purpel) !important;
  color: var(--bg_white);
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
