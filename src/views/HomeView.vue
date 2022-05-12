<template>
  <Banner/>
  <div class="main-container">
    <h1 style="margin-left: 22px">Monte o seu burguer:</h1>
    <BurgerForm/>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';


export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm
}
}
</script>
