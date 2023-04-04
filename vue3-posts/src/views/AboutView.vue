<template>
  <div>
    <h2>AboutView</h2>
    <p>{{ $route.name }}</p>
    <button class="btn btn-primary" @click="moveHome">Move Home</button>
  </div>
</template>

<script setup>
import { useRouter } from 'vue-router';

const router = useRouter();

const moveHome = () => {
  router.push('/');
};
</script>

<style lang="scss" scoped></style>
