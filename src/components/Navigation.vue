<template>
  <div>
    <v-toolbar>
      <v-row>
        <v-spacer></v-spacer>
        <ul>
          <li>
            <a>About</a>
          </li>
          <li>
            <a>Projects</a>
          </li>
          <li>
            <a>Contact</a>
          </li>
        </ul>
      </v-row>
    </v-toolbar>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  list-style-type: none;
  margin-right: 5px;
  padding: 0;
  overflow: hidden;
}

li {
  float: right;
}

li a {
  display: block;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 20px;
}

li a:hover {
  background-color: #111;
  color: white;
  border-radius: 10px;
}
</style>