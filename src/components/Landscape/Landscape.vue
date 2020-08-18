<template>
  <div>
    <img class="landscape" :src="actualImage" />
  </div>
</template>

<script>
export default {
  props: [
    'actualImage'
  ]
}
</script>

<style>
  .landscape{
    width: 50%;
    border: 6px solid white;
    box-shadow: 2px 3px 6px black;
  }
</style>