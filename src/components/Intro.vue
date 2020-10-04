<template>
  <div class="into-background-image">
    <v-container>
      <v-row>
        <v-col cols="12" sm="12" md="6" lg="6" xl="6" class="introduction">
          <v-img class="main-intro-image" src="../assets/profilePortfolio.png"></v-img>

          <h1 class="main-intro">Brent Gorwin</h1>
          <h2 class="sub-intro">Front End Developer</h2>
        </v-col>
        <v-col cols="12" sm="12" md="6" lg="6" xl="6">
          <p
            class="into-description"
          >I design and develope experiences that make peoples life easier</p>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.into-background-image {
  background-image: url("../assets/joshua-reddekopp-GkFQEOubrCo-unsplash.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* .introduction {
  height: 95%;
} */

.main-intro {
  margin: 0 auto;
  margin-top: 10px;
  width: 50%;
  padding: 10px;
  text-align: center;
  color: #ffffff;
  font-family: "Julius Sans One", sans-serif;
}

.sub-intro {
  margin: 0 auto;
  margin-bottom: 50px;
  width: 50%;
  padding: 10px;
  text-align: center;
  color: #ffffff;
  font-family: "Julius Sans One", sans-serif;
}

.main-intro-image {
  margin: 0 auto;
  margin-top: 10%;
  border-radius: 50%;
  width: 50%;
  padding: 10px;
  height: 415px;
  width: 415px;
}

.into-description {
  margin: 0 auto;
  margin-top: 25%;
  margin-bottom: 30%;
  width: 70%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
  text-align: center;
  color: #ffffff;
  font-family: "Julius Sans One", sans-serif;
  font-size: 40px;
}
</style>