<template>
  <div class="main">
    <Navbar></Navbar>
    <main> 
      <nuxt />
    </main>
    <footer>
&copy 2020 - test i18n with Nuxt.js
    </footer>
   
  </div>
</template>

<script>
import Navbar from '../components/NavBar'
export default {
  components: {
    Navbar
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
}
.main {
  font-family: 'Roboto', sans-serif;
}
nav {
  background-color: rgb(27, 27, 50);
  padding: 20px;
  color: white;
}
main {
  height: 100%;
  padding: 10px;
  border-radius: 5px;
  margin: 5px;
  border: 1px solid rgb(27, 27, 50);
}

 footer {
  background-color: rgb(238, 238, 240);
  color: rgb(59, 59, 79);
  padding: 25px;
  margin: 5px;
  border-radius: 5px;
}

.spacing{
  /* color: white; */
  margin: 5px;
  padding: 35px;
  border-radius: 5px;
}
.routes {
  color: white;
  margin-right: 35px;
  text-decoration: none;
  font-size: 20px;
}
</style>
