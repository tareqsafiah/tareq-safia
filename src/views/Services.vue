<template>
<div id="Services">
  <navbar id="nav"/>
  <v-content>
  <div class="continer px-4 px-lg-5 mt-5">
<div class="row">
  <div class="col-sm-12 col-md-3 col-12 down-2-anim" id="card1" style="position:relative">
    <div id="app">
  <v-app id="inspire">
    <v-hover v-slot="{ hover }">
      <v-card
        class="mx-auto"
        color="grey lighten-4"
        width="100%"
        height="100%"
      >
        <v-img
          :aspect-ratio="16/10"
          src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2440/Shape-2018-LR-106_d2799ae4d9532e75c7b76f8fe7c80560.webp"
        >
          <v-expand-transition>
            <div
              v-if="hover"
              class="d-flex transition-fast-in-fast-out Very light red v-card--reveal text-h2 white--text"
              style="height: 100%;"
            >
              Get Service ?
            </div>
          </v-expand-transition>
        </v-img>
        <v-card-text
          class="pt-6"
          style="position: relative;"
        >
          <v-btn
            absolute
            color="#ff7675"
            class="white--text"
            fab
            large
            right
            top
          >
            <a href="/GetService/" style="text-decoration:none; color:#dfe6e9;"><v-icon>mdi-cart-variant</v-icon></a>
          </v-btn>
          <div class="font-weight-light grey--text text-h6 mb-2">
            For the perfect
          </div>
          <h3 class="text-h4 font-weight-light Very light red--text mb-2">
            Web Design
          </h3>
          <div class="font-weight-light text-h6 mb-2">
            A website is a brands most important marketing tool. It can deliver rich content, to a wide audience in a short period of time.
          </div>
        </v-card-text>
      </v-card>
    </v-hover>
  </v-app>
</div>
  </div>
  <br><br>
<div class="col-sm-12 col-md-3 col-12 up-2-anim" id="card2" style="position:relative">
<v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      width="100%"
      height="100%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2492/Shape-2018-LR-172_d2799ae4d9532e75c7b76f8fe7c80560.webp"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out Very light red v-card--reveal text-h2 white--text"
            style="height: 100%;"
          >
            Get Service ?
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-6"
        style="position: relative;"
      >
        <v-btn
          absolute
          color="#ff7675"
          class="white--text"
          fab
          large
          right
          top
        >
          <a href="/GetService/" style="text-decoration:none; color:#dfe6e9;"><v-icon>mdi-cart-variant</v-icon></a>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light Very light red--text mb-2">
          SEO
        </h3>
        <div class="font-weight-light text-h6 mb-2">
          Increase the visibility of your website within search engines such as Google to increase traffic and revenue. Everything we do is organic.
        A website is a brands most important marketing tool.<br> It can deliver rich content, to a wide audience in a short period of time.
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
</v-app>
</div>
<br><br>
<div class="col-sm-12 col-md-3 col-12 down-2-anim" id="card3" style="position:relative">
<v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      width="100%"
      height="100%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/142670/Shape-2018-LR-100_5472332afa344033d2bf9e7b6b9d883e.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out Very light red v-card--reveal text-h2 white--text"
            style="height: 100%;"
          >
            Get Service ?
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-6"
        style="position: relative;"
      >
        <v-btn
          absolute
          color="#ff7675"
          class="white--text"
          fab
          large
          right
          top
        >
          <a href="/GetService/" style="text-decoration:none; color:#dfe6e9;"><v-icon>mdi-cart-variant</v-icon></a>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light Very light red--text mb-2">
          Craft CMS
        </h3>
        <div class="font-weight-light text-h6 mb-2">
          Craft CMS is our choice of content management system (CMS), that puts you in control of your content & layout.
        A website is a brands most important marketing tool.<br>
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
</v-app>
</div>
<br><br>
<div class="col-sm-12 col-md-3 col-12 up-2-anim" id="card4" style="position:relative">
 <v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      width="100%"
      height="100%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2440/Shape-2018-LR-106_d2799ae4d9532e75c7b76f8fe7c80560.webp"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out Very light red v-card--reveal text-h2 white--text"
            style="height: 100%;"
          >
            Get Service ?
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-6"
        style="position: relative;"
      >
        <v-btn
          absolute
          color="#ff7675"
          class="white--text"
          fab
          large
          right
          top
        >
          <a href="/GetService/" style="text-decoration:none; color:#dfe6e9;"><v-icon>mdi-cart-variant</v-icon></a>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light Very light red--text mb-2">
          Web Design
        </h3>
        <div class="font-weight-light text-h6 mb-2">
          A website is a brands most important marketing tool.<br> It can deliver rich content, to a wide audience in a short period of time.<br>
          A website is a brands most important marketing tool.<br> It can deliver rich content, to a wide audience in a short period of time.
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
 </v-app>
  </div>
  </div>
  </div>
  </v-content>
  <footer><h1><br></h1></footer>
</div>
</template>
<script>
import navbar from '../components/header.vue'
export default {
  name: 'Services',
  components: {
    navbar
  }
  // data: () => ({
  //   loading: false,
  //   selection: 1
  // }),
  // methods: {
  //   reserve () {
  //     this.loading = true

  //     setTimeout(() => (this.loading = false), 2000)
  //   }
  // }
}
</script>
<style>
 /* #about, #app{
  background-color:#2d3436 ;
  height: 100vh;
} */
/* #card1{
  margin-top: -30;
} */
@media screen and (max-width:600px) {
  .col-md-3 {
    width: 100%;
  }
}
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}
#card1{
  margin-top: 50px;

}
#card2{
  margin-top: 110px;
}
#card3{
  margin-top: 50px;
}
#card4{
  margin-top: 110px;
}
#nav{
  position: sticky;
  top:0;
  z-index: 10;
}
/* #Services{
background-color: #dfe6e9;
    opacity: 0.99;
height: 100%;
} */
.continer{
background-color: #dfe6e9;
    opacity: 0.99;
    height: 100%;
}
.up-2-anim {

    -webkit-animation: transation-up 2s;
    animation: transation-up 2s;
}
@keyframes transation-up{
  0% {
    opacity: 0;
    transform: translatey(40px);
}
100% {
    opacity: 1;
    transform: translateY(0);
}
}
.down-2-anim {

    -webkit-animation: transation-down 2s;
    animation: transation-down 2s;
}
@keyframes transation-down{
  0% {
    opacity: 0;
    transform: translatey(-40px);
}
100% {
    opacity: 1;
    transform: translateY(0);
}
}
</style>
