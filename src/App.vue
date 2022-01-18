<template>
 

    <v-main>
      <Header />
      <Footer />
    
    </v-main>
  
  
</template>

<script>
import Header from './components/Header.vue';
 import Footer from './components/Footer.vue';


export default {
  name: 'App',

  components: {
    Header,
    Footer,
  },

  data: () => ({
    
    //
  }),
};
</script>
