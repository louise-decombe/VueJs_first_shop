<template>
  <div class="w-25 border product-container">
  </div>
</template>

<script>
  export default {
    data() {
      return {
        product: {
          img: 'url-image',
          title: 'Ordinateur',
          description: 'une super affaire',
          price: '1030 €',
        },
      };
    },
  };
</script>

<style>
  .product-container {
    height: 400px;
  }
</style>