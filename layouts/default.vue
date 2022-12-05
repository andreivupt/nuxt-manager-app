<template>
  <div class="h-screen">
    <Navbar>
      <slot/>
    </Navbar>
  </div>
</template>

<script setup lang="ts">
import Navbar from "~/components/layout/navbar.vue";
</script>