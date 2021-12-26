<template>
  <!--Informacion de contacto-->
  <div class="row first-info d-none d-md-none d-lg-flex">
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
  
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Main extends Vue {
  @Prop() private msg!: string;
}
</script>
