<script setup lang="ts">
import { defineProps, computed } from 'vue'
import { handleBackground } from '../layoutHelper'

const props = defineProps({
  background: {
    default: '',
  },
})

const style = computed(() => handleBackground(props.background, true))
</script>

<template>
  <div class="slidev-layout section w-full h-full grid from-green-500" :style="style">
    <div class="my-auto w-full">
      <slot />
    </div>
  </div>
</template>
