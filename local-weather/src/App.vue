<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
<SideNav/>
<RouterView/>
</div>
</template>

<script setup>
import { RouterView } from "vue-router";
import SideNav from "./components/sideNav.vue"
</script>

<style lang="scss" scoped></style>
