<template>
<div id="contact">
    <navigation id="nav"/>
      <div class="continer mt-2" data-v-822f34ec="" >
    <div class="row" data-v-822f34ec="">
    <div class="col-sm-12 col-md-7 col" data-v-822f34ec="" id="forrm">
      <div id="card1" class="left-15-anim v-card v-sheet theam--light" data-v-d53af812="" data-v-822f34ec="" style="height: 612px;">
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
  <div class="col-sm-12 col-md-5 col" data-v-822f34ec="" id="forrm">
    <div div id="card1" class="right-15-anim v-card v-sheet theam--light" data-v-822f34ec="" style="min-height: 500px;">
<div class="continer mt-2" data-v-822f34ec="">
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
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="mailto:tareq.safyah@gmail.com" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-email theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.facebook.com/eng.comunicat" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-facebook theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://wa.me/963992752024" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-whatsapp theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.instagram.com/tareq.safiah/" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-instagram theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://twitter.com/SlayerSafia" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i></a></span></button>
      <button data-v-822f34ec="" type="button" class="mx-4 v-btn v-btn--icon v-btn--round theme--light v-size--default"><span class="v-btn__content"><a data-v-822f34ec="" href="https://www.youtube.com/channel/UCNPSyfLmpM_wT-oxvDaunJA" class="links"><i data-v-822f34ec="" aria-hidden="true" class="v-icon notranslate mdi mdi-youtube theme--light" style="font-size: 24px;"></i></a></span></button>
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
import navigation from '../components/header.vue'

export default {
  name: 'contact',
  components: {
    navigation
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
    /* margin-left: 10px; */
    margin: auto;
}
#conta{
  border: 1px solid;
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
.continer{
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

    min-height: 500px;
}
.v-sheet.v-card {
    border-radius: 4px;
}
*, ::after, ::before {
    background-repeat: no-repeat;
    box-sizing: inherit;
}
.col, .col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col-auto, .col-lg, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg-auto, .col-md, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md-auto, .col-sm, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm-auto, .col-xl, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl-auto {
    width: 100%;
    padding: 12px;
}
.col-md-7 {
    flex: 0 0 58.3333333333%;
    max-width: 58.3333333333%;
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
.v-card {
    overflow-wrap: break-word;
    white-space: normal;
}
* {
    padding: 0;
    margin: 0;
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
