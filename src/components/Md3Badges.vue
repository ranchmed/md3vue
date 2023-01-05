<!-- eslint-disable prettier/prettier -->
<script setup></script>

<template>
  <div class="md3-badge">
    <span
      class="md3-badge__icon md3-svg-icon md3-svg-icon--medium md3-svg-icon--baseline"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
      >
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
      </svg>
    </span>
    <div class="md3-badge--large"><span>1</span></div>
  </div>
  <div class="md3-badge">
    <span
      class="md3-badge__icon md3-svg-icon md3-svg-icon--medium md3-svg-icon--baseline"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
      >
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
      </svg>
    </span>
    <div class="md3-badge--small"><span>1</span></div>
  </div>
</template>

<style scoped lang="scss">
.md3-badge {
  position: relative;
  width: max-content;
}
.md3-badge--small {
  background-color: var(--md-sys-color-error);
  border-radius: 3px;
  height: 6px;
  position: absolute;
  top: 5px;
  left: 14px;
  width: 6px;
  span {
    display: none;
  }
}
.md3-badge--large {
  align-items: center;
  background-color: var(--md-sys-color-error);
  border-radius: 8px;
  display: flex;
  height: 16px;
  justify-content: center;
  left: 16px;
  padding: 4px;
  position: absolute;
  top: 0px;
  min-width: 16px;
  span {
    color: var(--md-sys-color-on-error);
    font-size: var(--md-sys-typescale-label-small-font-size);
    font-weight: var(--md-sys-typescale-label-small-weight);
    line-height: var(--md-sys-typescale-label-small-line-height);
  }
}

.md3-svg-icon {
  svg {
    position: relative;
    top: 0.125em;
  }
  &--small {
    svg {
      height: 20px;
      width: 20px;
    }
  }
  &--small-target {
    padding: 20px;
    svg {
      height: 20px;
      width: 20px;
    }
  }
  &--medium {
    svg {
      height: 24px;
      width: 24px;
    }
  }
  &--medium-target {
    padding: 24px;
    svg {
      height: 24px;
      width: 24px;
    }
  }
  &--large {
    svg {
      height: 40px;
      width: 40px;
    }
  }
  &--x-large {
    svg {
      height: 48px;
      width: 48px;
    }
  }
}
</style>
