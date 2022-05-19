<template>
  <Header :logo_src="src" :app_name="alt"/>
  <router-view/>
  <Footer />
</template>

<script>

import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    Header,
    Footer
  },

  data(){
    return{
      src: '/img/logo.png',
      alt: 'Hamburgueria VueJS'
    }
  }
}

</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Helvetica, Arial, sans-serif;
  }

  .main_container{
    margin: 50px;
    min-height: 360px;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>
