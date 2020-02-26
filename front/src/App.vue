<template>
  <div>
     <Header/>
    <router-view />
    <ScrollButton/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header';
import ScrollButton from './components/ScrollButton'
import Footer from './components/Footer'

export default {
  name: "App",
  components: {
    Header,
    ScrollButton,
    Footer
  }
};
</script>
