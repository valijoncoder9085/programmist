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
