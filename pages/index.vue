<template>
  <div class="wrapper">
    <h2>Tailwinds Css with Nuxt Js</h2>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.wrapper {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
  h2 {
    @apply 2xl:text-6xl lg:text-4xl md:text-3xl sm:text-2xl 
    font-bold p-5 text-green-600 bg-red-200 rounded-lg shadow-lg;
  }
}
</style>
