<script setup></script>

<template>
  <h3>Theme base colors</h3>
  <div class="theme-colors">
    <div class="c1">#525942<br />Primary</div>
    <div class="c2">#a6a15d<br />Secondary</div>
    <div class="c3">#d9b68b<br />Tertiary</div>
    <div class="c4">#592918</div>
    <div class="c5">#bf6956</div>
  </div>
  <div class="theme-colors">
    <div class="cl1">Primary Light</div>
    <div class="cl2">Secondary Light</div>
    <div class="cl3">Tertiary Light</div>
  </div>
  <div class="theme-colors">
    <div class="cd1">Primary Dark</div>
    <div class="cd2">Secondary Dark</div>
    <div class="cd3">Tertiary Dark</div>
  </div>
  <h3>Containers</h3>
  <div class="theme-colors">
    <div class="cs1">Surface</div>
    <div clas="cs2">Surface Variant</div>
  </div>
  <h3>Errors</h3>
  <div class="theme-colors">
    <div class="ce1">Error Container</div>
    <div class="ce2">Error</div>
  </div>
</template>

<style scoped lang="scss">
/* Color Theme Swatches in Hex */
$The-bay-horse-gallops-on-the-grass-1-hex: #525942;
$The-bay-horse-gallops-on-the-grass-2-hex: #a6a15d;
$The-bay-horse-gallops-on-the-grass-3-hex: #d9b68b;
$The-bay-horse-gallops-on-the-grass-4-hex: #592918;
$The-bay-horse-gallops-on-the-grass-5-hex: #bf6956;

/* Color Theme Swatches in RGBA */
$The-bay-horse-gallops-on-the-grass-1-rgba: rgba(81, 89, 66, 1);
$The-bay-horse-gallops-on-the-grass-2-rgba: rgba(165, 160, 92, 1);
$The-bay-horse-gallops-on-the-grass-3-rgba: rgba(216, 181, 138, 1);
$The-bay-horse-gallops-on-the-grass-4-rgba: rgba(89, 41, 24, 1);
$The-bay-horse-gallops-on-the-grass-5-rgba: rgba(191, 105, 86, 1);

/* Color Theme Swatches in HSLA */
$The-bay-horse-gallops-on-the-grass-1-hsla: hsla(78, 14%, 30%, 1);
$The-bay-horse-gallops-on-the-grass-2-hsla: hsla(56, 29%, 50%, 1);
$The-bay-horse-gallops-on-the-grass-3-hsla: hsla(33, 50%, 69%, 1);
$The-bay-horse-gallops-on-the-grass-4-hsla: hsla(16, 57%, 22%, 1);
$The-bay-horse-gallops-on-the-grass-5-hsla: hsla(11, 45%, 54%, 1);

.theme-colors {
  display: flex;
  gap: 1rem;
  margin-bottom: 1rem;
  div {
    align-items: center;
    display: flex;
    height: 100px;
    justify-content: center;
    padding: 1rem;
    text-align: center;
    width: 100px;
  }
  .c1 {
    background-color: $The-bay-horse-gallops-on-the-grass-1-hex;
  }
  .c2 {
    background-color: $The-bay-horse-gallops-on-the-grass-2-hex;
  }
  .c3 {
    background-color: $The-bay-horse-gallops-on-the-grass-3-hex;
  }
  .c4 {
    background-color: $The-bay-horse-gallops-on-the-grass-4-hex;
  }
  .c5 {
    background-color: $The-bay-horse-gallops-on-the-grass-5-hex;
  }
  .cl1 {
    background-color: var(--md-sys-color-primary);
    color: var(--md-sys-color-on-primary-light);
  }
  .cl2 {
    background-color: var(--md-sys-color-secondary);
    color: var(--md-sys-color-on-secondary-light);
  }
  .cl3 {
    background-color: var(--md-sys-color-tertiary);
    color: var(--md-sys-color-on-tertiary-light);
  }
  .cd1 {
    background-color: var(--md-sys-color-primary-dark);
    color: var(--md-sys-color-on-primary-dark);
  }
  .cd2 {
    background-color: var(--md-sys-color-secondary-dark);
    color: var(--md-sys-color-on-secondary-dark);
  }
  .cd3 {
    background-color: var(--md-sys-color-tertiary-dark);
    color: var(--md-sys-color-on-tertiary-dark);
  }
  .cs1 {
    background-color: var(--md-sys-color-surface);
    color: var(--md-sys-color-on-surface)
  }
  .cs2 {
    background-color: var(--md-sys-color-surface-variant);
    color: var(--md-sys-color-on-surface-variant)
  }
  .ce1 {
    background-color: var(--md-sys-color-error-container);
    color: var(--md-sys-color-on-error-container)
  }
  .ce2 {
    background-color: var(--md-sys-color-error);
    color: var(--md-sys-color-on-error)
  }
}
</style>
