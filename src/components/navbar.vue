<template>
    <nav>
        <section>
            <p class="text-red-500 font-[15px] font-[700]">Riders</p>
            <p class="choice font-[11px] font-[60] padding-[7px_4px]">choice</p>
        </section>
    </nav>
</template>

<script>
    export default {
        name: 'NavbarComponent',
    };
</script>
<style scoped>
    .choice{
        color:rgb(112, 196, 245);
    }
    section{
        display:flex;
        justify-content: start;
        flex-direction: column;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        padding: 15px;
    }
</style>
