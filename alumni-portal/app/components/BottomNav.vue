<template>
  <nav class="bottom-nav">
    <NuxtLink to="/home" :class="{ active: isActive('/home') }">
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <path
          d="M4 10.5L12 4l8 6.5v8a1 1 0 0 1-1 1h-4.5v-5h-5v5H5a1 1 0 0 1-1-1v-8z"
          stroke="currentColor"
          stroke-width="1.6"
          stroke-linejoin="round"
        />
      </svg>
      Home
    </NuxtLink>
    <NuxtLink to="/events" :class="{ active: isActive('/events') }">
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <rect x="4" y="6" width="16" height="14" rx="2" stroke="currentColor" stroke-width="1.6" />
        <path d="M8 4v4M16 4v4M4 10h16" stroke="currentColor" stroke-width="1.6" />
      </svg>
      Events
    </NuxtLink>
    <NuxtLink to="/donations" :class="{ active: isActive('/donations') }">
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <path d="M5 12h14" stroke="currentColor" stroke-width="1.6" />
        <path d="M12 5v14" stroke="currentColor" stroke-width="1.6" />
        <rect x="6" y="6" width="12" height="12" rx="2" stroke="currentColor" stroke-width="1.6" />
      </svg>
      Donate
    </NuxtLink>
    <NuxtLink to="/notifications" :class="{ active: isActive('/notifications') }">
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <path
          d="M12 4a6 6 0 0 1 6 6v3.2l1.2 2.2H4.8L6 13.2V10a6 6 0 0 1 6-6z"
          stroke="currentColor"
          stroke-width="1.6"
          stroke-linejoin="round"
        />
        <path d="M9.5 19a2.5 2.5 0 0 0 5 0" stroke="currentColor" stroke-width="1.6" />
      </svg>
      Alerts
    </NuxtLink>
    <NuxtLink to="/profile" :class="{ active: isActive('/profile') }">
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <circle cx="12" cy="8" r="3" stroke="currentColor" stroke-width="1.6" />
        <path d="M5 20a7 7 0 0 1 14 0" stroke="currentColor" stroke-width="1.6" />
      </svg>
      Profile
    </NuxtLink>
  </nav>
</template>

<script setup lang="ts">
const route = useRoute()
const isActive = (path: string) => route.path === path || route.path.startsWith(`${path}/`)
</script>
