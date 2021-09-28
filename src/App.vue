<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import errGif from '@/assets/401_images/401.gif'

console.log('------------------>', errGif)
export default {
  name: 'App'
}
</script>
