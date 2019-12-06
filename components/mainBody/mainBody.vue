<template>
  <section class="products">
    <div v-for="product in products" :key="produto.id" class="procut">
      <img :src="product.img" :alt="produto.nome" class="produto_img" />
      <div>
        <span class="product_price">{{product.price}}</span>
        <h2 class="product_title">{{product.name}}</h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "main",
  props: [],
  data() {
    return {};
  }
};
</script>