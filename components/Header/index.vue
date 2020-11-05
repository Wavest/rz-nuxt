<template>
  <div class="flex w-full shadow">
    <div class="flex container mx-auto items-center">
      <div class="w-1/3">
        Logo
      </div>
      <div class="flex">
        <NavItem title="Tentang Kami" path="/madun" />
        <NavItem title="Zakat" path="/madun" />
        <NavItem title="Program" path="/madun" />
        <NavItem title="Layanan" path="/madun" />
        <NavItem title="Kolaborasi" path="/madun" />
      </div>
      <BtnRectangle text="Donasi" path="/donasi" />
    </div>
  </div>
</template>

<script>
import Rectangle from '../Button/Rectangle'
import NavigationItem from './NavigationItem'

export default {
  components: {
    NavItem: NavigationItem,
    BtnRectangle: Rectangle
  }
}
</script>

<style></style>
