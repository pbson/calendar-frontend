<template>
  <v-app>
      <h1>Home page</h1>
  </v-app>
</template>

<script>
export default {
  data: () => ({
    step: 1,
  }),
  props: {
    source: String,
  },
};
</script>
