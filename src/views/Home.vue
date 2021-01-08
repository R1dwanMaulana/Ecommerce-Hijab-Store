<template>
  <div class="home">
    <Header />
    <Baner />
    <Brands />
    <features />
    <Designer />
    <Footer />
  </div>
</template>



<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue';
import Baner from '@/components/Baner.vue';
import Brands from '@/components/Brands.vue';
import Features from '@/components/Features.vue';
import Designer from '../components/Designer.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Baner,
    Brands,
    Features,
    Designer,
    Footer
  }
}
</script>
