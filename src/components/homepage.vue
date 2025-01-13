<template>
    <div>
        <NavbarComponent/>
        <HeroSection/>
    </div>
</template>
<script>
import NavbarComponent from './navbar.vue';
import HeroSection from './hero.vue';
export default {
    name:'HomepageComponent',
    components: {
        NavbarComponent,
        HeroSection
    },
};
</script>