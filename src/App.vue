<template>
  <div id="app">
    <Nav />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Nav,
    Main,
    Footer,
  }
};
</script>

<style>
@import "~bulma/css/bulma.css";


#app {
  font-family: 'Poppins', sans-serif;
   background-color: #efefef;
}

.px-1,
.p-1 {
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}
.py-1,
.p-1 {
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}

.box-shadow-y {
  box-shadow: 0px 2px 20px rgba(0, 0, 0, 0.05);
}

.menu-container {
  position: fixed;
  bottom: 0;
  margin: auto;
  min-width: 300px;
  z-index: 10;
  background-color: transparent;
  transform: translateX(-100%);
  transition: all ease 0.5s;
}

.menu-container.active {
  transform: translateX(0%);
}
.icon {
  height: 30px;
  width: 30px;
  vertical-align: baseline;
  display: inline-flex;
  justify-content: center;
  align-items: center;
}
.toggler {
  margin-left: 0;
  cursor: pointer;
}

@media (min-width: 769px) {
  .menu-container {
    width: 25%;
    min-width: auto;
    transform: translateX(0%);
  }
}

@media (min-width: 1024px) {
  .menu-container {
    width: 16.6667%;
    min-width: auto;
    transform: translateX(0%);
  }
}

</style>
