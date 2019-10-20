<template>
  <v-card tile flat color="primary" v-bind="$attrs" v-on="$listeners">
    <slot />
  </v-card>
</template>

<script>
export default {
  name: "BaseCard",
  inheritAttrs: false
};
</script>

<style>
</style>