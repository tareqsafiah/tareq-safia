<template>
<v-app>
<div class="container-fluid mt-3"  id="app">
      <navbar id="nav"/>
        <router-view></router-view>
            <v-footer padless>
    <v-col
      class="text-center"
      cols="12"
    >
      <strong>Copyright ©</strong> {{ new Date().getFullYear() }} <strong>Tareq Safiah. all rights reserved.</strong>
    </v-col>
  </v-footer>
</div>
</v-app>
</template>

<script>
import navbar from './components/header.vue'
export default {
  name: 'app',
  components: {
    navbar
  }
}
</script>
<style>
#nav{
  position: sticky;
  top:0;
  z-index: 10;
}
</style>
