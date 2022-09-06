<template>
  <v-app id="mywork">
    <div class="container-fluid">
      <v-card>
        <v-tabs color="deep-purple accent-4" right>
          <v-tab>Latest Design</v-tab>
          <v-tab-item v-for="n in 3" :key="n">
            <div id="gallery">
              <div class="container">
                <div class="row" warp="">
                  <div class="down-2-anim col-sm-6 col-md-4 col-12">
                    <div
                      class="v-card v-sheet theme--light"
                      style="max-width: 400px;"
                    >
                      <div
                        class="v-image v-responsive white--text align-end theme--light"
                        style="height: 200px;"
                      >
                        <div
                          class="v-responsive__sizer"
                          style="padding-bottom: 56.23%;"
                        ></div>
                        <div class="v-image__image v-image__image--cover">
                          <v-img src="../assets/taskmanager.png" />
                        </div>
                        <div
                          class="v-responsive__content"
                          style="width: 626px;"
                        ></div>
                      </div>
                      <div class="v-card__subtitle pb-0">
                        Task Manager "vue.js"
                      </div>
                      <div class="v-card__text text--primary">
                        <div>
                          To do manager
                        </div>
                      </div>
                      <div class="v-card__actions">
                        <div class="row justify-center">
                          <div class="col col-4">
                            <button
                              type="button"
                              class="blak--text v-btn v-btn--is-elevated v-btn--has-bg theme--light v-size--default red lighten-5"
                              role="button"
                              aria-haspopup="true"
                              aria-expanded="false"
                            >
                              <span class="v-btn__content"
                                ><a
                                  href="https://task-manager-t.netlify.app/"
                                  style="text-decoration: none; color: black;"
                                  >Visit</a
                                ><i
                                  aria-hidden="true"
                                  class="v-icon notranslate v-icon--right mdi mdi-arrow-right-bold-circle theme--light"
                                ></i
                              ></span>
                            </button>
                            <div
                              role="dialog"
                              class="v-dialog__container"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="up-2-anim col-sm-6 col-md-4 col-12">
                    <div
                      class="v-card v-sheet theme--light"
                      style="max-width: 400px;"
                    >
                      <div
                        class="v-image v-responsive white--text align-end theme--light"
                        style="height: 200px;"
                      >
                        <div
                          class="v-responsive__sizer"
                          style="padding-bottom: 56.23%;"
                        ></div>
                        <div class="v-image__image v-image__image--cover">
                          <v-img src="../assets/weather.png" />
                        </div>
                        <div
                          class="v-responsive__content"
                          style="width: 626px;"
                        ></div>
                      </div>
                      <div class="v-card__subtitle pb-0">Weather Status "puer"</div>
                      <div class="v-card__text text--primary">
                        <div>Weather Status</div>
                      </div>
                      <div class="v-card__actions">
                        <div class="row justify-center">
                          <div class="col col-4">
                            <button
                              type="button"
                              class="blak--text v-btn v-btn--is-elevated v-btn--has-bg theme--light v-size--default red lighten-5"
                              role="button"
                              aria-haspopup="true"
                              aria-expanded="false"
                            >
                              <span class="v-btn__content"
                                ><a
                                  href="https://tareqsafiah.github.io/weather/"
                                  style="text-decoration: none; color: black;"
                                  >Visit</a
                                ><i
                                  aria-hidden="true"
                                  class="v-icon notranslate v-icon--right mdi mdi-arrow-right-bold-circle theme--light"
                                ></i
                              ></span>
                            </button>
                            <div
                              role="dialog"
                              class="v-dialog__container"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="down-2-anim col-sm-6 col-md-4 col-12">
                    <div
                      class="v-card v-sheet theme--light"
                      style="max-width: 400px;"
                    >
                      <div
                        class="v-image v-responsive white--text align-end theme--light"
                        style="height: 200px;"
                      >
                        <div
                          class="v-responsive__sizer"
                          style="padding-bottom: 56.23%;"
                        ></div>
                        <div class="v-image__image v-image__image--cover">
                          <v-img src="../assets/mazadak.jpg" />
                        </div>
                        <div
                          class="v-responsive__content"
                          style="width: 626px;"
                        ></div>
                      </div>
                      <div class="v-card__subtitle pb-0">
                        Mazadak Website Multi Page
                      </div>
                      <div class="v-card__text text--primary">
                        <div>
                        Multi language
                        </div>
                      </div>
                      <div class="v-card__actions">
                        <div class="row justify-center">
                          <div class="col col-4">
                            <button
                              type="button"
                              class="blak--text v-btn v-btn--is-elevated v-btn--has-bg theme--light v-size--default red lighten-5"
                              role="button"
                              aria-haspopup="true"
                              aria-expanded="false"
                            >
                              <span class="v-btn__content"
                                ><a
                                  href="https://tareqsafiah.github.io/tareq-safiah-mazadak/index.html#"
                                  style="text-decoration: none; color: black;"
                                  >Visit</a
                                ><i
                                  aria-hidden="true"
                                  class="v-icon notranslate v-icon--right mdi mdi-arrow-right-bold-circle theme--light"
                                ></i
                              ></span>
                            </button>
                            <div
                              role="dialog"
                              class="v-dialog__container"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="down-2-anim col-sm-6 col-md-4 col-12">
                    <div
                      class="v-card v-sheet theme--light"
                      style="max-width: 400px;"
                    >
                      <div
                        class="v-image v-responsive white--text align-end theme--light"
                        style="height: 200px;"
                      >
                        <div
                          class="v-responsive__sizer"
                          style="padding-bottom: 56.23%;"
                        ></div>
                        <div
                          class="v-image__image v-image__image--cover"
                          style="background-image: url('file:///D:/vue/design_ui/src/assets/mercedes.jpg;'); background-position: center center;"
                        >
                          <v-img src="../assets/mercedes.jpg" />
                        </div>
                        <div
                          class="v-responsive__content"
                          style="width: 626px;"
                        ></div>
                      </div>
                      <div class="v-card__subtitle pb-0">
                        Mercedes website One Page
                      </div>
                      <div class="v-card__text text--primary">
                        <div>Just For Training</div>
                      </div>
                      <div class="v-card__actions">
                        <div class="row justify-center">
                          <div class="col col-4">
                            <button
                              type="button"
                              class="blak--text v-btn v-btn--is-elevated v-btn--has-bg theme--light v-size--default red lighten-5"
                              role="button"
                              aria-haspopup="true"
                              aria-expanded="false"
                            >
                              <span class="v-btn__content"
                                ><a
                                  href=" "
                                  style="text-decoration: none; color: black;"
                                  >Visit</a
                                ><i
                                  aria-hidden="true"
                                  class="v-icon notranslate v-icon--right mdi mdi-arrow-right-bold-circle theme--light"
                                ></i
                              ></span>
                            </button>
                            <div
                              role="dialog"
                              class="v-dialog__container"
                            ></div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </v-tab-item>
        </v-tabs>
      </v-card>
    </div>
  </v-app>
</template>

<style scoped>
body {
  background-color: #dfe6e9;
  opacity: 0.99;
  height: 100%;
}
.up-2-anim {
  -webkit-animation: transation-up 1.5s;
  animation: transation-up 1.5s;
}
@keyframes transation-up {
  0% {
    opacity: 0;
    transform: translatey(60px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
.down-2-anim {
  -webkit-animation: transation-down 1.5s;
  animation: transation-down 1.5s;
}
@keyframes transation-down {
  0% {
    opacity: 0;
    transform: translatey(-60px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
.col-md-4 {
  flex: 0 0 33.3333333333%;
  width: 33.3333333333%;
}
.col-sm-6 {
  flex: 0 0 50%;
  width: 50%;
}
.col-12 {
  flex: 0 0 100%;
  width: 100%;
}
</style>
