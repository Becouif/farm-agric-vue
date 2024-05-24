<script setup>
import {ref} from 'vue'
let year= ref(null);

let date = new Date().getFullYear();
year.value = date;

</script>

<template>
  <footer id="footer" class="bg-green-800 text-gray-50">
    <div class="text-center m-auto ">
        <!-- <h1 class=" h1 font-bold text-3xl">Year </h1> -->
        <p class=""><i class="fa fa-copyright" aria-hidden="true"></i>
            <span class=""> 2024 - {{year}} design and developed by Blessing Afolabi </span> </p>
    </div>

</footer>

</template>
<style scoped>
/* my footer section css */
#footer {
  font-size: 1rem;
  margin: auto;
    padding: 2rem;
    font-family: 'Alegreya Sans', sans-serif;
}




</style>