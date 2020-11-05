<template>
  <nuxt-link :to="path">
    <div class="rounded-full bg-blue-500 px-4 py-1 text-white">
      {{ text }}
    </div>
  </nuxt-link>
</template>

<script>
export default {
  props: ['text', 'path']
}
</script>

<style lang="scss" scoped></style>
