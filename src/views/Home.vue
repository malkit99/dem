<template>
  <div class="home">
    <h1>Macroword</h1>
 
   <v-btn flat class="pink white--text"> 
     click me
   </v-btn>

   <v-btn flat small="default" color="primary">
   <v-icon left small="default" >email</v-icon>
   <span> Send Email</span>
   </v-btn>

   <v-btn fab small dark color="purple">
   <v-icon >favorite</v-icon>
   </v-btn>

   
  </div>
</template>

<script>
export default {
  name: 'home',
 
}
</script>
