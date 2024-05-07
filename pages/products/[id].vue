<template>
<div>
    <h1 class="text- 3xl font-sans mx-10 my-10 text text-lime-600">
       Products 
    </h1>
    <p>Detalle del artículo {{ id }} </p>
</div>
</template>

<script setup>
//páginas producto 

const {id} = useRoute().params
</script>