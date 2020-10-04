<template>
  <div id="about-background-section">
    <v-container>
      <h1 id="about-heading">About Me</h1>
      <v-divider></v-divider>
      <v-row id="description-story">
        <p>
          My name is Brent Gorwin and I am a Front End Engineer and Web Developer. My passion for tech and
          web development started when moving to Austin, Texas and seeing the amazing innovation and tech driven
          companies that are located here.
        </p>
        <br />
        <p>
          I attending The University of Texas at Austin Full Stack Coding Bootcamp and it gave me a great understanding
          of coding and the foundations for beginning a career in Engineering.
        </p>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* * {
  font-family: "Julius Sans One", sans-serif;
  font-family: "Montserrat", sans-serif;
} */

#description-story {
  margin: 10px;
}

#about-background-section {
  padding-bottom: 100px;
}

#about-heading {
  margin: 0 auto;
  text-align: center;
  padding: 50px;
  font-size: 45px;
  font-family: "Montserrat", sans-serif;
}

p {
  margin-top: 10px;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
}
</style>