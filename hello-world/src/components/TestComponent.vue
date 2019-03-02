<template lang="pug">
    v-alert(value="true", type="warning") {{ text }}
</template>

<script>
    export default {
        props: ['text']
    }
</script>

