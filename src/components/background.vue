<template>
<div id="teeeet">
    <midd></midd>
</div>
</template>

<script>
import midd from './body.vue'
export default {
  name: 'teeeet',
  components: {
    midd
  }
}
</script>
<style>
#teeeet{
    background-image: url('../assets/back.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    opacity: 0.7;
}
</style>
