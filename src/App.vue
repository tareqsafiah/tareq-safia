<template>
<v-app>
<div class="continer-fluid"  id="app">
<!-- <v-app-bar app> -->
    <!-- <div class="continer" id="app"> -->
        <router-view></router-view>
            <v-footer padless>
    <v-col
      class="text-center"
      cols="12"
    >
      <strong>Copyright ©</strong> {{ new Date().getFullYear() }} <strong>Tareq Safiah. all rights reserved.</strong>
    </v-col>
  </v-footer>
    <!-- </div> -->
<!-- </v-app-bar> -->
</div>
</v-app>
</template>

<script>
export default {
  name: 'app'
}
</script>
