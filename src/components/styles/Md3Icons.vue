<script setup></script>

<template>
  <span class="md3-svg-icon md3-svg-icon--small">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
    >
      <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
    </svg>
  </span>
  <a href="#">
    <span class="md3-svg-icon md3-svg-icon--small-target">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
      >
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
      </svg>
    </span>
  </a>
  <span class="md3-svg-icon md3-svg-icon--medium">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
    >
      <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
    </svg>
  </span>
  <a href="#">
    <span class="md3-svg-icon md3-svg-icon--medium-target">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
      >
        <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
      </svg>
    </span>
  </a>
  <span class="md3-svg-icon md3-svg-icon--large">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
    >
      <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
    </svg>
  </span>
  <span class="md3-svg-icon md3-svg-icon--x-large">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
    >
      <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" />
    </svg>
  </span>
</template>

<style scoped lang="scss">
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
