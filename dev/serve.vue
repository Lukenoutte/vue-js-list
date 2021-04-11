<script>
import { defineComponent } from 'vue';
import VueJsList from '@/vue-js-list.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    VueJsList
  }
});
</script>

<template>
  <div id="app">
    <vue-js-list />
  </div>
</template>
