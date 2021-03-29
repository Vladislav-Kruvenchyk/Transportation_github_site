<template>
  <div id="app">
    <vHeader />
    <vNavbar />
    <vImgHeader />
    <vCountry />
    <vService />
    <vCompany />
    <vMap />
    <vFooter />
  </div>
</template>
<script>
import vHeader from './components/header'
import vNavbar from './components/navbar'
import vImgHeader from './components/imgHeader'
import vCountry from './components/country'
import vService from './components/service'
import vCompany from './components/company'
import vMap from './components/map'
import vFooter from './components/footer'
export default {
  name: 'App',
  components: {
    vHeader,
    vNavbar,
    vImgHeader,
    vCountry,
    vService,
    vCompany,
    vMap,
    vFooter,
  },
}
</script>

<style lang="scss">
* {
  width: 100%;
  overflow-x: hidden;
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  text-decoration: none;
  outline: none;
  cursor: default;
}
body::-webkit-scrollbar {
  width: 1em;
  background: #c8a35f;
}
body::-webkit-scrollbar-thumb {
  height: 40px;
}

body::-webkit-scrollbar-track {
  box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
  height: 20px;
}
body::-webkit-scrollbar-thumb {
  background: #2f343a;
  outline: 1px solid slategrey;
  height: 20px;
}
@font-face {
  font-family: 'Roboto_bold';
  src: local('Roboto Bold'), local('Roboto-Bold'),
    url('./assets/fonts/roboto/Robotobold.woff2') format('woff2'),
    url('./assets/fonts/roboto/Robotobold.woff') format('woff'),
    url('./assets/fonts/roboto/Robotobold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
}
@font-face {
  font-family: 'Roboto';
  src: local('Roboto Thin'), local('Roboto-Thin'),
    url('./assets/fonts/roboto/Roboto.woff2') format('woff2'),
    url('./assets/fonts/roboto/Roboto.woff') format('woff'),
    url('./assets/fonts/roboto/Roboto.ttf') format('truetype');
  font-weight: 100;
  font-style: normal;
}
</style>
