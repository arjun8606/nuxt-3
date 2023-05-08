<template>
  <div>
    <ProductDetails :product="product"/>
  </div>
</template>

<script setup>
 const { id } = useRoute().params
 const url = 'https://fakestoreapi.com/products/'+ id

 const { data: product } = await useFetch(url)

 definePageMeta({
    layout:'product'
 })
</script>
 
<style>

</style>