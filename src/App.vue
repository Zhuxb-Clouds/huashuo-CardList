<template>
  <HomeHeader></HomeHeader>
  <router-view></router-view>
  <FooterFav />
</template>

<script setup lang="ts">
import { useRouter } from 'vue-router';
import HomeHeader from './components/homeHeader.vue';
import FooterFav from "./components/FooterView.vue";

const router = useRouter()

</script>

<style>
#app {
  font-family: SerifCN;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
