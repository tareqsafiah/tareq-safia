<template>
<div id="contact">
    <navbar id="nav"/>
      <div class="container-fluid">
    <div class="row">
    <div class="col-sm-12 col-md-7 col" id="forrm">
      <div id="card1" class="left-15-anim v-card v-sheet theam--light" style="height: 700px;">
  <v-form
    ref="form"
    v-model="valid"
    lazy-validation
  >
    <v-text-field
      v-model="name"
      :counter="40"
      :rules="nameRules"
      label="Name"
      required
    ></v-text-field>
    <v-text-field
      v-model="Company"
      :rules="CompanyRules"
      label="Company Name"
      required
    ></v-text-field>
    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="E-mail"
      required
    ></v-text-field>

    <v-select
      v-model="select"
      :items="items"
      :rules="[v => !!v || 'Item is required']"
      label="Type of Enquiry"
      required
    ></v-select>
    <v-text-field
      v-model="Subject"
      :rules="SubjectRules"
      label="Subject"
      required
    ></v-text-field>
    <v-checkbox
      v-model="checkbox"
      :rules="[v => !!v || 'You must agree to continue!']"
      label="Do you agree?"
      required
    ></v-checkbox>

    <v-btn
      :disabled="!valid"
      color="success"
      class="mr-4"
      @click="validate"
      id="sub"
    >
      Submit
    </v-btn>
 <v-btn
      color="error"
      class="mr-4"
      @click="reset"
      id="sub2"
    >
      Reset Form
    </v-btn>
  </v-form>
      </div>
  </div>
  <div class="col-sm-12 col-md-5 col" id="forrm">
    <div div id="card1" class="right-15-anim v-card v-sheet theam--light" style="min-height: 700px;">
<div class="container mt-2">
  <div class="row">
    <div class="col-md-11 col-12">
      <h3><i class="v-icon notranslate text-h5 mdi mdi-map-marker-right theam--light" aria-hidden="true">  </i>  Location:</h3>
      <p>Syria, Damascus,</p>
    </div>
  </div>
  <div class="row">
    <div class="col-md-11 col-12">
      <h3><i class="v-icon notranslate text-h5 mdi mdi-email theam--light" aria-hidden="true">  </i>  E-mail:</h3>
      <p>tareq.safyah@gmail.com</p>
    </div>
  </div>
    <div class="row">
    <div class="col-md-11 col-12">
      <h3><i class="v-icon notranslate text-h5 mdi mdi-phone theam--light" aria-hidden="true">  </i>  Phone:</h3>
      <p>+963992752024</p>
    </div>
  </div>
  <div style="z-index: 4; position: absolute; left: 50%; top: 50%; width: 100%; transform: translate(0px);"><div style="position: absolute; left: 0px; top: 0px; z-index: 104; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 105; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 106; width: 100%;"></div><div style="position: absolute; left: 0px; top: 0px; z-index: 107; width: 100%;"></div></div>
       <div class="col col-12"><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d51716.476117918886!2d36.28471041429808!3d33.50156725869812!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1518e6dc413cc6a7%3A0x6b9f66ebd1e394f2!2sDamascus%2C%20Syria!5e0!3m2!1sen!2sro!4v1635374258376!5m2!1sen!2sro" allowfullscreen="allowfullscreen" loading="lazy" style="border: 0px none;" width="100%" height="220px"></iframe></div>
       <div class="row">
    <div class="col-md-11 col-12">
      <h4>You Can also click her to contact Us:</h4>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="mailto:tareq.safyah@gmail.com" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-email theme--light" style="font-size: 24px;"></i></a></span></button>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="https://www.facebook.com/eng.comunicat" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-facebook theme--light" style="font-size: 24px;"></i></a></span></button>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="https://wa.me/963992752024" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-whatsapp theme--light" style="font-size: 24px;"></i></a></span></button>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="https://www.instagram.com/tareq.safiah/" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-instagram theme--light" style="font-size: 24px;"></i></a></span></button>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="https://twitter.com/SlayerSafia" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i></a></span></button>
      <button type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a href="https://www.youtube.com/channel/UCNPSyfLmpM_wT-oxvDaunJA" class="links"><i aria-hidden="true" class="v-icon notranslate mdi mdi-youtube theme--light" style="font-size: 24px;"></i></a></span></button>
       </div>
  </div>
  </div>
    </div>
      </div>
</div>
      </div>
</div>
</template>
<script>
import navbar from '../components/header.vue'

export default {
  name: 'contact',
  components: {
    navbar
  },
  data: () => ({
    valid: true,
    name: '',
    nameRules: [
      v => !!v || 'Name is required',
      v => (v && v.length <= 40) || 'Name must be less than 10 characters'
    ],
    email: '',
    emailRules: [
      v => !!v || 'E-mail is required',
      v => /.+@.+\..+/.test(v) || 'E-mail must be valid'
    ],
    Company: '',
    CompanyRules: [
      v => !!v || 'Company Name is required',
      v => /.+@.+\..+/.test(v) || 'Company Name must be valid'
    ],
    Subject: '',
    SubjectRules: [
      v => !!v || 'Subject Name is required',
      v => /.+@.+\..+/.test(v) || 'Subject Name must be valid'
    ],
    select: null,
    items: [
      'Just Saying Hi',
      'New Project',
      'Support/Help'
    ],
    checkbox: false
  }),

  methods: {
    validate () {
      this.$refs.form.validate()
    },
    reset () {
      this.$refs.form.reset()
    }
  }
}
</script>
<style>
#forrm{
    top: 30px;
}
#sub{
    background-color: rgb(0, 153, 255);
}
#sub2{
    background-color: rgb(0, 153, 255);
}
#sub3{
    background-color: rgb(0, 153, 255);
}
body{
background-color: #dfe6e9;
    opacity: 0.99;
    height: 100%;
}
#nav{
  position: sticky;
  top:0;
  z-index: 10;
}
.v-card {
    border-width: thin;
    display: block;
    max-width: 100%;
    outline: none;
    text-decoration: none;
    transition-property: box-shadow,opacity;
    overflow-wrap: break-word;
    position: relative;
    white-space: normal;
    padding: 20px;
}
.v-sheet.v-card:not(.v-sheet--outlined) {
    box-shadow: 0 3px 1px -2px rgba(0,0,0,.2),0 2px 2px 0 rgba(0,0,0,.14),0 1px 5px 0 rgba(0,0,0,.12);
}
element {
    min-height: 800px;
}
.v-sheet.v-card {
    border-radius: 4px;
}
.col-md-7 {
    flex: 0 0 58.3333333333%;
    max-width: 58.3333333333%;
}
.col-md-5 {
    flex: 0 0 41.6666666667%;
    max-width: 41.6666666667%;
}
.col-sm-12 {
    flex: 0 0 100%;
    max-width: 100%;
}
.col {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%;
}
.left-15-anim {
    -webkit-animation: transation-left 1.5s;
    animation: transation-left 1.5s;
}
@keyframes transation-left{

  0% {
    opacity: 0;
    transform: translatex(-40px);

  }
  100% {
    opacity: 1;
    transform: translateY(0);
}
}
.right-15-anim {
    -webkit-animation: transation-right 1.5s;
    animation: transation-right 1.5s;
}
@keyframes transation-right{
  0% {
    opacity: 0;
    transform: translatex(40px);
}
100% {
    opacity: 1;
    transform: translateY(0);
}
}
</style>
