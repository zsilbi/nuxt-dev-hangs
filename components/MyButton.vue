<script setup lang="ts">
/**
 * This does not work
/*/
import { MyLink } from "#components";

const render = () => {
  return h(MyLink, {}, () => "Button");
};

/**
 * This doesn't work either
 */
// import { NuxtLink } from "#components";
// 
// const render = () => {
//   return h(NuxtLink, {}, () => "Button");
// };

/**
 * This works
 */
// import MyLink from "./MyLink.vue"
// 
// const render = () => {
//   return h(MyLink, {}, () => "Button");
// };
</script>

<template>
  <render />
</template>
