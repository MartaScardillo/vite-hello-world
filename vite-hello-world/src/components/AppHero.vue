<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="background">
    
  </div>
</template>

<style scoped>
.background {
    background-image: url(../assets/nahida.png);
}

</style>