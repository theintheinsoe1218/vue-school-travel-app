

<template>
  
  <TheNavigation/>
  <div class="container">

    <router-view/>
  </div>
 
</template>
<script>
import TheNavigation from './components/TheNavigation.vue';


export default {
  data: () => ({
    
  }),
   props: {},
  mounted: function() {},
  methods: {},
  watch: {},
  components: {
    TheNavigation
  }
};
</script>
<style scoped>
</style>

