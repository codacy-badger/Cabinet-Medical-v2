<template>
  <div>
     <Header/>
    <router-view />
    <ScrollButton/>
  </div>
</template>

<script>
import Header from './components/Header';
import ScrollButton from './components/ScrollButton'

export default {
  name: "App",
  components: {
    Header,
    ScrollButton
  }
};
</script>
