<template>
  <div>
      <h1>Product Page</h1>
      <router-link :to="{name: 'ProductDetail'}">
          Detail
      </router-link>
  </div>
</template>

<script>
export default {
    name: 'product-index'
}
</script>

<style>

</style>