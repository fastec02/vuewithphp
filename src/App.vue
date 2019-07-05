<template>
  <div id="app">
    <Header msg="Test"/>
    <img width="25%" src="./assets/logo.png">
    <MainContaints msg="Build your contents here"/>
    <Footer msg="Test"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Header from "./components/Header";
import Footer from "./components/Footer";
import MainContaints from "./components/MainContaints";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
    Footer,
    MainContaints
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
