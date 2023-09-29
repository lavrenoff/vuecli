<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import MainComponent from './components/MainComponent.vue'

export default {
  name: 'App',
  components: {
    FooterComponent,
    HeaderComponent,
    MainComponent
  }
}
</script>

<style lang="scss">
#app {  
}

@font-face {
  font-family: "DM Serif Display Regular";
  font-style: normal;
  font-weight: normal;
  src: local("DM Serif Display Regular"),
    url("assets/fonts/DMSerifDisplay-Regular.woff") format("woff");
}

@font-face {
  font-family: "DM Serif Display Italic";
  font-style: normal;
  font-weight: normal;
  src: local("DM Serif Display Italic"),
    url("assets/fonts/DMSerifDisplay-Italic.woff") format("woff");
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "DM Serif Display Regular";
  position: relative;
}

.center {
  padding-left: calc(50% - 600px);
  padding-right: calc(50% - 600px);
}



</style>
