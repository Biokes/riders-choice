<template>
    <nav>
        <section>
            <p class='rider'>Riders</p>
            <p class='choice'>choice</p>
        </section>
    </nav>
</template>

<script>
    export default {
        name: 'Navbar',
    };
</script>
<style scoped>
    .rider{
        color:red;
        font-size: 15px;
        font-weight:700;
    }
    .choice{
        color:rgb(112, 196, 245);
        font-size:11px;
        font-weight: 600;
        padding: 6px;
    }
    section{
        display:flex;
        justify-content: start;
        flex-direction: column;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        padding: 15px;
    }
</style>
