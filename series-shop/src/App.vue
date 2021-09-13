<template>
  <div id="app">
    <the-header></the-header>
        <div class="d-flex flex-row">
      // components
    </div>
  </div>
  
</template>

<script>
import TheHeader from './components/TheHeader';
import Shop from './components/Shop/Shop';
import Cart from './components/Cart/Cart';

export default {
  name: 'app',
  components: {
    TheHeader,
    Cart,
    Shop
  }
}
</script>

