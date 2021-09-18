<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="ab">
    <p class="hello"> hello</p>
  </div>
</template>

<style lang="scss">
@import "@/style/base.scss";
$border-color: red;
.ab{
  border: 1px solid red;
  background-color: $border-color;
  width: 375px;
  height: 750px;
  text-align: center;
  .hello{
    color: red;
  }
}
</style>
