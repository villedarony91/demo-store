<template>
  <v-container fluid>
    <v-layout row wrap>
      <the-product-card
        image-link="https://picsum.photos/id/248/3872/2592"
        style="margin: 1em"
        header="Cactus"
        author="Viverito"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/1/5616/3744"
        style="margin: 1em"
        header="Servicios de programacion"
        author="Allium"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/1025/4951/3301"
        style="margin: 1em"
        header="Se vende perro"
        author="Adoptame"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/152/3888/2592"
        style="margin: 1em"
        header="Arreglo de flores"
        author="Viverito"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/1080/6858/4574"
        style="margin: 1em"
        header="Fresas a granel"
        author="Eres Fresa"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/111/4400/2656"
        style="margin: 1em"
        header="Automovil"
        author="Pedro Perez"
      ></the-product-card>
    </v-layout>
  </v-container>
</template>

<script>
import TheProductCard from '../components/TheProductCard'
export default {
  components: { TheProductCard }
}
</script>
