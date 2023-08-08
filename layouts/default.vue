<template>
  <div>
    <SidebarPage/>
  </div>
</template>

<script>
import SidebarPage from "~/components/Sidebar.vue";
import FooterComponents from "@/components/Footer.vue";

export default {
  name: 'DefaultLayout',
  components: {FooterComponents, SidebarPage},

}
</script>
<style lang="scss">
@media (max-width: 980px) {
  .v-application--wrap {
    padding: 0 10px !important;
  }
}
</style>
