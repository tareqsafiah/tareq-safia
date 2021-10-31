<template>
  <div class="continer">
    <v-toolbar id="navbar" flat elevation="1" app dark class="position-fixed">
       <v-app-bar-nav-icon class="hidden-md-and-up" @click="sidebar = !sidebar"></v-app-bar-nav-icon>
      <v-navigation-drawer v-model="sidebar" app hide-overlay temporary>
        <v-list>
          <v-list-item v-for="(item, i) in menuItems" exact :key="i" :to="item.path">{{item.title}}</v-list-item>
                  <hr>
                  <div class="row">
    <div dense elevation="1" class="col-sm-12 col-12" style="position: absolute; left: 10px; bottom: 10px;">
      <h4>You Can also click her to contact Us:</h4>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="mailto:tareq.safyah@gmail.com" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-email theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.facebook.com/eng.comunicat" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-facebook theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://wa.me/963992752024" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-whatsapp theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.instagram.com/tareq.safiah/" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-instagram theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.youtube.com/channel/UCNPSyfLmpM_wT-oxvDaunJA" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-youtube theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://twitter.com/SlayerSafia" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px; text-decoration:none;"></i></a></span></button>
       </div>
  </div>
                  </v-list>
      </v-navigation-drawer>
    <v-toolbar-items d-flex id="titl">
      <v-toolbar-title><v-btn flat depressed>Tareq Safiah</v-btn></v-toolbar-title>
    </v-toolbar-items>
      <v-spacer></v-spacer>
      <!-- <hidden-sm-and-up> -->
      <v-toolbar-items id="itm" class="hidden-sm-and-down" style="text-decoration:none;">
      <!-- <v-btn id="bt1" flat depressed to="/">Home</v-btn>
      <v-btn id="bt2" flat depressed to="/Services/">Services</v-btn>
      <v-btn id="bt3" flat depressed to="/MyWork/">My Work</v-btn>
      <v-btn id="bt3" flat depressed to="/contact/">Contact</v-btn> -->
 <v-btn id="bt" flat depressed v-for="item in menuItems" :key="item.title" style="text-decoration:none; color:#dfe6e9">
          <router-link :to="item.path" style="text-decoration:none; color:#dfe6e9">{{item.title}}</router-link>
        </v-btn>
      </v-toolbar-items>
      <v-btn icon id="bt4">
        <a href="/GetService/" style="text-decoration:none; color:#dfe6e9;"><v-icon>mdi-shape-square-rounded-plus</v-icon></a>
      </v-btn>
    </v-toolbar>
  </div>
</template>
<script>
// export default {
//   name: 'navbar'
// }
export default {
  name: 'navbar',
  data: function () {
    return {
      sidebar: false,
      menuItems: [
        { path: '/', name: 'Home', title: 'Home', icon: 'home' },
        { path: '/Services', name: 'Services', title: 'Services' },
        { path: 'MyWork', name: 'My Work', title: 'My Work' },
        { path: '/contact', name: 'contact', title: 'contact' }
      ]
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
#bt :hover{
  background-color: transparent;
}
.v-btn__content {
    align-items: center;
    color: inherit;
    display: flex;
    flex: 1 0 auto;
    justify-content: inherit;
    line-height: normal;
    position: relative;
    transition: inherit;
        transition-property: inherit;
    transition-property: opacity;}
    .theme--light.v-btn.v-btn--icon {
    color: rgba(0,0,0,.54);
}
.v-btn.v-size--default, .v-btn.v-size--large {
    font-size: .875rem;
}
.v-btn {
    font-weight: 500;
    letter-spacing: .0892857143em;
    text-indent: .0892857143em;
    text-transform: uppercase;
    white-space: nowrap;
}
.v-card {
    overflow-wrap: break-word;
    white-space: normal;
}
/* #bt2 :hover{
  background-color: transparent;
}
#bt3 :hover{
  background-color: transparent;
} */
/* .theme--light.v-application {
    color: rgba(0,0,0,.87);
} */
#bt4:hover{
background-color: #ff7675;
text-decoration: double;
color: black;
border-bottom: 3px;
}
#titl{
  /* background-color: rgb(233, 224, 224); */
  top: 10px;
  position: relative;
  animation-name: mymove;
  animation-duration: 2s;
  animation-iteration-count: 1;
    animation-timing-function: ease;
    /* font-family: weight-bold; */
}
@keyframes mymove {
  from {left: -90%;}
  to {color:#2d3436; left: -1px;
}
}
#titl :hover{
    transform: rotateZ(360deg);
    transition: width 6s;
}
</style>
