<script>
import Vue from 'vue';
import { Yo2Sample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    Yo2Sample,
  }
});
</script>

<template>
  <div id="app">
    <yo2-sample />
  </div>
</template>
