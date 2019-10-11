<template>
  <v-container fluid>
    <v-layout row wrap>
      <the-product-card
        image-link="https://picsum.photos/id/248/3872/2592"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/1/5616/3744"
      ></the-product-card>
      <the-product-card
        image-link="https://picsum.photos/id/1025/4951/3301"
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
