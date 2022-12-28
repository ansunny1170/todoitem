<script>
import Vue from 'vue';
import YechankimCalculator from '@/yechankim-calculator.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    YechankimCalculator
  }
});
</script>

<template>
  <div id="app">
    <yechankim-calculator />
  </div>
</template>
