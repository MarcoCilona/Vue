<template lang="pug">
  v-alert(value="true", type="success") {{ text }}    
</template>

<script>
  export default {
    props: ['text']
  }
</script>

<style>

</style>
