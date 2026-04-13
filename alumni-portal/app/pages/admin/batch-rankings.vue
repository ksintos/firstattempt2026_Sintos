<template>
  <div class="screen admin-screen">
    <div class="admin-top">
      <NuxtLink to="/admin/home" class="admin-back">Back</NuxtLink>
      <div class="admin-page-title">Batch Leaderboard</div>
      <div class="admin-info">i</div>
    </div>

    <div class="admin-tabs">
      <span class="active">Global Rank</span>
      <span>Your Batch</span>
      <span>Recent Activity</span>
    </div>

    <div class="admin-podium">
      <div class="admin-podium-card">
        <div class="admin-podium-rank">2</div>
        <div class="admin-podium-meta">78% Participation</div>
      </div>
      <div class="admin-podium-card highlight">
        <div class="admin-podium-rank">1</div>
        <div class="admin-podium-meta">$42.5K Raised</div>
      </div>
      <div class="admin-podium-card">
        <div class="admin-podium-rank">3</div>
        <div class="admin-podium-meta">72% Goal</div>
      </div>
    </div>

    <div class="admin-section">
      <div class="admin-section-header">
        <div>All Batch Rankings</div>
        <div class="admin-link">Filter by Year</div>
      </div>

      <div class="admin-rank-row">
        <div>
          <div class="admin-rank-title">Class of 2005</div>
          <div class="admin-rank-meta">64% Participation - PHP 28,900</div>
        </div>
        <div class="admin-rank-action">Cheer</div>
      </div>
      <div class="admin-rank-row">
        <div>
          <div class="admin-rank-title">Class of 1998</div>
          <div class="admin-rank-meta">58% Participation - PHP 24,200</div>
        </div>
        <div class="admin-rank-action">Cheer</div>
      </div>
      <div class="admin-rank-row highlight">
        <div>
          <div class="admin-rank-title">Class of 2018</div>
          <div class="admin-rank-meta">52% Participation - PHP 18,500</div>
        </div>
        <div class="admin-rank-action">Invite</div>
      </div>
      <div class="admin-rank-row">
        <div>
          <div class="admin-rank-title">Class of 2021</div>
          <div class="admin-rank-meta">45% Participation - PHP 12,100</div>
        </div>
        <div class="admin-rank-action">Cheer</div>
      </div>
    </div>

    <div class="admin-summary">
      <div>
        <div class="admin-summary-label">TOTAL ALUMNI RAISED</div>
        <div class="admin-summary-value">PHP 1.2M+</div>
      </div>
      <div>
        <div class="admin-summary-label">ACTIVE BATCHES</div>
        <div class="admin-summary-value">42 Classes</div>
      </div>
    </div>

    <AdminNav />
  </div>
</template>
