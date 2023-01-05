<script setup></script>

<template>
  <nav class="navbar">
    <div class="navbar__left">Logo</div>
    <div class="navbar__center">
      <ul class="navbar__menu">
        <li class="navbar__menu-item">
          <a href="#">Home</a>
        </li>
        <li class="navbar__menu-item">
          <a href="#">Health Centers</a>
        </li>
      </ul>
    </div>
    <div class="navbar__right">
      <ul class="navbar__actions">
        <li>
          <button>Search</button>
        </li>
        <li>
          <button>Subscribe</button>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped lang="scss">
.navbar {
  display: flex;
  justify-content: space-between;
  &__left {
    text-align: left;
  }
  &__center {
    text-align: center;
  }
  &__right {
    text-align: right;
  }
  &__logo {
    height: 40px;
    widht: 40px;
  }
  &__menu {
    display: flex;
    list-style-type: none;
  }
  &__menu-item {
  }
  &__actions {
    display: flex;
    list-style-type: none;
  }
}
</style>
