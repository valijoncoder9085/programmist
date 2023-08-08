<template>
  <div>
    <v-container>
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
