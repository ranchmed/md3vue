<script setup></script>

<template>
  <div class="container">
    <div class="s1 shape-none">200x50 None</div>
    <div class="s1 shape-extra-small">200x50 Extra small</div>
    <div class="s1 shape-small">200x50 Small</div>
    <div class="s1 shape-medium">200x50 Medium</div>
    <div class="s1 shape-large">200x50 Large</div>
    <div class="s1 shape-extra-large">200x50 Extra large</div>
    <div class="s1 shape-full">200x50 Full</div>
    <div class="s2 shape-none">50x50 None</div>
    <div class="s2 shape-extra-small">50x50 Extra small</div>
    <div class="s2 shape-small">50x50 Small</div>
    <div class="s2 shape-medium">50x50 Medium</div>
    <div class="s2 shape-large">50x50 Large</div>
    <div class="s2 shape-extra-large">50x50 Extra large</div>
    <div class="s2 shape-full">50x50 Full</div>
  </div>
</template>

<style scoped lang="scss">
.container {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-bottom: 1rem;
  .s1 {
    align-items: center;
    border: 1px solid black;
    display: flex;
    height: 50px;
    justify-content: center;
    width: 200px;
  }
  .s2 {
    align-items: center;
    border: 1px solid black;
    display: flex;
    height: 200px;
    justify-content: center;
    width: 200px;
  }  
  .shape-full {
    border-radius: 50%;
  }
}
</style>