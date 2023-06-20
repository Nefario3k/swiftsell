<template>
  <div>
    <v-app-bar
      :clipped="clipped"
      :fixed="true"
      height="96"
      app
      hide-on-scroll
      color="#fff"
      elevate-on-scroll
      :elevation="1"
      class="topNav"
    >
      <v-container class="p-0">
        <div class="topBar">
          <!-- logo  -->
          <nuxt-link class="d-block" to="/">
            <div class="flexGap">
              <img src="/image/logo.png" alt="logo" />
              <span>Swiftsell</span>
            </div>
          </nuxt-link>
          <nav>
            <ul class="flexGap">
              <li><nuxt-link to="/">About</nuxt-link></li>
              <li><nuxt-link to="/">Pricing</nuxt-link></li>
              <li><nuxt-link to="/">FAQ</nuxt-link></li>
            </ul>
          </nav>
          <div class="flexGap">
            <v-btn
              color="var(--secondaryColor)"
              height="48"
              width="106"
              outlined
              elevation="0"
              class="Btn Btn__outlined"
              >Log In</v-btn
            >
            <v-btn
              color="var(--primaryColor)"
              height="48"
              width="181"
              class="Btn"
              elevation="0"
              >Sign-up For Free</v-btn
            >
          </div>
        </div>
      </v-container>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
    };
  },
};
</script>

<style lang="scss" scoped>
</style>