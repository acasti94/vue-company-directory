<script setup>
  import { ref } from 'vue'
  const brand = ref('🏢 Fake Company Directory')
</script>

<template>
  <nav class="bg-red-500">
    <div class="wrapper">
      <div class="brand">
        <span class="brand-title"> {{ brand }}</span>
      </div>
      <div class="menu">
        <a href="#" class="menu-item">Departments </a>
        <a href="#" class="menu-item">Settings</a> 
        <a href="#" class="menu-item">Logout</a>
      </div>
    </div>
  </nav>
</template>
