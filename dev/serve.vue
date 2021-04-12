<script>
import { defineComponent } from 'vue';
import VList from '@/vue-js-list.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    VList
  }
});
</script>

<template>
  <div id="app">
    <v-list />
  </div>
</template>
