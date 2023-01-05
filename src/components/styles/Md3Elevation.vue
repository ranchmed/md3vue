<script setup></script>

<template>
  <div class="elevation">
    <div class="md-sys-elevation-level0">Level 0 (none)</div>
    <div class="md-sys-elevation-level1">Level 1 (1px)</div>
    <div class="md-sys-elevation-level2">Level 2 (3px)</div>
    <div class="md-sys-elevation-level3">Level 3 (6px)</div>
    <div class="md-sys-elevation-level4">Level 4 (8px)</div>
    <div class="md-sys-elevation-level5">Level 5 (12px)</div>
  </div>
</template>

<style lang="scss">
.elevation {
  display: flex;
  gap: 1rem;
  margin-bottom: 1rem;
  div {
    align-items: center;
    background-color: var(--md-sys-color-surface-light);
    display: flex;
    justify-content: center;
    height: 100px;
    padding: 1rem;
    width: 100px;
  }
}
</style>
