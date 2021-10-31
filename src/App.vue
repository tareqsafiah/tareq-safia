<template>
<v-app>
    <div class="continer xs-12 sm-6 md-4 lg-3"  id="headerDemo">
      <!-- <tollbar></tollbar> -->
        <router-view></router-view>
<!-- <div class="row">
        <carou></carou>
        </div> -->
    </div>
</v-app>
</template>

<script>
// import tollbar from './components/header'
// import call from './components/slideshow.html'
// import teeeet from './components/background'
// import foot from "./components/footer";

// import carou from './components/caro'

export default {
  name: 'headerDemo'
  // components: {
  //   tollbar
  //   // teeeet,
  //   carou
  //   // call
  // }
}
</script>
