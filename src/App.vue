<template>
  <v-app dark>
    <CoreDrawer />

    <CoreAppBar />

    <CoreView />
  </v-app>
</template>

<script>
import CoreDrawer from "@/components/core/Drawer";
import CoreAppBar from "@/components/core/AppBar";
import CoreView from "@/components/core/View";

export default {
  name: "App",
  components: {
    CoreDrawer,
    CoreAppBar,
    CoreView
  },
  data: () => ({
    //
  })
};
</script>
