<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";

export default {
components: {
  AppHeader,
  AppMain,
},

  data() {
    return {
      prova: "ciao",
    }
  },

  methods: {
    ciao() {
      console.log(this.prova);
    }
  },

  mounted() {
    this.ciao();
  },
}
</script>

<template>
  <AppHeader/>
  <AppMain/>
</template>

<style scoped>


</style>
