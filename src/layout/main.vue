<template>
  <div id="main">
    <Header></Header>

    <router-view></router-view>

    <Footer></Footer>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";

export default {
  name: 'Main',
  components: {
    Footer,
    Header,
  }
}
</script>