<template>
  <div id="main">
    <h1>The easiest way to create QR Code</h1>
    <h2>Generate a QR Code and download it!</h2>

    <div id="colorPicker">
      <input v-model="text" />
      <ColorPicker />
    </div>
  </div>
</template>

<script>
import ColorPicker from '../components/ColorPicker.vue';

export default {
  name: 'Main',
  props: {},
  components: {
    ColorPicker,
  },
};
</script>

<style scoped>
#main {
  font-size: 12px;
}

#colorPicker {
  display: flex;
}
</style>
