<template>
  <nuxt-link
    :to="path"
    class="link px-4 py-5 font-semibold text-gray-600 hover:text-orange-500"
  >
    {{ title }}
  </nuxt-link>
</template>

<script>
export default {
  props: ['title', 'path']
}
</script>

<style scoped>
.link {
  /* color: #333333; */
}
</style>
