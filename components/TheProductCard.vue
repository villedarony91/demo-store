<template>
  <v-card max-width="344">
    <v-list-item>
      <v-list-item-avatar color="grey"></v-list-item-avatar>
      <v-list-item-content>
        <v-list-item-title class="headline"
          >Our Changing Planet</v-list-item-title
        >
        <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
      </v-list-item-content>
    </v-list-item>
    <v-img :src="imageLink" height="194"></v-img>
    <v-card-text>
      Visit ten places on our planet that are undergoing the biggest changes
      today.
    </v-card-text>

    <v-card-actions>
      <v-btn text color="deep-purple accent-4">
        Read
      </v-btn>
      <v-btn text color="deep-purple accent-4">
        Bookmark
      </v-btn>
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
    imageLink: {
      type: String,
      default: ''
    }
  },
  computed: {
    transformedUrl() {
      return ''
    }
  }
}
</script>

<style scoped></style>
