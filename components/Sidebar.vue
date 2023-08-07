<template>
  <div>
    <v-app dark>
      <v-app-bar
        elevation="0"
        class="container rounded-xxl mt-9 py-0"
        color="#fff"
        height="73px"
        style="border: 1px solid #D7E0E8;"
      >
        <div style="width: 100%;" class="d-flex align-center justify-space-between">
          <nuxt-link to="/">
            <p class="d-flex align-center mb-0"><img src="/logo.svg" alt="logo" class="mr-2">Test<span
              style="color: #45A4FF;">Design</span></p>
          </nuxt-link>
          <div>
            <ul class="d-flex justify-space-between">
              <li><a href="#">Portfolio</a></li>
              <li><a href="#xizmatlar">Bizning xizmatlarimiz</a></li>
              <li><a href="#xamkorlar">Hamkorlarimiz</a></li>
            </ul>
          </div>
          <div>
            <v-btn elevation="0" text>
              <v-icon>mdi-phone-outline</v-icon>
              <span class="pl-2">+998 97 628 28 82</span>
            </v-btn>
          </div>
        </div>
      </v-app-bar>
      <v-main>
        <v-container>
          <Nuxt/>
        </v-container>
      </v-main>
      <v-footer
        class="rounded-xxl container"
        color="#fff"
      >
        <FooterComponents/>
      </v-footer>
    </v-app>
  </div>
</template>
<script>

import FooterComponents from "@/components/Footer.vue";

export default {
  name: 'SidebarPage',
  components: {FooterComponents},
  data() {
    return {}
  }
}
</script>

<style lang="scss" scoped>
v-toolbar__content{
  display: contents;
}
v-application--wrap{
  background-color: red!important; ;
}
a{
  color: black;
  text-decoration: none;
}
ul {
  li {
    list-style-type: none;
    padding: 0 30px;

    a {
      text-decoration: none;
      color: black;
    }
  }
}
</style>
