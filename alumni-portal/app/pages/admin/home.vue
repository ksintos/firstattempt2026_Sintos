<template>
  <div class="screen admin-screen">
    <div class="admin-hero">
      <div style="display: flex; justify-content: space-between; align-items: center; gap: 12px;">
        <div style="display: flex; align-items: center; gap: 12px;">
          <img src="/avatar.svg" alt="Admin avatar" class="admin-avatar" />
          <div>
            <div class="admin-eyebrow">WELCOME, ADMIN!</div>
            <div class="admin-name">Manon Bannerman</div>
          </div>
        </div>
        <NuxtLink to="/login" class="admin-link">LOG OUT</NuxtLink>
      </div>
      <NuxtLink to="/admin/donations/create" class="button admin-primary" style="margin-top: 14px;">
        Create Donation
      </NuxtLink>
    </div>

    <div class="admin-stats">
      <div class="admin-stat">
        <div class="admin-stat-label">TOTAL FUNDS RAISED</div>
        <div class="admin-stat-value">PHP 12,500.00</div>
      </div>
      <div class="admin-stat">
        <div class="admin-stat-label">SCHOLAR SUPPORTED</div>
        <div class="admin-stat-value">400 Students</div>
      </div>
      <div class="admin-stat">
        <div class="admin-stat-label">ACTIVE CAMPAIGNS</div>
        <div class="admin-progress">
          <span style="width: 75%;"></span>
        </div>
        <div class="admin-stat-note">75%</div>
      </div>
      <NuxtLink to="/admin/batch-rankings" class="admin-stat admin-link-card">
        <div class="admin-stat-label">BATCH RANKING</div>
        <div class="admin-stat-value">#3 Top Class</div>
      </NuxtLink>
    </div>

    <div style="display: flex; align-items: center; justify-content: space-between; margin: 18px 0 10px;">
      <h3 style="margin: 0; font-size: 14px; color: #ffffff;">Latest News</h3>
      <NuxtLink to="/admin/donations" class="admin-link">See all</NuxtLink>
    </div>

    <div class="admin-news-grid">
      <div class="admin-news-card">
        <div class="admin-news-date">OCT 24, 2024</div>
        <div class="admin-news-title">Grand Alumni Homecoming 2024</div>
      </div>
      <div class="admin-news-card">
        <div class="admin-news-date">OCT 12, 2024</div>
        <div class="admin-news-title">Scholarship Goal</div>
      </div>
    </div>

    <AdminNav />
  </div>
</template>
