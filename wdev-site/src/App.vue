<template>
  <div id="app">
    
    <Header />
    <Home />
    <Footer />
  </div>
</template>

<script>
import './styles/global.css'

import Header from './components/Header';
import Home from './pages/Home';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Home

  }
}
</script>
