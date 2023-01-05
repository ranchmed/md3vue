<script setup>
import Md3Color from "./components/styles/Md3Color.vue";
import Md3Elevation from "./components/styles/Md3Elevation.vue";
import Md3Icons from "./components/styles/Md3Icons.vue";
import Md3Motion from "./components/styles/Md3Motion.vue";
import Md3Shape from "./components/styles/Md3Shape.vue";
import Md3Typography from "./components/styles/Md3Typography.vue";
import Md3Badges from "./components/Md3Badges.vue";
import Md3Buttons from "./components/Md3Buttons.vue";
import Md3Cards from "./components/Md3Cards.vue";
import Md3Navbar from "./components/Md3Navigationbar.vue";
import Md3Menu from "./components/Md3Menu.vue";
import Md3List from "./components/Md3List.vue";
</script>

<template>
  <header>
    <Md3Navbar />
  </header>
  <main>
    <h1>Styles</h1>
    <h2>Color</h2>
    <Md3Color />
    <h2>Elevation</h2>
    <Md3Elevation />
    <h2>Icons</h2>
    <Md3Icons />
    <h2>Motion</h2>
    <Md3Motion />
    <h2>Shape</h2>
    <Md3Shape />
    <h2>Typography</h2>
    <Md3Typography />
    <h1>Components</h1>
    <h2>Badges</h2>
    <Md3Badges />
    <h2>Buttons</h2>
    <Md3Buttons />
    <h2>Cards</h2>
    <Md3Cards />
    <h2>Chips</h2>
    <h2>Dialogs</h2>
    <h2>Divider</h2>
    <h2>List</h2>
    <Md3List />
    <h2>Menu</h2>
    <Md3Menu />
    <h2>Navigation bar</h2>
    <Md3Navbar />
    <h2>Navigation drawer</h2>
    <h2>Navigation rail</h2>
    <h2>Progress Indicator</h2>
    <h2>Radio Button</h2>
    <h2>Search</h2>
    <h2>Sliders</h2>
    <h2>Snack bar</h2>
    <h2>Switch</h2>
    <h2>Tabs</h2>
    <h2>Text field</h2>
    <h2>Top app bar</h2>
  </main>
</template>

<style scoped lang="scss">
@import "./tokens/scss/variables.scss";
body {
  padding: 1rem;
}
main {
  padding: 1rem;
}
header {
  background-color: $md-sys-color-surface-tint-dark;
  color: $md-sys-color-on-surface-dark;
  line-height: 1.6;
  margin-bottom: 1rem;
}
</style>
