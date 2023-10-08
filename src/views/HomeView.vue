<template>
<div>
  <Carousel_View />
  <Toptrending_View />
  <Art_list/>
  <Game_list/>
  <Pro_list/>
</div>
</template>

<script setup>
import Toptrending_View from '@/components/Toptrending_View.vue'
import Carousel_View from '@/components/Carousel_View.vue'
import Art_list from '@/data/nft.js'
import Game_list from '@/data/nft.js'
import Pro_list from '@/data/nft.js'

</script>

<style lang="scss" scoped>

</style>