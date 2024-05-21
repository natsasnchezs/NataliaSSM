<template>
    <div class="grid grid-cols-2"> 

        <div> 
            <img :src="product.image" alts="">
        </div>
        <div>
            <h2>{{ product.title }}</h2>
            <p>{{ product.price }}</p>
            <h3>{{ product.description }}</h3>
        </div>

    </div>
</template>

<script setup>

</script>

<style scoped>

</style>