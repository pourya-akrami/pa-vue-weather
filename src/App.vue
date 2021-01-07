<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" name="" id="" class="search-bar" placeholder="Search..."/>
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
      api_key: "d86e1c8defd9809d96fc69c302ac3bbf"
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
}
</style>
