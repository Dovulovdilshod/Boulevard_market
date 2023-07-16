<template>

    <Navbar />
    <Header />
    <Cards />
    <Phonecards />
    <Footer />
</template>

<script>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Cards from './components/Cards.vue';
import Phonecards from './components/Phonecards.vue';
import Footer from './components/Footer.vue';

export default {
    components: { Navbar, Header, Cards, Phonecards, Footer }
}
</script>
<!-- https://www.figma.com/file/siplAjvvwsMWS4M8TpUYCA/BOULEVARD-MARKET-(Copy)?node-id=0%3A1&mode=dev -->