<template>
  <CHeader/>
  <div class="app">
    <router-view />
  </div>
</template>

<script setup>
import CHeader from './components/CHeader.vue';


</script>

<style lang="less">
@import './styles/vars.less';

.app {
  max-width: 1440px;
  margin: 0 auto;
  padding: 30px;

  @media @mobile {
    padding: 20px 12px;
  }
}
</style>
