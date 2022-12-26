<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';

import { ref } from 'vue';
import Services from '../Components/Custom/services.vue';
import Hero from '../Components/Custom/Hero.vue';
import Header from '../Components/Custom/Header.vue';
import Carosello from '../Components/Custom/Carosello.vue';
import MyFooter from '../Components/Custom/MyFooter.vue';
import CtaVue from '../Components/Custom/Cta.vue';
let open = ref(false);
defineProps({
canLogin: Boolean,
canRegister: Boolean,
laravelVersion: String,
phpVersion: String,
});
</script>

<template>
<Head title="Zafferano" />
<Header/>
<Hero/>
<CtaVue/>
<Carosello/>
<Services/>
<MyFooter/>



</template>
