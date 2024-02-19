<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import {store} from './store'

export default {
  data() {
    return {
      store: store,
    };
  },

  components: { AppHeader, AppMain, AppFooter, },

};

</script>

<template>
</template>

<style>
</style>
