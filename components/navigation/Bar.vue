<template>
  <div>
    <v-app-bar
      :clipped="clipped"
      :fixed="true"
      height="96"
      app
      :hide-on-scroll="false"
      :color="color"
      :elevate-on-scroll="true"
      :elevation="1"
      class="topNav"
    >
      <v-container class="p-0">
        <div class="topBar">
          <div>swsw</div>
          <div>swsw</div>
          <div>swsw</div>
        </div>
      </v-container>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      clipped: (Boolean = false),
    };
  },
};
</script>

<style lang="scss" scoped>
</style>