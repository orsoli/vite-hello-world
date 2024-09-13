<script>
// Import componets
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default{
  components:{
    AppTitle,
    AppHero
  },

  data(){
    return{
    }
  }
}
</script>

<template>
  <!-- Call back AppTitle  -->
  <AppTitle/>
  <AppHero/>
</template>

<style scoped>
</style>
