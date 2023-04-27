<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ullam, magni cumque hic praesentium, quis rerum, explicabo non nam nulla quae aperiam laboriosam. Quisquam ea harum laboriosam obcaecati ducimus sit praesentium.</p>
        
        <div>{{data}}</div>
    </div>
</template>

<script setup>
    const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>

</style>