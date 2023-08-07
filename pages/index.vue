<template>
  <div>
    <div>
      <v-card class="elevation-0 mt-9">
        <v-card-text class="text-center">
          <p style="font-size: 16px">Biznesingizni keyingi bosqichga olib chiqish yoki g’oyalaringizni binzesga
            aylantirish haqida
            qayg’uryapsizmi?</p>
          <p class="text-h2 font-weight-bold" style="color: #000">
            <span class="text-h2 font-weight-bold" style="color: #0677E1">Programmist.uz </span>bilan tanishing
          </p>
          <p style="font-size: 16px">
            Hurmat bilan, Mijozlar muammosiga IT orqali yechim beruvchi jamoa!
          </p>
        </v-card-text>
        <v-card-actions>
          <v-spacer/>
          <BTNComponents/>
          <v-spacer/>
        </v-card-actions>

        <v-row class="mt-8">
          <v-col cols="12" lg="9">
            <v-img src="/moskup1.svg"></v-img>
          </v-col>
          <v-col cols="12" lg="3">
            <v-img width="100%" src="/moskup2.svg"></v-img>
          </v-col>
        </v-row>
      </v-card>
    </div>

    <!-- Bizning statistika -->
    <div class="d-flex justify-center text-center mt-16">
      <v-card elevation="0" width="900">
        <v-card-title>
          <v-spacer/>
          <h1>
            <nuxt-link to="#xizmatlar" style="color: black">Bizning<span style="color: #8C1FE2"> statistika</span>
            </nuxt-link>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <v-row class="d-flex justify-space-between mt-3">
            <v-col class="card_static" cols="12" md="3" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">3+</div>
              <div>Yillik tajriba</div>
            </v-col>
            <v-col class="card_static" cols="12" md="3" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">13+</div>
              <div>Loyihalar</div>
            </v-col>
            <v-col class="card_static" cols="12" md="3" lg="3">
              <div class="font-weight-bold text-h4" style="color: black">13+</div>
              <div>Mutaxxasislar</div>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>
    </div>
    <div class="mt-12">
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
    <div class="d-flex justify-center text-center mt-16" style="width: 100%!important;">
      <v-card elevation="0" width="900">
        <v-card-title>
          <v-spacer/>
          <h1 id="xizmatlar">
            <p style="color: black">Bizning<span style="color: #8C1FE2"> xizmatlar</span>
            </p>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <v-row class="mt-3 d-flex justify-space-between grid-list-md">
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
            <v-col cols="12">
              <BTNComponents/>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>
    </div>
    <!-- Bizning hamkorlar -->
    <div class="d-flex justify-center text-center mt-16" style="width: 100%!important;">
      <v-card elevation="0" width="900">
        <v-card-title>
          <v-spacer/>
          <h1 id="xamkorlar">
            <p style="color: black">Bizning<span style="color: #8C1FE2"> xamkorlar</span>
            </p>
          </h1>
          <v-spacer/>
        </v-card-title>
        <v-card-text>
          <v-row class="mt-3 d-flex justify-space-between">
            <v-col style="background: #F8FBFE" class="card_static" cols="12" md="6" lg="4">
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
          </v-row>
        </v-card-text>
      </v-card>
    </div>
    <!-- Ko'p so'raladigan savollar -->
    <div class="my-10">
      <v-row justify="space-between">
        <v-col cols="12" md="4" lg="4">
          <h1>
            Eng ko’p <br> beriladigan <span style="color: #8C1FE2"> savollar</span>
          </h1>
        </v-col>
        <v-col cols="12" md="6" lg="6">
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
          <div class="hidden-card elevation-1 rounded-xxl pa-1 mb-3">
            <span>
              <v-btn color="blue" icon class="mr-2">
              <v-icon>
                mdi-chevron-down
              </v-icon>
            </v-btn>
            </span>
            <span>
              Lorem Ipsum is simply dummy text of the printing
            </span>
            <div class="hidden-active pl-12 pb-3 pr-3 text-caption">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aspernatur beatae cum deleniti dolorem
              ea eligendi enim error impedit molestias nesciunt nulla, perspiciatis praesentium quas quidem, ut voluptatem
              voluptates? Ad atque blanditiis consequatur doloribus ducimus enim illum in incidunt itaque mollitia
              necessitatibus nemo odio perspiciatis, praesentium quam quasi ratione soluta.
            </div>
          </div>
        </v-col>
      </v-row>
    </div>
    <!-- O'ylab ko'ring -->
    <div class="mt-16">
      <v-card class="rounded-xxl elevation-0" style="border: 1px solid #D7E0E8; overflow: hidden">
        <v-row justify="space-between" class="pa-12" style="height: 343px" align="center">
          <v-col cols="12" md="2" lg="2" align-self="start">
            <v-img src="/business-goal.svg"></v-img>
          </v-col>
          <v-col cols="12" md="6" lg="6" class="text-center">
            <v-card-title>
              <v-spacer/>
              <h1>
                <nuxt-link to="#xizmatlar" style="color: black">O'ylab<span style="color: #8C1FE2"> ko'ring!</span>
                </nuxt-link>
              </h1>
              <v-spacer/>
            </v-card-title>
            <v-card-text>
              Biznesingizni keyingi bosqichga olib chiqish yoki g’oyalaringizni biznesga aylantirish haqida
              qayg’uryapsizmi?
            </v-card-text>
            <v-card-actions class="d-flex justify-center">
              <BTNComponents/>
            </v-card-actions>
          </v-col>
          <v-col cols="12" md="2" lg="2" align-self="end">
            <v-img src="repair-tool.svg"></v-img>
          </v-col>
        </v-row>
      </v-card>
    </div>
  </div>
</template>

<script>
import BTNComponents from "@/components/Btn.vue";

export default {
  components: {BTNComponents},
  data() {
    return {}
  }
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
.hidden-card{
  .hidden-active{
    display: none;
    opacity: 0;
  }
}
.hidden-card:hover{
  .hidden-active{
    display: block;
    opacity: 1;
  }
}
</style>
