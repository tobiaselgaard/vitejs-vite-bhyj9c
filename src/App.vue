<script setup>
function showRadialMenu(event) {
  let cursorPositionX = event.x;
  let cursorPositionY = event.y;

  let firstButtonLeftProperty = cursorPositionX;
  let firstButtonTopProperty = cursorPositionY;
}
</script>

<template @click="showRadialMenu" (event)></template>
