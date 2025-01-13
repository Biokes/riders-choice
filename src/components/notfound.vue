<template>
    <div class="justify-center items-center">
        <p class="text-[12px] font-[700]">page not found</p>
        <router-link to="/" class="rounded-[20px] p-[8px_5px] hover:scale-105 transform transition-all duration-[500] ease-in-out backdrop-shadow-sm">
            Return Home
        </router-link>
    </div>
</template>
<script>
export default {
    name:'NotFound'
}
</script>