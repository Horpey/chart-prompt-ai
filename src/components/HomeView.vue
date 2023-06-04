<script lang="ts" setup>
import Sidebar from "./Sidebar.vue";
import MainView from "./MainView.vue";
import { ref } from "vue";

defineProps({
  msg: String,
});
</script>

<template>
  <div class="overflow-hidden w-full h-full relative flex z-0">
    <Sidebar />

    <MainView />
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
