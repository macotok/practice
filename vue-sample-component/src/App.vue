<style lang="scss">
  @import 'assets/sass/styles';
</style>

<template>
  <div id="app">
    <questionnaire></questionnaire>
  </div>
</template>

<script>
import Questionnaire from './pages/Questionnaire';

export default {
  name: 'app',
  components: {
    Questionnaire,
  },
};
</script>
