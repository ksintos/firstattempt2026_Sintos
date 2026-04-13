<template>
  <div class="screen admin-screen">
    <div class="admin-top">
      <NuxtLink to="/admin/donations" class="admin-back">Back</NuxtLink>
      <div class="admin-page-title">Create Campaign/Donation</div>
    </div>

    <div class="admin-stepper">
      <span class="active"></span>
      <span></span>
      <span></span>
    </div>

    <div class="admin-form">
      <label class="label">Campaign Title</label>
      <input class="input" type="text" placeholder="e.g., Scholarship Fund for Batch 2024" />
      <div class="admin-help">Make it catchy and descriptive to attract more donors.</div>

      <label class="label" style="margin-top: 14px;">Category</label>
      <div class="admin-select">Select a category</div>

      <label class="label" style="margin-top: 14px;">Full Story / Details</label>
      <textarea class="admin-textarea" rows="4" placeholder="Share why this campaign is important. Tell your story..."></textarea>

      <label class="label" style="margin-top: 14px;">Campaign Image / Banner</label>
      <div class="admin-upload">
        <div class="admin-upload-icon">UP</div>
        <div class="admin-upload-title">Upload Header Image</div>
        <div class="admin-help">JPEG, PNG or JPG (Recommended: 1200x630)</div>
      </div>

      <NuxtLink to="/admin/donations/options" class="button admin-primary" style="margin-top: 16px;">
        Next Step >
      </NuxtLink>
    </div>

    <AdminNav />
  </div>
</template>
