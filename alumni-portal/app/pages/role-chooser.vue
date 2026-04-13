<template>
  <div class="screen">
    <div class="logo">
      <img src="/crest.svg" alt="AdDU crest" />
    </div>
    <h1 class="auth-title">Access Your Portal</h1>
    <p class="auth-subtitle">Select your role to continue</p>

    <NuxtLink to="/home" class="role-card">
      <div class="role-icon">
        <svg class="icon" viewBox="0 0 24 24" fill="none">
          <path d="M4 9l8 4 8-4" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round" />
          <path d="M4 9v6l8 4 8-4V9" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round" />
        </svg>
      </div>
      <div class="role-text">
        <h4>Alumni</h4>
        <p>Add your donations and explore network</p>
      </div>
      <span aria-hidden="true">></span>
    </NuxtLink>

    <NuxtLink to="/admin/home" class="role-card">
      <div class="role-icon">
        <svg class="icon" viewBox="0 0 24 24" fill="none">
          <path d="M7 10a5 5 0 1 1 10 0v4H7v-4z" stroke="currentColor" stroke-width="1.6" />
          <path d="M5 14h14v5H5z" stroke="currentColor" stroke-width="1.6" />
        </svg>
      </div>
      <div class="role-text">
        <h4>Administrator</h4>
        <p>Access portal management tools</p>
      </div>
      <span aria-hidden="true">></span>
    </NuxtLink>

    <div class="center" style="margin-top: 18px;">
      <NuxtLink to="/login" class="text-link">Need help or support?</NuxtLink>
    </div>

    <div class="legal">
      Ateneo de Davao University<br />
      Data Privacy &nbsp;-&nbsp; Terms of Service
    </div>
  </div>
</template>
