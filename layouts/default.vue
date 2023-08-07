<template>
  <div>
    <v-container class="elevation-0">
      <SidebarPage/>
    </v-container>
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
