<template>
  <div>
      Hello
  </div>
</template>

<script>
export default {
  name: 'Tester',    
  created: function () 
  {
        window.console.log(this.$route.query.test)
  },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
