<script setup></script>

<template>
  <ul class="list">
    <li class="list__container list__container--oneline">
      <div class="list__container-left"></div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">Line 1</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--twoline">
      <div class="list__container-left"></div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">Line 1<br>Line 2</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--threeline">
      <div class="list__container-left"></div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">Line 1<br>Line 2<br>Line 3</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--oneline list__container--has-leading-icon">
      <div class="list__container-left">
        <span class="list__icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M9 11.75a1.25 1.25 0 1 0 0 2.5 1.25 1.25 0 0 0 0-2.5zm6 0a1.25 1.25 0 1 0 0 2.5 1.25 1.25 0 0 0 0-2.5zM12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8 0-.29.02-.58.05-.86 2.36-1.05 4.23-2.98 5.21-5.37a9.974 9.974 0 0 0 10.41 3.97c.21.71.33 1.47.33 2.26 0 4.41-3.59 8-8 8z"/></svg>
        </span>
      </div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">One line w leading icon</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--oneline list__container--has-leading-avatar">
      <div class="list__container-left">
        <img class="list__avatar" src="src/assets/images/mark-cropped-500x500.png" />
      </div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">One line w leading avatar</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--oneline list__container--has-leading-thumbnail">
      <div class="list__container-left">
        <img class="list__thumbnail" src="src/assets/images/mark-cropped-500x500.png" />
      </div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">One line w leading thumbnail</p>
      </div>
      <div class="list__container-right"></div>
    </li>
    <li class="list__container list__container--oneline list__container--has-trailing-icon">
      <div class="list__container-left"></div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">One line w trailing icon</p>
      </div>
      <div class="list__container-right">
        <span class="list__trailing-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M9 11.75a1.25 1.25 0 1 0 0 2.5 1.25 1.25 0 0 0 0-2.5zm6 0a1.25 1.25 0 1 0 0 2.5 1.25 1.25 0 0 0 0-2.5zM12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8 0-.29.02-.58.05-.86 2.36-1.05 4.23-2.98 5.21-5.37a9.974 9.974 0 0 0 10.41 3.97c.21.71.33 1.47.33 2.26 0 4.41-3.59 8-8 8z"/></svg>
        </span>
      </div>
    </li>
    <li class="list__container list__container--oneline list__container--has-trailing-text">
      <div class="list__container-left"></div>
      <div class="list__container-center">
        <h1 class="list__headline">List title</h1>
        <p class="list__text">One line w trailing text</p>
      </div>
      <div class="list__container-right">
        <span class="list__trailing-text">100+</span>
      </div>
    </li>
</ul>
</template>

<style scoped lang="scss">
@import "../tokens/scss/variables.scss";
.list {
  $listwidth: 350px;
  $wireframe: 1px solid #ccc;
  background-color: $md-ref-palette-neutral-99;
  display: flex;
  flex-direction: column;
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 100%;
  &__container {
    background-color: white;
    border: 1px solid #eee;
    display: flex;
    flex-direction: row;
    margin-bottom: 1rem;
    width: $listwidth;
    &-left {
      align-items: center;
      display: flex;
      flex-basis: 0;
      justify-content: center;
    }
    &-center {
      align-items: left;
      display: flex;
      flex-basis: 350px;
      flex-direction: column;
      justify-content: center;
      padding: 8px 24px 8px 16px;
    }
    &-right {
      align-items: center;
      display: flex;
      flex-basis: 0;
      justify-content: center;
    }
    &--oneline {
      height: auto;
    }
    &--twoline {
      height: 72px;
    }
    &--threeline {
      height: 88px;
    }
    &--has-leading-icon {
      .list__container-left {
        flex: 0 1 56px;
        padding: 8px 16px 8px 16px;
      }
      .list__container-center {
        flex: 0 1 294px;
        padding: 8px 24px 8px 0;
      }
      .list__container-right {
        flex-basis: 0;
      }
    }
    &--has-leading-avatar {
      .list__container-left {
        flex: 0 1 72px;
        padding: 8px 16px 8px 16px;
      }
      .list__container-center {
        flex: 0 1 278px;
        padding: 8px 24px 8px 0;
      }
      .list__container-right {
        flex-basis: 0;
      }
    }
    &--has-leading-thumbnail {
      .list__container-left {
        flex: 0 1 88px;
        padding: 8px 16px 8px 16px;
      }
      .list__container-center {
        flex: 0 1 262px;
        padding: 8px 24px 8px 0;
      }
      .list__container-right {
        flex-basis: 0;
      }
    }
    &--has-trailing-icon {
      .list__container-left {
        flex-basis: 0;
      }
      .list__container-center {
        flex: 0 1 262px;
        padding: 8px 0 8px 24px;
      }
      .list__container-right {
        flex: 0 1 88px;
        padding: 8px 24px 8px 16px;
      }
    }
    &--has-trailing-text {
      .list__container-left {
        flex-basis: 0;
      }
      .list__container-center {
        flex: 0 1 262px;
        padding: 8px 0 8px 24px;
      }
      .list__container-right {
        flex: 0 1 88px;
        padding: 8px 24px 8px 16px;
      }
    }
  }
  &__headline {
    color: $md-sys-color-on-surface;
    font-size: 16px;
    line-height: 1.5;
  }
  &__text {
    color: $md-sys-color-on-surface;
    font-size: 14px;
    line-height: 1.5;
  }
  &__trailing-text {
    font-size: 12px;
  }
  &__trailing-icon {
    height: 24px;
    width: 24px;
  }
  &__divider {}
  &__avatar {
    border-radius: 50%;
    height: 40px;
    padding: 0;
    width: 40px;
  }
  &__icon {
    height: 24px;
    width: 24px;
  }
  &__thumbnail {
    height: 56px;
    padding: 0;
    width: 56px;
  }
}
</style>
