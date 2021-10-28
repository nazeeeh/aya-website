<template>
  <v-app>
    
    <v-main>
      <v-container fluid class="pa-0 container">
        <Nuxt />
      </v-container>
    </v-main>
    
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      
    }
  }
}
</script>
<style scoped>
 * {
  margin: 0;
  padding: 0;
}

*, *::after, *::before{
  box-sizing: border-box;
}
/* .container{
  border: 1px solid red;
} */
</style>