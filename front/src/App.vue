<template>
  <div>
    <router-view />
  <Header/>
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  name: "App",
  components: {
    Header
  }
};
</script>
