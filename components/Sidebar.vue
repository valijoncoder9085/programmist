<template>
  <div>
    <v-app dark>
      <v-navigation-drawer
        v-model="drawer"
        absolute
        temporary
      >
        <v-card elevation="0">
          <v-card-title>
            <nuxt-link to="/">
              <p class="d-flex align-center mb-0 text-caption"><img src="/logo.svg" alt="logo" width="30"
                                                                    class="mr-2">Test<span
                style="color: #45A4FF;">Design</span></p>
            </nuxt-link>
            <v-spacer/>
            <v-btn @click="drawer = !drawer" icon>
              <v-icon>
                mdi-close
              </v-icon>
            </v-btn>
          </v-card-title>
        </v-card>
        <v-divider/>
        <v-list
          nav
          dense
          class="mt-3"
        >
          <v-list-item-group
            v-model="group"
            active-class="deep-purple--text text--accent-4"
          >
            <v-list-item>
              <v-list-item-title><a href="#">Portfolio</a></v-list-item-title>
            </v-list-item>

            <v-list-item>
              <v-list-item-title><a href="#xizmatlar">Bizning xizmatlarimiz</a></v-list-item-title>
            </v-list-item>

            <v-list-item>
              <v-list-item-title><a href="#xamkorlar">Hamkorlarimiz</a></v-list-item-title>
            </v-list-item>

            <v-list-item>
              <v-list-item-title>
                <v-btn elevation="0" text>
                  <v-icon>mdi-phone-outline</v-icon>
                  <span class="pl-2">+998 97 628 28 82</span>
                </v-btn>
              </v-list-item-title>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-navigation-drawer>
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
            <v-btn class="menu-phone" elevation="0" text>
              <v-icon>mdi-phone-outline</v-icon>
              <span class="pl-2">+998 97 628 28 82</span>
            </v-btn>
            <v-btn @click.stop="drawer = !drawer" class="menu-burger" icon>
              <v-icon>
                mdi-menu
              </v-icon>
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
    return {
      drawer: false,
      group: null,
      items: [
        {title: 'Dashboard', icon: 'mdi-view-dashboard'},
        {title: 'Photos', icon: 'mdi-image'},
        {title: 'About', icon: 'mdi-help-box'},
      ],
    }
  },
  watch: {
    group() {
      this.drawer = false
    },
  },
}
</script>

<style lang="scss" scoped>



.menu-burger {
  display: none;
}

a {
  color: black;
  text-decoration: none;
}

ul {
  li {
    list-style-type: none;
    padding: 0 20px;

    a {
      text-decoration: none;
      color: black;
    }
  }
}

@media (max-width: 880px) {
  ul {
    li {
      display: none;
    }
  }
  .menu-burger {
    display: inline;
  }
}

@media (max-width: 500px) {
  .menu-phone {
    display: none;
  }
}
</style>
