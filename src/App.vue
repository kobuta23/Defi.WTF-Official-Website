<template>
  <div>
    <Header></Header>
    <!--Router View, for index content please use 'views/Home.vue' instead -->
    <router-view/> 
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";

export default {
  name: "APP",
  components: { Header, Footer },
};
</script>

