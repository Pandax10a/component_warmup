<template>
    <div>
        <h1>Asus Laptop</h1>
        <h3>
ASUS Laptop meets a wide range of exclusive usability features, a diverse color choice, and always-great affordability for everyone.</h3>
<product-gallery/>
    </div>
</template>

<script>
import productGallery from './productGallery.vue'
    export default {
  components: { productGallery },
        name: 'product-info'
    }
</script>

<style scoped>
h1, h3 {
    text-align: center;
}

</style>