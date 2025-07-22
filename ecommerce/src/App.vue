<script setup>
import Header from "./components/Header.vue";
import ProductList from "./components/ProductList.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <Header />
    <ProductList />
  </main>
  <footer>
    <Footer />
  </footer>
</template>
