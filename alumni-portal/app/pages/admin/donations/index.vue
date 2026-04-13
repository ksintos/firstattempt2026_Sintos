<template>
  <div class="screen admin-screen">
    <div class="admin-hero small">
      <div style="display: flex; align-items: center; justify-content: space-between;">
        <div>
          <div class="admin-eyebrow">WELCOME, ADMIN!</div>
          <div class="admin-name">Manon Bannerman</div>
        </div>
        <div class="admin-search">SR</div>
      </div>
      <NuxtLink to="/admin/donations/create" class="button admin-primary" style="margin-top: 12px;">
        + Create Donation
      </NuxtLink>
    </div>

    <div class="admin-section">
      <div class="admin-section-header">
        <div>Current Donation Campaigns</div>
        <NuxtLink to="/admin/donations" class="admin-link">See all</NuxtLink>
      </div>

      <div class="admin-campaign">
        <div class="admin-campaign-thumb">IMG</div>
        <div class="admin-campaign-body">
          <div class="admin-tag active">ACTIVE</div>
          <div class="admin-campaign-title">Scholarship Fund 2024</div>
          <div class="admin-campaign-meta">PHP 45,000 / PHP 60,000</div>
          <div class="admin-progress"><span style="width: 75%;"></span></div>
        </div>
        <div class="admin-campaign-more">...</div>
      </div>

      <div class="admin-campaign">
        <div class="admin-campaign-thumb">IMG</div>
        <div class="admin-campaign-body">
          <div class="admin-tag warn">ENDING SOON</div>
          <div class="admin-campaign-title">Library Renovation Project</div>
          <div class="admin-campaign-meta">PHP 91,000 / PHP 120,000</div>
          <div class="admin-progress"><span style="width: 92%;"></span></div>
        </div>
        <div class="admin-campaign-more">...</div>
      </div>

      <div class="admin-campaign">
        <div class="admin-campaign-thumb">IMG</div>
        <div class="admin-campaign-body">
          <div class="admin-tag active">ACTIVE</div>
          <div class="admin-campaign-title">Grand Alumni Homecoming</div>
          <div class="admin-campaign-meta">PHP 25,000 / PHP 100,000</div>
          <div class="admin-progress"><span style="width: 25%;"></span></div>
        </div>
        <div class="admin-campaign-more">...</div>
      </div>

      <div class="admin-campaign">
        <div class="admin-campaign-thumb">IMG</div>
        <div class="admin-campaign-body">
          <div class="admin-tag paused">PAUSED</div>
          <div class="admin-campaign-title">Annual Health and Medical Mission</div>
          <div class="admin-campaign-meta">PHP 5,000 / PHP 20,000</div>
          <div class="admin-progress"><span style="width: 25%;"></span></div>
        </div>
        <div class="admin-campaign-more">...</div>
      </div>
    </div>

    <AdminNav />
  </div>
</template>
