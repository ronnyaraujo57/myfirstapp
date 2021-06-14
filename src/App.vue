<template>
  <div id="app">
    <appHeader/>
    <appHero/>
    <appPortafolio/>
    <appExperience/>
    <appContact/>
    <appFooter/>
  </div>
</template>

<script>
  import appHeader from './components/appHeader.vue';
  import appHero from './components/appHero.vue';
  import appPortafolio from './components/appPortafolio.vue'
  import appExperience from './components/appExperience.vue'
  import appContact from './components/appContact.vue'
  import appFooter from './components/appFooter.vue'

export default {
  name: 'App',
  components: {
    appHeader, 
    appHero,
    appPortafolio,
    appExperience,
    appContact,
    appFooter
  }
}
</script>

<style>
body{
  font-family: 'Source Sans Pro', sans-serif;
  margin: 0;
}
h1,
h2,
h3,
h4,
h5,
h6{
  font-family: 'Fjalla One', sans-serif;
  font-weight: normal;
}

h1 {
  font-size: 40px;
  line-height: 1.5;
  letter-spacing: -.2px;
  color: white;
  margin: 0;
}

h1 strong {
  color: #026fff;
}

h2{
  color: #026fff;
  text-transform: uppercase;
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: bold;
  font-size: 24px;
  margin-bottom: 40px;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.container {
    width: 1000px;
    margin: 0 auto;
    display: inherit;
    justify-content: inherit;
    align-items: inherit;
    height: inherit;
    flex-wrap: inherit;
  }
</style>
