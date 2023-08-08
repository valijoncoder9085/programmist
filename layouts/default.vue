<template>
  <div>
    <SidebarPage/>
    <v-btn @click="toTopScroll" ref="to-top" id="to-top" class="rounded-xl"
           style="background:linear-gradient(139deg, #0677E1 0%, #8C1FE2 100%);" dark>
      <v-icon>
        mdi-chevron-up
      </v-icon>
    </v-btn>
  </div>
</template>

<script>
import SidebarPage from "~/components/Sidebar.vue";
import FooterComponents from "@/components/Footer.vue";

window.addEventListener('scroll', () => {
  const btn = document.getElementById('to-top');
  const scrolled = window.scrollY;
  if (scrolled > 500) {
    btn.style.opacity = "1";
  } else {
    btn.style.opacity = "0";
  }
})
export default {
  name: 'DefaultLayout',
  components: {FooterComponents, SidebarPage},
  methods: {
    toTopScroll() {
      window.scrollTo({
        top: 0,
        behavior: 'smooth',
      })
    }
  }
}
</script>
<style lang="scss">
#to-top {
  position: fixed;
  right: 20px;
  bottom: 20px;
  opacity: 0;
  transition: all .5s ease;
}

@media (max-width: 980px) {
  .v-application--wrap {
    padding: 0 10px !important;
  }
}
</style>
