<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppMinaCard from "./components/AppMainCard.vue";

export default {
components: {
  AppHeader,
  AppMain,
  AppMainCard,
  
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
  
</template>

<style scoped>

</style>
