<template style="margin: 2em">
  <v-card max-width="344">
    <v-list-item>
      <v-list-item-avatar color="grey"></v-list-item-avatar>
      <v-list-item-content>
        <v-list-item-title class="headline">{{ header }}</v-list-item-title>
        <v-list-item-subtitle>by {{ author }}</v-list-item-subtitle>
      </v-list-item-content>
    </v-list-item>
    <v-img :src="imageLink" height="194"></v-img>
    <v-card-text>
      {{ header }}
    </v-card-text>

    <v-card-actions>
      <div class="flex-grow-1"></div>
      <v-btn icon>
        <v-icon>mdi-eco</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-cart</v-icon>
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: 'TheProductCard',
  props: {
    header: {
      type: String,
      default: ''
    },
    imageLink: {
      type: String,
      default: ''
    },
    author: {
      type: String,
      default: ''
    }
  }
}
</script>

<style scoped></style>
