<template>
  <div class="screen">
    <div class="logo">
      <img src="/crest.svg" alt="AdDU crest" />
    </div>
    <h1 class="auth-title">Welcome, Blue Knight</h1>
    <p class="auth-subtitle">AdDU Alumni Portal</p>

    <div class="input-group">
      <label class="label">Alumni ID or Email</label>
      <input class="input" type="text" placeholder="Enter your ID or email" />
    </div>

    <div class="input-group">
      <label class="label">Password</label>
      <div class="input-wrap">
        <input class="input with-icon" type="password" placeholder="Enter your password" />
        <svg class="input-icon" viewBox="0 0 24 24" fill="none">
          <path d="M2 12s4-6 10-6 10 6 10 6-4 6-10 6-10-6-10-6z" stroke="currentColor" stroke-width="1.6" />
          <circle cx="12" cy="12" r="3" stroke="currentColor" stroke-width="1.6" />
        </svg>
      </div>
    </div>

    <div class="center" style="margin: 4px 0 14px;">
      <NuxtLink to="/forgot-password" class="text-link">Forgot Password?</NuxtLink>
    </div>

    <NuxtLink to="/role-chooser" class="button primary">
      Login
      <svg class="icon" viewBox="0 0 24 24" fill="none">
        <path d="M5 12h14" stroke="currentColor" stroke-width="1.6" />
        <path d="M13 6l6 6-6 6" stroke="currentColor" stroke-width="1.6" />
      </svg>
    </NuxtLink>

    <div class="auth-footer">
      Don't have an account? <NuxtLink to="/signup"><strong>Sign Up</strong></NuxtLink>
    </div>

    <div class="legal">
      By logging in, you agree to the AdDU Alumni Data Privacy Policy and Terms of Service.
    </div>
  </div>
</template>
