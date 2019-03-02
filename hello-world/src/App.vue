<template lang="pug">
  v-app
    v-content
      v-container
        v-layout.row.wrap
          v-flex.xs6.pa-1
            HelloWorld(text="This is a success alert!")
          v-flex.xs6.pa-1
            TestComponent(text="Thi is a warning alert!")
</template>

<script>

import HelloWorld from './components/HelloWorld'
import TestComponent from './components/TestComponent';

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestComponent
  },
  data () {
    return {
      //
    }
  }
}
</script>
