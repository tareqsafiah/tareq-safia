قسم الbody components
<template>
 <div id="ed">
    <div class="row">
            <v-card id="midd">
                <v-col align-self="start" cols="12">
                    <v-avatar class="profile" color="black" size="300">
                        <v-img src="https://cdn.vuetifyjs.com/images/profiles/marcus.jpg"></v-img>
                    </v-avatar>
                </v-col>
            </v-card>
    </div>
  <div class="row">
      <div class="mid" cols="12">
          <div id="t1" class="test1 font-weight-bold">
              <i>Welcome In My Protfolio</i>
          </div><br><br><br>
          <div id="t2" class="test2 font-weight-light font-italic">
              <i>I'm Tareq</i>
            </div><br>
          <div id="t3" class="test3 font-weight-light font-italic">
              <i>I'm Front-End Developer</i>
            </div>
          <div id="t4" class="line"></div>
          <div class="middel">
            <a href="/MyWork/" class="btn btn1">Review My Work's</a>
          </div>
      </div>
    </div>
 </div>
</template>
<script>
export default {
  name: 'ed',
  data () {
    return {
      ed: ''
    }
  }
}
</script>
<style scoped>
#midd {
    background-color: transparent;
    border: 0px;
    box-shadow: 0px 0px 0px 0px;
    opacity: 1;
    margin-left: 70%;

}
/* @media screen and (max-width:600px) {
  .column {
    width: 100%;
  }
} */
@media screen and (max-width:600px) {
  .colm {
    width: 100%;
  }
}

/* #midd :hover{
    height: 310px;
} */

#t1,
#t2,
#t3
{
  color: #dfe6e9;
  font-size: 30px;
  left: 10%;
  display: inline;
  width: 100px;
  height: 50px;
  font-weight: bold;
  position: relative;
  animation-name: mymove;
  animation-duration: 5s;
  animation-iteration-count: 1;
    animation-timing-function: ease;
    /* font-family: weight-bold; */
}
@keyframes mymove {
  from {left: -110%;}
  to {color:white; left: 150px; font-family:Georgia, 'Times New Roman', Times, serif; font-size: 40px;
}
}
#t1 :hover{
color: #ff7675;

}
#t2 :hover{
color: #ff7675;
}
#t3
 :hover{
color: #ff7675;
}
        .btn{
            left: 10%;
            padding: 14px 50px;
            position: relative;
            display: block;
            color: #dfe6e9;
            font-size: 24px;
            font-family: "monttserrat";
            text-decoration: none;
            margin: 30px 0;
            border: 2px solid #ff7675;
            padding: 14px 50px;
            overflow: hidden;
            transition: 1s all ease;
            border-radius: 10px;
            text-align: center;
            animation-name: mybtn;
            animation-duration: 5s;
            animation-iteration-count: 1;
            animation-timing-function: ease;
        }
@keyframes mybtn {
  from {left: -110%;}
  to {color:white; left: 150px; font-family:Georgia, 'Times New Roman', Times, serif; font-size: 40px;
}
        }
        .btn::before{
          text-decoration: none;
            background: #ff7675;
            content: "";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: -1;
            transition: all 0.6s ease;
        }
        .btn1::before{
            width: 100%;
            height: 0;
            transform: translate(-50%, -50%) rotate(45deg);
        }
        .btn1:hover::before{
            height: 580%;
        }
</style>

-------------------------------------------------------------------------------
قسم الhome
<template>
<v-app>
<div class="continer" id="home">
    <navbar id="nav"/>
    <midd></midd>
</div>
</v-app>
</template>

<script>
import midd from '../components/body.vue'
import navbar from '../components/header.vue'
export default {
  name: 'home',
  components: {
    midd,
    navbar
  }
}
</script>
<style>
#home{
background-color: #2d3436;
height: 100%;
}
</style>
--------------------------------------------------
قسم الheader
<template>
  <div id="navbar">
    <v-toolbar
      dark
    >
    <v-toolbar-items  id="titl">
      <v-toolbar-title><v-btn flat depressed>Tareq Safiah</v-btn></v-toolbar-title>
    </v-toolbar-items>
      <v-spacer></v-spacer>
      <v-toolbar-items id="itm">
      <v-btn id="bt1" flat depressed to="/">Home</v-btn>
      <v-btn id="bt2" flat depressed to="/Services/">Services</v-btn>
      <v-btn id="bt3" flat depressed to="/MyWork/">My Work</v-btn>
      <v-btn id="bt3" flat depressed to="/contact/">Contact</v-btn>

      </v-toolbar-items>
      <v-btn icon>
        <v-icon>mdi-export</v-icon>
      </v-btn>
    </v-toolbar>
  </div>
</template>
<script>
export default {
  name: 'navbar',
  data () {
    return {
      // name: 'TAREQ SAFIAH'
    }
  }
}
</script>
<style>
#itm{
  border-radius: 25px;
}
#itm :hover{
background-color: #ff7675;
text-decoration: double;
color: black;
border-bottom: 3px;
}
#bt1 :hover{
  background-color: transparent;
}
#bt2 :hover{
  background-color: transparent;
}
#bt3 :hover{
  background-color: transparent;
}
#titl{
  /* background-color: rgb(233, 224, 224); */
top: 10px;
}
#titl :hover{
    transform: rotateZ(360deg);
    transition: width 6s;
}
</style>
---------------------------------------------------------
قسم الservice
<template>
<div class="continer">
  <navbar id="nav"/>
<div class="row" id="Services">
  <div class="col-md-3" id="card1">
    <div id="app">
  <v-app id="inspire">
    <v-hover v-slot="{ hover }">
      <v-card
        class="mx-auto"
        color="grey lighten-4"
        max-width="600"
        height="70%"
      >
        <v-img
          :aspect-ratio="16/10"
          src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2440/Shape-2018-LR-106_d2799ae4d9532e75c7b76f8fe7c80560.webp"
        >
          <v-expand-transition>
            <div
              v-if="hover"
              class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal text-h2 white--text"
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
            color="orange"
            class="white--text"
            fab
            large
            right
            top
          >
            <v-icon>mdi-export</v-icon>
          </v-btn>
          <div class="font-weight-light grey--text text-h6 mb-2">
            For the perfect
          </div>
          <h3 class="text-h4 font-weight-light orange--text mb-2">
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
<div class="col-md-3" id="card2">
<v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      max-width="600"
      height="85%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2492/Shape-2018-LR-172_d2799ae4d9532e75c7b76f8fe7c80560.webp"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal text-h2 white--text"
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
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-export</v-icon>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light orange--text mb-2">
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
<div class="col-md-3" id="card3">
<v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      max-width="600"
      height="70%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/142670/Shape-2018-LR-100_5472332afa344033d2bf9e7b6b9d883e.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal text-h2 white--text"
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
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-export</v-icon>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light orange--text mb-2">
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
<div class="col-md-3" id="card4">
 <v-app id="inspire">
<v-hover v-slot="{ hover }">
    <v-card
      class="mx-auto"
      color="grey lighten-4"
      max-width="600"
      height="85%"
    >
      <v-img
        :aspect-ratio="16/10"
        src="https://d6f6d0kpz0gyr.cloudfront.net/uploads/transforms/15cbde7adb337ff527f63208d331a2d8/2440/Shape-2018-LR-106_d2799ae4d9532e75c7b76f8fe7c80560.webp"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal text-h2 white--text"
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
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-export</v-icon>
        </v-btn>
        <div class="font-weight-light grey--text text-h6 mb-2">
          For the perfect
        </div>
        <h3 class="text-h4 font-weight-light orange--text mb-2">
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
  margin-top: 80px;

}
#card2{
  margin-top: 140px;
}
#card3{
  margin-top: 80px;
}
#card4{
  margin-top: 140px;
}
</style>
--------------------------------------
قسم الmy Work
<template>
<v-app id="insiper">
<div id="mywork">
      <navbar id="nav"/>
 <v-card>
    <v-tabs
      color="deep-purple accent-4"
      right
    >
      <v-tab>Landscape</v-tab>
      <v-tab>City</v-tab>
      <v-tab>Abstract</v-tab>

      <v-tab-item
        v-for="n in 3"
        :key="n"
      >
        <v-container fluid>
          <v-row>
            <v-col
              v-for="i in 6"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="`https://picsum.photos/500/300?image=${i * n * 5 + 10}`"
                :lazy-src="`https://picsum.photos/10/6?image=${i * n * 5 + 10}`"
                aspect-ratio="1"
              ></v-img>
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
    </v-tabs>
  </v-card>
  </div>
</v-app>
</template>

<script>
import navbar from '../components/header.vue'
export default {
  name: 'mywork',
  components: {
    navbar
  }
}
</script>
