<template>
  <v-app id="inspire">
    <v-navigation-drawer
      v-model="drawer"
      app
      permanent
      class="pt-4"
      color="#122875"
      mini-variant
    >
      <a href="/"
        ><v-avatar :size="36" class="d-block text-center mx-auto mb-9">
          <img
            src="./assets/Trevor_Beurman_small.png"
            alt="Trevor"
          /> </v-avatar
      ></a>
        <a href="https://github.com/trevorbdev" target="_blank"
          ><v-avatar
            color="grey"
            :size="32"
            class="d-block text-center mx-auto mb-9"
            ><v-icon dark> mdi-github </v-icon>
          </v-avatar></a
        >
        <a href="/tb.cool.resume.pdf" target="_blank"
          ><v-avatar
            color="grey"
            :size="32"
            class="d-block text-center mx-auto mb-9"
            ><v-icon dark> mdi-file </v-icon>
          </v-avatar></a
        >
        <a href="mailto:trevor@innov.dev"
          ><v-avatar
            color="grey"
            :size="32"
            class="d-block text-center mx-auto mb-9"
            ><v-icon dark> mdi-email </v-icon>
          </v-avatar></a
        >
        <a href="tel:7854306019"
          ><v-avatar
            color="grey"
            :size="32"
            class="d-block text-center mx-auto mb-9"
            ><v-icon dark> mdi-phone </v-icon>
          </v-avatar></a
        >
    </v-navigation-drawer>

    <v-main class="ml-4 mt-4 mr-4">
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
export default {
  //
};
</script>
