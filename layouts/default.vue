<template>
  <div class="layout">
    <nuxt class="nuxt-content"/>
    <Footer/>
  </div>
</template>
<script>

</script>
<style lang="scss">
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.nuxt-content {
  flex-grow: 1;
}
</style>
