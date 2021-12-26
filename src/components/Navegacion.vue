<template>
  <!--Busqueda-->
  <div>
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
            <img src="../../src/assets/img/LaikaMascotas.svg" alt="logo" />
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
          <li>
            <div class="text-white align-items-center">
              <i class="fas fa-flag-usa text-white menu-icon"></i>
              <span>USA</span>
            </div>
          </li>
        </ul>
      </div>
      <div class="col-md-6 account">
        <ul class="d-flex justify-content-end text-white">
          <li><i class="far fa-user me-2 user"></i> <span>Mi cuenta</span></li>
          <div class=""><li class="position-relative cart"><i class="fas fa-shopping-cart"></i> <small>2</small></li></div>
        </ul>
      </div>
    </div>
    <!--Navegación-->
    <div
      class="
        row
        row-cols-1
        row-cols-sm-12
        row-cols-md-12
        row-cols-lg-12
        row-cols-xl-12
      "
    >
      <div class="col">
        <nav class="navbar navbar-expand-lg mega-menu navbar-light p-0">
          <div
            class="
              collapse
              navbar-collapse
              d-md-flex d-lg-flex
              justify-content-evenly
            "
            id="main_nav"
          >
            <ul class="navbar-nav text-s-black align-items-center">
              <li class="nav-item dropdown mx-5">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  data-bs-toggle="dropdown"
                >
                  <img
                    src="../../src/assets/img/dog_mc.svg"
                    alt="Compra para Perro"
                  />
                  Perro
                </a>
                <ul class="dropdown-menu">
                  <li>
                    <a class="dropdown-item p-3" href="#">
                      <div
                        class="
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                      >
                        <div>
                          <i
                            class="fas fa-cookie-bite txt-purpel mr-4 menu-icon"
                          ></i>
                          <span>Alimento</span>
                        </div>

                        <i class="fas fa-chevron-right"></i>
                      </div>
                    </a>
                  </li>
                  <li>
                    <a class="dropdown-item p-3" href="#">
                      <div
                        class="
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                      >
                        <div>
                          <i class="fas fas fa-bone txt-purpel menu-icon"></i>
                          <span>Snacks</span>
                        </div>

                        <i class="fas fa-chevron-right"></i>
                      </div>
                    </a>
                  </li>
                  <li>
                    <a class="dropdown-item p-3" href="#">
                      <div
                        class="
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                      >
                        <div>
                          <i class="fas fa-capsules txt-purpel menu-icon"></i>
                          <span>Farmapet</span>
                        </div>

                        <i class="fas fa-chevron-right"></i>
                      </div>
                    </a>
                  </li>
                  <li class="has-megasubmenu">
                    <a class="dropdown-item p-3" href="#">
                      <div
                        class="
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                      >
                        <div>
                          <i class="fas fa-paw txt-purpel menu-icon"></i>
                          <span>Juguetes</span>
                        </div>

                        <i class="fas fa-chevron-right"></i>
                      </div>
                    </a>
                  </li>
                  <li>
                    <a class="dropdown-item p-3" href="#">
                      <div
                        class="
                          d-flex
                          justify-content-between
                          align-items-center
                        "
                      >
                        <div>
                          <i class="fas fa-home txt-purpel menu-icon"></i>
                          <span>Accesorios</span>
                        </div>

                        <i class="fas fa-chevron-right"></i>
                      </div>
                    </a>
                  </li>
                </ul>
              </li>
              <li class="nav-item mx-5">
                <a class="nav-link" href="#"
                  ><img
                    src="../../src/assets/img/cat_mc_s.svg"
                    alt="Compra para Gato"
                  />
                  Gato
                </a>
              </li>
              <li class="nav-item mx-5">
                <a class="nav-link" href="#"> Ofertas </a>
              </li>
              <li class="nav-item mx-3">
                <a class="nav-link" href="#"> Servicios </a>
              </li>
              <li class="nav-item mx-3">
                <a class="nav-link" href="#"> Blog </a>
              </li>
              <li class="nav-item mx-3">
                <a class="nav-link" href="#">
                  <img
                    src="../../src/assets/img/membership_logo.png"
                    alt="membership"
                  />
                </a>
              </li>
            </ul>
          </div>
        </nav>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Navegacion extends Vue {
  @Prop() private msg!: string;
}
</script>
