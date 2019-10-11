<template>
  <v-container fluid>
    <v-layout row wrap>
      <the-product-card></the-product-card>
      <the-product-card></the-product-card>
      <the-product-card></the-product-card>
      <the-product-card></the-product-card>
    </v-layout>
  </v-container>
</template>

<script>
import TheProductCard from '../components/TheProductCard'
export default {
  components: { TheProductCard }
}
</script>
