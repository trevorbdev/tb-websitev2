<template>
  <div>
    <v-card elevation="2" style="width: 800px">
      <div class="pa-4">
        <h1>Welcome to my product showcase!</h1>
        <p>
          As an innovative developer in Topeka, Kansas, Trevor Beurman has no
          shortage of experience working at various companies across the Topeka
          Metropolitan Area. Beyond those experiences, Trevor has also taken
          time to work on projects outside of his career to further his
          knowledge of various modern web frameworks, CMS systems, web design
          techniques, back-end RESTful APIs, and cloud services.
        </p>
      </div>
    </v-card>
    <div class="pa-4">
      <h1 style="font-weight: 300">Projects</h1>
      <v-row>
        <v-col>
          <a href="https://jokeapp.innov.dev/" target="_blank">
          <v-img
            src="../assets/the_joke_app_web.png"
            width="450"
            height="200"
          >
          </v-img>
          </a>
        </v-col>
      </v-row>
    </div>
    <div class="pa-4">
      <h1 style="font-weight: 300">Websites</h1>
      <v-row>
        <v-col>
          <a href="https://washburnsmallbusiness.com/" target="_blank">
          <v-img
            src="../assets/washburn_sbdc_web.png"
            width="450"
            height="200"
          >
          </v-img>
          </a>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects",
};
</script>
