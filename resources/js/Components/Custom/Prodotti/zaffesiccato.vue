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
              Saffrondoro
              </h1>
              <p class="mt-1 text-sm text-gray-600 dark:text-gray-400">
                L'Elba in un pizzico: scopri l'essenza dell'Elba con ogni cucchiaino di Saffrondoro, lo zafferano esiccato della nostra famiglia. Profumo intenso, colore intenso, gusto intenso
              </p>
            </div>

            <img
            :src="imageUrl"
            @mouseenter="imageUrl = 'https://pianetadiriserva.it/wp-content/uploads/zafferano.jpg'"
            @mouseleave="imageUrl = '/images/secco.png'"

              class="object-cover w-full h-full mt-2"
              alt="Zafferano"
            />
            <CardFooter/>
          </div>
        </div>
      </div>
</template>
<script>
import CardFooter from './CardFooter.vue';

export default {
    data() {
        return {
            imageUrl: "/images/secco.png",
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




