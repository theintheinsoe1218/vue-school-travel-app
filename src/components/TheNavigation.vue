<template>
    <div id="nav">
        <router-link to="/">Home</router-link> 
        <router-link to="/brazil">Brazil</router-link> 
        <router-link to="/hawaii">Hawaii</router-link> 
        <router-link to="/jamaica">Jamaica</router-link> 
        <router-link to="/panama">Panama</router-link> 
        </div>
  </template>
  <script>
  
  export default {
    
    data: () => ({
      
    }),
     props: {},
    mounted: function() {},
    methods: {},
    watch: {},
    components: {}
  };
  </script>
  <style scoped>
    #nav .vue-school-active-link{
        color: orange;
   
    }
  </style>