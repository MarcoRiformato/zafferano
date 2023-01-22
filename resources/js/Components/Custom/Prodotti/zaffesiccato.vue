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
            @mouseleave="imageUrl = 'https://www.hugmilano.it/wp-content/uploads/2018/01/zafferano.jpg'"

              class="object-cover w-full h-48 mt-2"
              alt="Zafferano"
            />

            <div
              class="flex items-center justify-between px-4 py-2 bg-gray-900"
            >
            <div class="flex items-center">
                <svg aria-hidden="true" class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Rating star</title><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
                <span class="w-1 h-1 mx-1.5 bg-gray-500 rounded-full dark:bg-gray-400"></span>
                <a href="#" class="text-sm font-medium text-gray-900 underline hover:no-underline dark:text-white">73 reviews</a>
            </div>
              <h1 class="text-lg font-bold text-white">€ 20</h1>
              <button
                class="px-2 py-1 text-xs font-semibold text-gray-900 uppercase transition-colors duration-300 transform bg-white rounded hover:bg-gray-200 focus:bg-gray-400 focus:outline-none"
              >
                Add to cart
              </button>
            </div>
          </div>
        </div>
      </div>
</template>
<script>
export default {
  data() {
    return {
        imageUrl: 'https://www.hugmilano.it/wp-content/uploads/2018/01/zafferano.jpg',
      zoom: false
    }
  }
}
</script>
<style>
img {
  transition: transform 0.3s;
}
</style>




