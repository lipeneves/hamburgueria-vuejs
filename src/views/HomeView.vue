<template>
  <Banner />
  <div class="main_container">
    <h1>Monte o seu burguer:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import BurgerForm from '@/components/BurgerForm.vue'

export default {
  name,
  components: { Banner, BurgerForm }
}
</script>
