<template>
  <Main />
 </template>
 
 <script>
 import Main from '../components/Main.vue'
 
 export default {
   components: {
     Main
 },
   data() {
     return {
       groceryList: [
         { id: 0, text: 'Vegetables' },
         { id: 1, text: 'Cheese' },
         { id: 2, text: 'Whatever else humans are supposed to eat' }
       ]
     }
   }
 }
 
 </script>
 
 <style scoped>
 
 </style>