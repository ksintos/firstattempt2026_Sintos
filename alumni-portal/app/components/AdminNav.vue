<template>
  <nav class="admin-nav">
    <NuxtLink to="/admin/home" :class="{ active: isActive('/admin/home') }">
      <span class="admin-nav-icon">HM</span>
      Home
    </NuxtLink>
    <NuxtLink to="/admin/donations" :class="{ active: isActive('/admin/donations') }">
      <span class="admin-nav-icon">DN</span>
      Donation
    </NuxtLink>
    <NuxtLink to="/admin/notifications" :class="{ active: isActive('/admin/notifications') }">
      <span class="admin-nav-icon">NT</span>
      Notifications
    </NuxtLink>
  </nav>
</template>

<script setup lang="ts">
const route = useRoute()
const isActive = (path: string) => route.path === path || route.path.startsWith(`${path}/`)
</script>
