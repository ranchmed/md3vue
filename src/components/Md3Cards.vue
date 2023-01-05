<script setup></script>

<template>
  <div class="container">
    <div class="md3-card md3-card--elevated">
      <span class="state-layer"></span>
      Elevated card content
    </div>
    <div class="md3-card md3-card--filled">
      <span class="state-layer"></span>
      Filled card content
    </div>
    <div class="md3-card md3-card--outlined">
      <span class="state-layer"></span>
      Outlined card content
    </div>
  </div>
</template>

<style scoped lang="scss">
.container {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.md3-card {
  align-items: center;
  border-radius: 12px;
  display: flex;
  flex: 0 1 250px;
  flex-direction: column;
  height: 250px;
  margin-bottom: 1rem;
  justify-content: center;
  &--elevated {
    background-color: var(--md-sys-color-surface);
    border: none;
    box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.2),
      0px 1px 1px 0px rgba(0, 0, 0, 0.14), 0px 2px 1px -1px rgba(0, 0, 0, 0.12);
    color: var(--md-sys-color-on-surface);
    .state-layer {

    }
    &:hover,
    &:focus {
      .state-layer {

      }
    }
  }
  &--filled {
    background-color: var(--md-sys-color-primary);
    border: none;
    box-shadow: none;
    color: var(--md-sys-color-on-primary);
    .state-layer {

    }
    &:hover,
    &:focus {
      .state-layer {

      }
    }
  }
  &--outlined {
    background-color: var(--md-sys-color-surface);
    border: 1px solid var(--md-sys-color-outline);
    box-shadow: none;
    color: var(--md-sys-color-on-surface);
    .state-layer {

    }
    &:hover,
    &:focus {

    }
  }
}
</style>
