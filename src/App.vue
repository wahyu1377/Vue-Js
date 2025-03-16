<script setup>
import HelloWorld from './components/HelloWorld.vue'
import belajar1  from './components/belajar1.vue'
import belajar2 from './components/belajar2.vue'
import Belajar3 from './components/belajar3.vue'
import belajar4 from './components/belajar4.vue'
import belajar5 from './components/belajar5.vue'

</script>

<template>
  <HelloWorld/>
  <belajar1/>
  <belajar2/>
  <Belajar3/>
  <belajar4/>
  <belajar5/>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
