<script setup></script>

<template>
  <h3>Common buttons</h3>
  <div class="container">
    <button class="md3-button md3-button--elevated">
      <span class="state-layer"></span>
      Elevated
    </button>
    <button class="md3-button md3-button--filled">
      <span class="state-layer"></span>
      Filled
    </button>
    <button class="md3-button md3-button--tonal">
      <span class="state-layer"></span>
      Tonal
    </button>
    <button class="md3-button md3-button--outlined">
      <span class="state-layer"></span>
      Outlined
    </button>
    <button class="md3-button md3-button--text">
      <span class="state-layer"></span>
      Text
    </button>
  </div>
  <h3>Common buttons w/ icons</h3>
  <div class="container">
    <button class="md3-button md3-button--elevated md3-button--has-icon">
      <span class="state-layer"></span>
      <span class="md3-button__icon--elevated">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
      Elevated
    </button>
    <button class="md3-button md3-button--filled md3-button--has-icon">
      <span class="state-layer"></span>
      <span class="md3-button__icon--filled">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
      Filled
    </button>
    <button class="md3-button md3-button--tonal md3-button--has-icon">
      <span class="state-layer"></span>
      <span class="md3-button__icon--tonal">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
      Tonal
    </button>
    <button class="md3-button md3-button--outlined md3-button--has-icon">
      <span class="state-layer"></span>
      <span class="md3-button__icon--outlined">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
      Outlined
    </button>
    <button class="md3-button md3-button--text md3-button--has-icon">
      <span class="state-layer"></span>
      <span class="md3-button__icon--text">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
      Text
    </button>
  </div>
  <h3>Icon buttons</h3>
  <div class="container">
    <button class="md3-icon-button">
      <span class="state-layer"></span>
      <span class="md3-icon-button__icon">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
    </button>
    <button class="md3-icon-button md3-icon-button--toggle">
      <span class="state-layer"></span>
      <span class="md3-icon-button__icon">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
        </svg>
      </span>
    </button>
  </div>
  <h3>Segmented single select buttons</h3>
  <div class="container">
    <div class="md3-segmented-button md3-segmented-button--single-select">
      <button class="md3-button md3-button--segmented">Segment 1</button>
      <button class="md3-button md3-button--segmented">Segment 2</button>
      <button class="md3-button md3-button--segmented">Segment 3</button>
    </div>
  </div>
  <h3>Segmented multiple select buttons</h3>
  <div class="container">
    <div class="md3-segmented-button md3-segmented-button--multi-select">
      <button class="md3-button md3-button--segmented">Segment 1</button>
      <button class="md3-button md3-button--segmented">Segment 2</button>
      <button class="md3-button md3-button--segmented">Segment 3</button>
    </div>
  </div>
  <h3>FAB buttons</h3>
  <div class="container">
    <div
      style="
        position: relative;
        background-color: beige;
        height: 250px;
        width: 250px;
      "
    >
      <button class="md3-fab-button">
        <span class="md3-fab-button__svg-icon">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 2C6.49 2 2 6.49 2 12s4.49 10 10 10a2.5 2.5 0 0 0 2.5-2.5c0-.61-.23-1.2-.64-1.67a.528.528 0 0 1-.13-.33c0-.28.22-.5.5-.5H16c3.31 0 6-2.69 6-6 0-4.96-4.49-9-10-9zm5.5 11c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm-3-4c-.83 0-1.5-.67-1.5-1.5S13.67 6 14.5 6s1.5.67 1.5 1.5S15.33 9 14.5 9zM5 11.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5S7.33 13 6.5 13 5 12.33 5 11.5zm6-4c0 .83-.67 1.5-1.5 1.5S8 8.33 8 7.5 8.67 6 9.5 6s1.5.67 1.5 1.5z"
            />
          </svg>
        </span>
      </button>
    </div>
  </div>
</template>

<style scoped lang="scss">
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 1rem;
}
.md3-button {
  background-color: var(--md-sys-color-primary);
  border: none;
  border-radius: 20px;
  box-shadow: none;
  color: var(--md-sys-color-on-primary);
  font-family: var(--md-sys-typescale-label-large-font-family-name), sans-serif;
  font-size: var(--md-sys-typescale-label-large-font-size);
  font-weight: var(--md-sys-typescale-label-large-font-weight);
  height: 40px;
  line-height: var(--md-sys-typescale-label-large-line-height);
  margin: 0;
  padding: 0 24px;
  position: relative;
  text-decoration: none;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  &__icon--filled {
    fill: var(--md-sys-color-on-primary);
    padding-right: 10px;
  }
  &.md3-button--has-icon {
    padding: 0 24px 0 18px;
  }
  &:hover,
  &:focus {
    box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.2),
      0px 1px 1px 0px rgba(0, 0, 0, 0.14), 0px 2px 1px -1px rgba(0, 0, 0, 0.12);
    .state-layer {
      border-radius: 20px;
      display: block;
      padding: 0;
      margin: 0;
      position: absolute;
      top: 0;
      left: 0;
      background: var(--md-sys-color-on-primary);
      opacity: var(--md-sys-state-hover-state-layer-opacity);
      width: 100%;
      height: 100%;
    }
  }
  &:disabled {
    background-color: rgba(
      #1b1c17,
      0.12
    ); // Hex value of --md-sys-color-on-surface
    color: var(--md-sys-color-on-surface);
    opacity: 0.38;
    &:hover {
      box-shadow: none;
    }
  }
  &__icon--elevated {
    fill: var(--md-sys-color-primary);
    padding-right: 10px;
  }
  &--elevated {
    background-color: var(--md-sys-color-surface);
    box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.2),
      0px 1px 1px 0px rgba(0, 0, 0, 0.14), 0px 2px 1px -1px rgba(0, 0, 0, 0.12);
    color: var(--md-sys-color-primary);
    &:hover,
    &:focus {
      box-shadow: 0px 1px 8px 0px rgba(0, 0, 0, 0.2),
        0px 3px 4px 0px rgba(0, 0, 0, 0.14),
        0px 3px 3px -2px rgba(0, 0, 0, 0.12);
      .state-layer {
        border-radius: 20px;
        display: block;
        padding: 0;
        margin: 0;
        position: absolute;
        top: 0;
        left: 0;
        background: var(--md-sys-color-primary);
        opacity: var(--md-sys-state-hover-state-layer-opacity);
        width: 100%;
        height: 100%;
      }
    }
  }
  &__icon--tonal {
    fill: var(--md-sys-color-on-secondary-container);
    padding-right: 10px;
  }
  &--tonal {
    background-color: var(--md-sys-color-secondary-container);
    color: var(--md-sys-color-on-secondary-container);
    &:hover,
    &:focus {
      .state-layer {
        border-radius: 20px;
        display: block;
        padding: 0;
        margin: 0;
        position: absolute;
        top: 0;
        left: 0;
        background: var(--md-sys-color-primary);
        opacity: var(--md-sys-state-hover-state-layer-opacity);
        width: 100%;
        height: 100%;
      }
    }
  }
  &__icon--outlined {
    fill: var(--md-sys-color-primary);
    padding-right: 10px;
  }
  &--outlined {
    background: none;
    border: 1px solid var(--md-sys-color-on-surface);
    color: var(--md-sys-color-primary);
    &:hover,
    &:focus {
      border: 1px solid var(-md-sys-color-outline);
      box-shadow: none;
      .state-layer {
        border-radius: 20px;
        display: block;
        padding: 0;
        margin: 0;
        position: absolute;
        top: 0;
        left: 0;
        background: var(--md-sys-color-primary);
        opacity: var(--md-sys-state-hover-state-layer-opacity);
        width: 100%;
        height: 100%;
      }
    }
  }
  &__icon--text {
    fill: var(--md-sys-color-primary);
    padding-right: 10px;
  }
  &--text {
    background: none;
    border: none;
    color: var(--md-sys-color-primary);
    &:hover,
    &:focus {
      box-shadow: none;
      .state-layer {
        border-radius: 20px;
        display: block;
        padding: 0;
        margin: 0;
        position: absolute;
        top: 0;
        left: 0;
        background: var(--md-sys-color-primary);
        opacity: var(--md-sys-state-hover-state-layer-opacity);
        width: 100%;
        height: 100%;
      }
    }
  }
  &--icon {
    background: none;
    border: none;
    color: var(--md-sys-color-primary);
    &:hover,
    &:focus {
      box-shadow: none;
      .state-layer {
        border-radius: 20px;
        display: block;
        padding: 0;
        margin: 0;
        position: absolute;
        top: 0;
        left: 0;
        background: var(--md-sys-color-primary);
        opacity: var(--md-sys-state-hover-state-layer-opacity);
        width: 100%;
        height: 100%;
      }
    }
  }
}
.md3-segmented-button {
  display: flex;
}
.md3-icon-button {
  background-color: var(--md-sys-color-primary);
  border: none;
  border-radius: 20px;
  box-shadow: none;
  height: 40px;
  position: relative;
  width: 40px;
  &__icon {
    left: 8px;
    fill: var(--md-sys-color-on-primary);
    height: 24px;
    position: absolute;
    top: 7px;
    width: 24px;
  }
  &:disabled {
    background-color: rgba(
      #1b1c17,
      0.12
    ); // Hex value of --md-sys-color-on-surface
    color: var(--md-sys-color-on-surface);
    opacity: 0.38;
    &:hover {
      box-shadow: none;
    }
  }
  &--toggle {
    background-color: var(--md-sys-color-surface-variant);
    .md3-icon-button__icon {
      background-color: var(--md-sys-color-surface-variant);
      left: 8px;
      fill: var(--md-sys-color-primary);
      height: 24px;
      position: absolute;
      top: 7px;
      width: 24px;
    }
  }
}
.md3-segmented-button {
  button {
    background-color: white;
    border: 1px solid var(--md-sys-color-primary);
    border-radius: 0;
    color: var(--md-sys-color-on-surface);
    &:first-child {
      border-top-left-radius: 20px;
      border-bottom-left-radius: 20px;
      border-right: none;
    }
    &:last-child {
      border-top-right-radius: 20px;
      border-bottom-right-radius: 20px;
      border-left: none;
    }
    &:hover,
    &:focus {
      background-color: rgba(#1b1c17, 0.12);
      box-shadow: none;
      color: var(--md-sys-color-on-surface);
    }
  }
}
.md3-fab-button {
  align-items: center;
  background-color: var(--md-sys-color-primary);
  border: none;
  border-radius: 16px;
  box-shadow: 0px 3px 5px -1px rgba(0, 0, 0, 0.2),
    0px 6px 10px 0px rgba(0, 0, 0, 0.14), 0px 1px 18px 0px rgba(0, 0, 0, 0.12);
  display: flex;
  color: var(--md-sys-color-on-primary);
  height: 56px;
  justify-content: center;
  left: 100px;
  position: absolute;
  top: 100px;
  width: 56px;
  &__svg-icon {
    fill: var(--md-sys-color-on-primary);
  }
}
</style>
