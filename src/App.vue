<template>
    <Header></Header>
</template>

<script>
import Header from './components/Header'

export default {
  components: {
    Header
  }
}
</script>
 
<style>
@import url('https://fonts.googleapis.com/css?family=Nunito+Sans:300,600,800&display=swap');
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

#app {
  font-family: 'Nunito Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 14px;
  color: hsl(200, 15%, 8%);
}
</style>
