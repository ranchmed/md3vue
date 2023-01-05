<script setup></script>

<template>
  <div class="container">
    <div class="easing-standard duration-1000">Hi</div>
  </div>
</template>

<style scoped lang="scss">
.container {
  border: 1px solid red;
  height: 100px;
  position: relative;
  width: 100px;
  &:hover {
    div {
      top: 80px;
      left: 80px;
      transition-property: top, left;
    }
  }
  div {
    background-color: green;
    height: 20px;
    top: 0px;
    left: 0px;
    position: absolute;
    width: 20px;
  }
}
</style>
