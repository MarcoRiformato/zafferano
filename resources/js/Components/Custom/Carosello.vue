<template>
  <div class="container mx-auto">
    <div class="flex flex-wrap">

     <Zaffesiccato/>
     <The/>
     <Profumo/>

    </div>
  </div>
</template>
<script setup>
import The from './Prodotti/the.vue';
import Zaffesiccato from './Prodotti/zaffesiccato.vue';
import Profumo from './Prodotti/profumo.vue';
import SingleCard from './SingleCard.vue';


</script>