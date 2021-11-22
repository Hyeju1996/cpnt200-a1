<template>
  <div id="app">
    <img :src="image" />
  </div>
</template>

<script>
import image from "./assets/logo.png";

export default {
  data: function () {
    return {
      image: image,
    };
  },
};
</script>