<template>
  <div>
    <h2>HomeView</h2>
    <p>{{ $route.name }}</p>
    <button class="btn btn-primary" @click="() => $router.push('/about')">
      Move About
    </button>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
