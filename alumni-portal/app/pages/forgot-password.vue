<template>
  <div class="screen">
    <NuxtLink to="/login" class="text-link">Back to Login</NuxtLink>

    <div class="card flat" style="padding: 18px; margin-top: 14px;">
      <div class="center" style="margin-bottom: 10px;">
        <div class="badge blue">Reset</div>
      </div>
      <h1 class="page-title center">Forgot Password?</h1>
      <p class="page-subtitle center">Select a method to verify your identity and recover your account access.</p>

      <div class="split-pill" style="margin: 12px 0 18px;">
        <button class="active">Email Address</button>
        <button>Student ID</button>
      </div>

      <div class="input-group">
        <label class="label">School Email Address</label>
        <input class="input" type="email" placeholder="e.g. student@university.edu.ph" />
        <p class="page-subtitle" style="margin-top: 6px;">We'll send a password reset link to this address.</p>
      </div>

      <NuxtLink to="/login" class="button primary">Continue</NuxtLink>

      <div class="center" style="margin-top: 16px;">
        <span class="page-subtitle">Can't access your email or don't know your ID?</span>
        <div style="margin-top: 8px;">
          <NuxtLink to="/login" class="text-link">Contact Support</NuxtLink>
        </div>
      </div>
    </div>

    <div class="legal">(c) 2026 AdDU alumni. All rights reserved.</div>
  </div>
</template>
