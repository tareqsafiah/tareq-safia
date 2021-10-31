<template>
<v-app id="home">
    <navbar id="nav"/>
    <bodyy/>
</v-app>
</template>

<script>
import navbar from '../components/header.vue'
import bodyy from '../components/body.vue'
export default {
  name: 'home',
  components: {
    navbar,
    bodyy
  }
}
</script>
<style scoped>
#home{
background-color: #dfe6e9;
    opacity: 0.99;
height: 100%;
}
/* .continer{
background-color: #dfe6e9;
    opacity: 0.99;
    height: 100%;
} */
#nav{
  position: sticky;
  top:0;
  z-index: 10;
}
</style>
