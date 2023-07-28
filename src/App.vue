<script setup>
import NavBar from "./components/NavBar.vue";
import Image from "./components/Image.vue";
import Quote from "./components/Quote.vue";
import AboutUs from "./components/AboutUs.vue";
import CardContainer from "./components/CardContainer.vue";
import Member from "./components/Member.vue"
import Footer from "./components/Footer.vue";
import {RouterView} from "vue-router"

</script>

<template>
<NavBar/>
<Image/>
<Quote/>
<AboutUs/> 
<RouterView/> 
<CardContainer/>
<Member/>
<Footer/>

</template>

<style scoped>

</style>
