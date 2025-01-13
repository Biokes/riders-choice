<template>
    <div>
        <Navbar/>
        <HeroSection/>
    </div>
</template>
<script>
import Navbar from './navbar.vue';
import Heropage from './hero.vue'

export default {
    name:'Home',
    components: {
        Navbar,
    },
};
</script>