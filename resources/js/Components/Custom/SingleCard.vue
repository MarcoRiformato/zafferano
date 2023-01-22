<template>
    <div class="w-full md:w-1/4 px-4 py-6">
        <div class="rounded-lg shadow-md bg-white">
          <div
            class="max-w-xs overflow-hidden bg-white rounded-lg shadow-lg dark:bg-gray-800"
          >
            <div class="px-4 py-2">
              <h1
                class="text-3xl font-bold text-gray-800 uppercase dark:text-white"
              >
                Zafferano
              </h1>
              <p class="mt-1 text-sm text-gray-600 dark:text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi
                quos quidem sequi illum facere recusandae voluptatibus
              </p>
            </div>

            <img
            :src="imageUrl"
            @mouseenter="imageUrl = 'https://pianetadiriserva.it/wp-content/uploads/zafferano.jpg'"
            @mouseleave="imageUrl = 'https://www.hugmilano.it/wp-content/uploads/2018/01/zafferano.jpg'"

              class="object-cover w-full h-48 mt-2"
              alt="Zafferano"
            />

            <CardFooter/>
          </div>
        </div>
      </div>
</template>
<script>
import CardFooter from './Prodotti/CardFooter.vue';

export default {
    data() {
        return {
            imageUrl: "https://www.hugmilano.it/wp-content/uploads/2018/01/zafferano.jpg",
            zoom: false
        };
    },
    components: { CardFooter }
}
</script>
<style>
img {
  transition: transform 0.3s;
}
</style>




