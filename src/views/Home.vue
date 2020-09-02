<template>
  <div class="home">
    <DL />
    <Features />
  </div>
</template>

<script>
// @ is an alias to /src
import DL from '@/components/home/DL.vue'
import Features from '@/components/home/Features.vue'

export default {
  name: 'Home',
  components: {
    DL,
    Features
  }
}
</script>
