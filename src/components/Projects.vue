<template>
  <div id="background-c">
    <v-container>
      <v-row>
        <v-col>
          <h1 id="projects-heading">Projects</h1>
          <v-divider></v-divider>
        </v-col>
      </v-row>

      <v-row id="project-row" cols="12" sm="12" md="6" lg="4">
        <v-card
          id="project-cards"
          max-width="355"
          v-for="portfolio in projects"
          :key="portfolio.title"
        >
          <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px"></v-img>

          <v-card-title>{{portfolio.title}}</v-card-title>

          <v-card-subtitle>{{portfolio.description}}</v-card-subtitle>

          <v-card-actions>
            <v-btn color="orange lighten-2" text>View Project</v-btn>
            <v-spacer></v-spacer>
          </v-card-actions>
        </v-card>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data: () => ({
    show: false,
    projects: [
      {
        title: "Emaily",
        description:
          "React project where you can email your customers and collect feedback from them",
        url: "https://murmuring-beyond-13124.herokuapp.com/"
      },
      {
        title: "Restaurant App",
        description:
          "Simple React project utilizing Yelp API to search for a restaurant in the city of your choice",
        url: "https://bgorwin.github.io/restaurant-search/"
      },
      {
        title: "Quiz App",
        description:
          "Javascript project where you can choose a coding language and take a quiz to test your skills",
        url: "https://bgorwin.github.io/quizSurveyProject/"
      }
    ]
  })
};
</script>

<style scoped>
#background-c {
  background-color: #f6f6f6;
  padding-bottom: 100px;
}

#projects-heading {
  margin: 0 auto;
  text-align: center;
  padding: 50px;
  font-size: 45px;
  font-family: "Montserrat", sans-serif;
}

#project-row {
  justify-content: center;
}

#project-cards {
  margin: 5px;
}
</style>