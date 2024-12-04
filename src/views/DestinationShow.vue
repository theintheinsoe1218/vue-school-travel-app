<template>
  <div class="about">
    <h1>{{ destination.name }}</h1>
    <section class="destination">
      <div class="destination-details">
        <img :src="`/images/${destination.image}`" :alt="destination.name">
        <p>{{ destination.description }}</p>
      </div>
    </section>
   
  </div>
</template>
<script>
  import sourceData from '../data.json'
export default {
  data: () => ({
    
  }),
   props: {},
  mounted: function() {},
  methods: {},
  watch: {},
  components: {

  },
  computed:{
    destinationId(){
      return parseInt(this.$route.params.id);
    },
    
    destination(){
      return sourceData.destinations.find(destination=>destination.id === this.destinationId)
    }

  }

};
</script>
<style scoped>

</style>