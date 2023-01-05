<!-- eslint-disable prettier/prettier -->
<script script></script>

<template>
  <nav class="menu">
    <div class="menu-container">
      <ul class="menu-list">
        <li class="menu-list__item">
          <a class="menu-list__link" href="#">
            <span class="menu-list__icon"></span>
            <span class="menu-list__text">Menu item 1 text</span>
          </a>
        </li>
        <li class="menu-list__item">
          <a class="menu-list__link" href="#">
            <span class="menu-list__icon"></span>
            <span class="menu-list__text">Menu item 2 text</span>
          </a>
        </li>
        <li class="menu-list__item">
          <a class="menu-list__link" href="#">
            <span class="menu-list__icon"></span>
            <span class="menu-list__text">Menu item 3 text</span>
          </a>
        </li>
        <li class="menu-list__item">
          <a class="menu-list__link" href="#">
            <span class="menu-list__icon"></span>
            <span class="menu-list__text">Menu item 4 text</span>
          </a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style lang="scss">
.menu {
  border: 1px solid #aaa;
  height: 130px;
  position: relative;
  width: 130px;
  &:hover {
    .menu-container {
      transition: left .5s ease-out;
      left: 0%;
    }
  }
  &-container {
    position: absolute;
    left: -100%;
  }
  &-list {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  &__icon {
    width: 40px;
    height: 40px;
  }
  &__text {
    font-size: 14px;
  }
}
</style>
