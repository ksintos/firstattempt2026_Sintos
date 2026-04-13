<template>
  <div class="screen admin-screen">
    <div class="admin-top">
      <NuxtLink to="/admin/donations/create" class="admin-back">Back</NuxtLink>
      <div class="admin-page-title">Donation Options &amp; Review</div>
    </div>

    <div class="admin-stepper">
      <span class="done"></span>
      <span class="active"></span>
      <span></span>
    </div>

    <div class="admin-form">
      <div class="admin-subtitle">Suggested Donation Amounts</div>
      <div class="admin-pill-row">
        <div class="admin-pill active">PHP 500</div>
        <div class="admin-pill">PHP 1,000</div>
        <div class="admin-pill">PHP 5,000</div>
      </div>

      <div class="admin-subtitle" style="margin-top: 12px;">Custom Amount</div>
      <input class="input" type="text" placeholder="PHP 0.00" />

      <div class="admin-toggle-card">
        <div>
          <div style="font-weight: 700;">Enable monthly donations</div>
          <div class="admin-help">Donors can choose to give automatically every month</div>
        </div>
        <div class="admin-toggle"></div>
      </div>

      <div class="admin-subtitle">Campaign Preview</div>
      <div class="admin-preview">
        <div class="admin-tag active">SCHOLARSHIP</div>
        <div class="admin-preview-image">Campaign Image</div>
        <div class="admin-preview-title">Scholarship Fund for Batch 2024</div>
        <div class="admin-help">Providing educational support for underprivileged and deserving students from the Davao region.</div>
      </div>

      <button class="button admin-primary" style="margin-top: 14px;">Publish Campaign</button>
      <NuxtLink to="/admin/donations/create" class="button admin-secondary" style="margin-top: 10px;">Edit / Back</NuxtLink>
    </div>

    <AdminNav />
  </div>
</template>
