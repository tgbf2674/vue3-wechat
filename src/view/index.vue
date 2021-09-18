<template>
  <Login></Login>
  {{ state.a }}
</template>

<script lang="ts">
import {defineComponent, reactive} from 'vue';
import Login from './Login.vue';

export default defineComponent({
  name: 'index',
  components: {Login},
  setup() {
    const state = reactive({
      a: 'a'
    });
    return {state};
  }
});
</script>

<style lang="scss" scoped>

</style>
