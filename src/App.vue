<template>
  <div id="app">
    <Titolo provap="La mia prima app con Vue CLI!"></Titolo>
  </div>
</template>

<script>
import Titolo from './components/Titolo.vue'

export default {
  name: 'App',
  components: {
    Titolo,
  },
}
</script>
