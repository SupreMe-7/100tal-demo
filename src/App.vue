<template>
  <div id="app">
    <class-magic />
    <classTrack />
    <classVideo />
  </div>
</template>

<script>
import classMagic from './components/classMagic.vue'
import classTrack from './components/classTrack.vue'
import classVideo from './components/classVideo.vue'
export default {
  name: 'App',
  components: {
    classMagic,
    classTrack,
    classVideo
  }
}
</script>

<style>
 * {
    list-style: none;
    margin: 0;
    padding: 0;
 }
 html {
   font-size: calc(100vw/7.5);
   background-color: rgb(245, 245, 245);
 }

</style>
