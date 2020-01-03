<template>
  <v-app id="app">
    <router-view/>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },

  data: () => ({
    //
  }),
};
</script>
<style>
h1{
  font-family: Bw Modelica;
font-style: normal;
font-weight: 800;
font-size: 61px;
}
h2{
  font-family: Bw Modelica;
font-style: normal;
font-weight: 800;
font-size: 69px;
}
button{
  font-family: Bw Modelica;
font-weight: 800;
font-size:20px;
}
</style>