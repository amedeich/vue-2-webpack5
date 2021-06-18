<style>
.container {
  width: 800px;
  margin: auto;
  padding: 1rem;
}
.detail {
  display: grid;
  grid-template-columns: 30% 70%;
  grid-column-gap: 1rem;
}
.detail img {
  width: 100%;
}
</style>

<template>
<v-app>
      <v-main>
        <v-container>Hello world</v-container>
        <v-btn
      depressed
      color="primary"
    >
      Primary
    </v-btn>
      </v-main>
    </v-app>
</template>

<script>

export default {
}
</script>