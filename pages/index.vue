<template>
  <div>
    <div data-aos="fade-down-right" data-aos-delay="150">
      <v-card class="elevation-0 mt-9">
        <v-card-text class="text-center">
          <p style="font-size: 16px">Biznesingizni keyingi bosqichga olib chiqish yoki g’oyalaringizni binzesga
            aylantirish haqida
            qayg’uryapsizmi?</p>
          <p class="title-pro text-h2 font-weight-bold" style="color: #000">
            <span class="title-pro text-h2 font-weight-bold" style="color: #0677E1">Programmist.uz </span>bilan
            tanishing
          </p>
          <p style="font-size: 16px">
            Hurmat bilan, Mijozlar muammosiga IT orqali yechim beruvchi jamoa!
          </p>
        </v-card-text>
        <v-card-actions>
          <v-row justify="center">
            <v-col cols="12" sm="8" md="6" lg="4">
              <BTNComponents/>
            </v-col>
          </v-row>
        </v-card-actions>
        <v-row class="mt-8">
          <v-col data-aos="fade-down-right" cols="12" lg="9">
            <v-img src="/moskup1.svg"></v-img>
          </v-col>
          <v-col data-aos="fade-down-left" cols="12" lg="3" align="center">
            <v-spacer/>
            <v-img class="phone-image" width="100%" src="/moskup2.svg" max-width="400"></v-img>
          </v-col>
        </v-row>
      </v-card>
    </div>
    <!-- Bizning statistika -->
    <div data-aos="fade-down-left" data-aos-offset="200" data-aos-delay="200"
         class="d-flex justify-center text-center mt-16">
      <v-card elevation="0" width="900">
        <v-card-title>
          <v-spacer/>
          <h1>
            <nuxt-link to="#xizmatlar" class="statistik-title" style="color: black">Bizning<span style="color: #8C1FE2"> statistika</span>
            </nuxt-link>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <v-row class="d-flex justify-space-between mt-3">
            <v-col class="card_static" cols="12" md="6" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">3+</div>
              <div>Yillik tajriba</div>
            </v-col>
            <v-col class="card_static" cols="12" md="6" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">13+</div>
              <div>Loyihalar</div>
            </v-col>
            <v-col class="card_static" cols="12" md="12" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">13+</div>
              <div>Mutaxxasislar</div>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>
    </div>
    <div data-aos="flip-left" data-aos-delay="200" class="mt-12">
      <v-card
        style="box-shadow: 0px 6px 24px 0px rgba(139, 141, 144, 0.08); border: 1px solid #D7E0E8; overflow: hidden"
        class="rounded-xxl">
        <v-row class="d-flex justify-center align-center pl-10 pr-3">
          <v-col>
            <v-card-title>
              <div>
                <div class="text-caption text-uppercase">Bizning <span style="color: #8C1FE2">portfolio</span></div>
                <div class="text-h5 font-weight-bold">
                  Lorem Ipsum is simply
                </div>
              </div>
            </v-card-title>
            <v-card-text>
              <div class="text-body-2">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
                industry's standard dummy text ever since the 1500s,
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn dark class="rounded-lg pa-5" small height="24" text color="#0677E1">
                Loyihani ko’rish
                <v-icon class="ml-3">
                  mdi-chevron-right
                </v-icon>
              </v-btn>
              <v-spacer/>
              <v-btn dark icon color="#0677E1" class="pa-6">
                <v-icon large>
                  mdi-chevron-left
                </v-icon>
              </v-btn>
              <v-btn icon dark color="#0677E1" class="pa-6">
                <v-icon large>
                  mdi-chevron-right
                </v-icon>
              </v-btn>
            </v-card-actions>
          </v-col>
          <v-col class="pr-0 ml-9 mt-3">
            <v-img src="/1.svg" sizes="600">
            </v-img>
          </v-col>
        </v-row>
      </v-card>
    </div>

    <!-- Bizning xizmatlar -->
    <div data-aos="fade-up"
         data-aos-duration="3000" class="d-flex justify-center text-center mt-16"
         style="width: 100%!important;">
      <v-card elevation="0" width="900">
        <v-card-title>
          <v-spacer/>
          <h1 id="xizmatlar">
            <p style="color: black" class="statistik-title">Bizning<span style="color: #8C1FE2"> xizmatlar</span>
            </p>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <v-row class="mt-3 d-flex justify-space-between grid-list-md">
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/web-site.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                Vebsayt yaratish
              </div>
            </v-col>
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/crm.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                CRM
              </div>
            </v-col>
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/telegram.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                Telegram bot
              </div>
            </v-col>
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/phone.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                Mobile ilovalar
              </div>
            </v-col>
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/brush.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                Grafik dizayn
              </div>
            </v-col>
            <v-col style="background: #F8FBFE" class="card_static" cols="12" sm="6" md="6" lg="4">
              <div class="d-flex justify-center">
                <p class="card--title__img">
                  <v-img src="/design.svg" width="32">
                  </v-img>
                </p>
              </div>
              <div>
                UX/UI Dizayn
              </div>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="12" sm="10" md="8" lg="6">
              <BTNComponents/>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>
    </div>
    <!-- Bizning hamkorlar -->
    <div
      data-aos="fade-down"
      data-aos-easing="linear"
      data-aos-duration="1500"
      class="mt-16 mx-auto">
      <v-card elevation="0">
        <v-card-title>
          <v-spacer/>
          <h1 id="xamkorlar">
            <p style="color: black" class="statistik-title">Bizning<span style="color: #8C1FE2"> xamkorlar</span>
            </p>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text class="px-0 mt-10">
          <v-card elevation="0">
            <v-carousel
              hide-delimiters
              height="200px"
              class="carousel-card__container"
            >
              <template v-slot:prev="{ on, attrs }">
                <v-btn
                  icon
                  class="prev-btn"
                  style="background-color: #fff; border: 1px solid #D7E0E8"
                  v-bind="attrs"
                  v-on="on"
                >
                  <v-icon color="#0677E1">
                    mdi-chevron-left
                  </v-icon>
                </v-btn>
              </template>
              <template v-slot:next="{ on, attrs }">
                <v-btn
                  icon
                  style="background-color: #fff; border: 1px solid #D7E0E8"
                  v-bind="attrs"
                  v-on="on"
                >
                  <v-icon color="#0677E1">
                    mdi-chevron-right
                  </v-icon>
                </v-btn>
              </template>
              <v-carousel-item>
                <div class="mt-3 ml-3" style="height: 100%; width: 100%">
                  <v-row class="carousel-card" style="width: 100%; height: 100%" justify="space-around" align="center">
                    <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                           style="min-width: 200px; border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/uzum.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                    <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                           style="min-width: 200px; border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                    <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                           style="min-width: 200px; border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                    <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                           style="min-width: 200px; border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-carousel-item>
              <v-carousel-item>
                <v-row class="carousel-card" style="width: 100%; height: 100%" justify="space-around" align="center">
                  <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                         style="min-width: 200px; border: 1px solid #D7E0E8">
                    <div>
                      <v-img class="mx-auto" src="/uzum.svg" max-width="100px"></v-img>
                    </div>
                  </v-col>
                  <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                         style="min-width: 200px; border: 1px solid #D7E0E8">
                    <div>
                      <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                    </div>
                  </v-col>
                  <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                         style="min-width: 200px; border: 1px solid #D7E0E8">
                    <div>
                      <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                    </div>
                  </v-col>
                  <v-col cols="5" sm="5" md="2" lg="2" class="rounded-xxl"
                         style="min-width: 200px; border: 1px solid #D7E0E8">
                    <div>
                      <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                    </div>
                  </v-col>
                </v-row>
              </v-carousel-item>
            </v-carousel>
            <v-carousel
              hide-delimiters
              height="120px"
              class="carousel-card__container-card"
            >
              <template v-slot:prev="{ on, attrs }">
                <v-btn
                  icon
                  style="background-color: #fff; border: 1px solid #D7E0E8"
                  v-bind="attrs"
                  v-on="on"
                >
                  <v-icon color="#0677E1">
                    mdi-chevron-left
                  </v-icon>
                </v-btn>
              </template>
              <template v-slot:next="{ on, attrs }">
                <v-btn
                  icon
                  style="background-color: #fff; border: 1px solid #D7E0E8"
                  v-bind="attrs"
                  v-on="on"
                >
                  <v-icon color="#0677E1">
                    mdi-chevron-right
                  </v-icon>
                </v-btn>
              </template>
              <v-carousel-item>
                <div class="mt-3 ml-3" style="height: 100%; width: 100%">
                  <v-row class="carousel-card" style="width: 100%; height: 100%" align="center">
                    <v-col class="rounded-xxl"
                           style="width: 100%; border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/uzum.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-carousel-item>
              <v-carousel-item>
                <div class="mt-3 ml-3" style="height: 100%; width: 100%">
                  <v-row class="carousel-card" style="width: 100%; height: 100%" align="center">
                    <v-col class="rounded-xxl"
                           style="border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-carousel-item>
              <v-carousel-item>
                <div class="mt-3 ml-3" style="height: 100%; width: 100%">
                  <v-row class="carousel-card" style="width: 100%; height: 100%" align="center">
                    <v-col class="rounded-xxl"
                           style="border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-carousel-item>
              <v-carousel-item>
                <div class="mt-3 ml-3" style="height: 100%; width: 100%">
                  <v-row class="carousel-card" style="width: 100%; height: 100%" align="center">
                    <v-col class="rounded-xxl"
                           style=" border: 1px solid #D7E0E8">
                      <div>
                        <v-img class="mx-auto" src="/avtosavdo.svg" max-width="100px"></v-img>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-carousel-item>
            </v-carousel>
          </v-card>
        </v-card-text>
      </v-card>
    </div>

    <!-- Ko'p so'raladigan savollar -->
    <div data-aos="fade-up"
         data-aos-anchor-placement="top-bottom" class="my-10">
      <v-row justify="space-between">
        <v-col cols="12" md="5" lg="6">
          <h1>
            Eng ko’p beriladigan <span style="color: #8C1FE2"> savollar</span>
          </h1>
        </v-col>
        <v-col cols="12" md="7" lg="6">
          <v-expansion-panels class="my-2">
            <v-expansion-panel class="rounded-xl mb-5">
              <v-expansion-panel-header
                class="rounded-xl"
              >
                <template #actions>
                  <v-btn icon>
                    <v-icon color="#0677E1">
                      mdi-chevron-down
                    </v-icon>
                  </v-btn>
                </template>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, fugit.
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium architecto beatae commodi
                consequatur culpa doloribus est exercitationem facilis, fugit hic ipsum iusto labore magni modi nobis
                provident quam quisquam repudiandae ut? Beatae enim impedit nam nihil porro provident quaerat quasi sint
                sunt voluptate? Animi obcaecati officia omnis quae quia.
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>
          <v-expansion-panels class="my-2">
            <v-expansion-panel class="rounded-xl mb-5">
              <v-expansion-panel-header
                class="rounded-xl"
              >
                <template #actions>
                  <v-btn icon>
                    <v-icon color="#0677E1">
                      mdi-chevron-down
                    </v-icon>
                  </v-btn>
                </template>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, fugit.
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium architecto beatae commodi
                consequatur culpa doloribus est exercitationem facilis, fugit hic ipsum iusto labore magni modi nobis
                provident quam quisquam repudiandae ut? Beatae enim impedit nam nihil porro provident quaerat quasi sint
                sunt voluptate? Animi obcaecati officia omnis quae quia.
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>
          <v-expansion-panels class="my-2">
            <v-expansion-panel class="rounded-xl mb-5">
              <v-expansion-panel-header
                class="rounded-xl"
              >
                <template #actions>
                  <v-btn icon>
                    <v-icon color="#0677E1">
                      mdi-chevron-down
                    </v-icon>
                  </v-btn>
                </template>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, fugit.
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium architecto beatae commodi
                consequatur culpa doloribus est exercitationem facilis, fugit hic ipsum iusto labore magni modi nobis
                provident quam quisquam repudiandae ut? Beatae enim impedit nam nihil porro provident quaerat quasi sint
                sunt voluptate? Animi obcaecati officia omnis quae quia.
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>
          <v-expansion-panels class="my-2">
            <v-expansion-panel class="rounded-xl mb-5">
              <v-expansion-panel-header
                class="rounded-xl"
              >
                <template #actions>
                  <v-btn icon>
                    <v-icon color="#0677E1">
                      mdi-chevron-down
                    </v-icon>
                  </v-btn>
                </template>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, fugit.
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium architecto beatae commodi
                consequatur culpa doloribus est exercitationem facilis, fugit hic ipsum iusto labore magni modi nobis
                provident quam quisquam repudiandae ut? Beatae enim impedit nam nihil porro provident quaerat quasi sint
                sunt voluptate? Animi obcaecati officia omnis quae quia.
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>
        </v-col>
      </v-row>
    </div>
    <!-- O'ylab ko'ring -->
    <div data-aos="fade-up"
         data-aos-anchor-placement="top-center" class="mt-16">
      <v-card class="rounded-xxl elevation-0" style="border: 1px solid #D7E0E8; overflow: hidden">
        <v-row justify="space-between" class="pa-12" style="min-height: 343px" align="center">
          <v-col cols="12" md="2" lg="2" align-self="start" class="d-flex justify-center">
            <v-img src="/business-goal.svg" max-width="150px"></v-img>
          </v-col>
          <v-col cols="12" md="6" lg="6" class="text-center">
            <v-card-title>
              <v-spacer/>
              <h1>
                <nuxt-link to="#xizmatlar" class="statistik-title" style="color: black">O'ylab<span
                  style="color: #8C1FE2"> ko'ring!</span>
                </nuxt-link>
              </h1>
              <v-spacer/>
            </v-card-title>
            <v-card-text>
              Biznesingizni keyingi bosqichga olib chiqish yoki g’oyalaringizni biznesga aylantirish haqida
              qayg’uryapsizmi?
            </v-card-text>
            <v-card-actions>
              <v-row justify="center">
                <v-col cols="12" sm="8" md="10" lg="8">
                  <BTNComponents/>
                </v-col>
              </v-row>
            </v-card-actions>
          </v-col>
          <v-col cols="12" md="2" lg="2" align-self="end" class="d-flex justify-center">
            <v-img src="repair-tool.svg" max-width="150px"></v-img>
          </v-col>
        </v-row>
      </v-card>
    </div>
  </div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
import BTNComponents from "@/components/Btn.vue";

AOS.init({
  useClassNames: true,
  initClassName: false,
  animatedClassName: 'animated',
});
AOS.refreshHard();
export default {
  components: {
    BTNComponents,

  },
  data() {
    return {}
  },
}
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
}
.card_static {
  padding: 40px;
  border-radius: 18px;
  box-shadow: 0px 6px 24px 0px rgba(139, 141, 144, 0.08);
}

.card--title__img {
  padding: 10px;
  border-radius: 50%;
  background-color: rgba(215, 227, 238, 0.68);
}

.hidden-card {
  .hidden-active {
    display: none;
    opacity: 0;
  }
}

.hidden-card:hover {
  .hidden-active {
    display: block;
    opacity: 1;
  }
}

.carousel-card__container-card {
  display: none;
}

.v-window__prev:hover {
  background-color: red;
}

@media (max-width: 700px) {
  .phone-image {
    max-width: 300px !important;
  }
}
@media (max-width: 502px) {
  .title-pro {
    font-size: 40px !important;
  }
}
@media (max-width: 450px) {
  .carousel-card__container {
    display: none;
  }
  .carousel-card__container-card {
    display: inline;
  }
}
@media (max-width: 425px) {
  .statistik-title {
    font-size: 28px !important;
  }
  .phone-image {
    max-width: 200px !important;
  }
}

</style>
