<template>
  <v-app>
    <v-main>
      <router-view/>
        <h1> Hello </h1>
    

    </v-main>
  </v-app>
</template>
<script>

export default {
  name: 'App',

  data: () => ({
    drawer: false,
    group: null,
  }),
};
</script>
