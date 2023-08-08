<template>
  <div>
    <SidebarPage/>
    <v-btn @click="clickBtn" ref="to-top" id="to-top" dark class="rounded-lg">
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

  const toTopBtn = document.getElementById('to-top');
  const scrollY = window.scrollY;
  if (Math.ceil(scrollY) > 400) {
    toTopBtn.style.opacity = '1';
  } else {
    toTopBtn.style.opacity = '0'
  }
})
export default {
  name: 'DefaultLayout',
  components: {FooterComponents, SidebarPage},
  methods: {
    clickBtn() {
      window.scrollTo({
        top: 0,
        behavior: 'smooth',
      })
    }
  },
}
</script>
<style lang="scss">
#to-top {
  position: fixed;
  right: 3%;
  bottom: 3%;
  opacity: 0;
  background: linear-gradient(139deg, #0677E1 0%, #8C1FE2 100%);
  transition: all .4s ease;
}

@media (max-width: 980px) {
  .v-application--wrap {
    padding: 0 10px !important;
  }
}
</style>
