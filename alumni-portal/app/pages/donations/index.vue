<template>
  <div class="screen">
    <div class="top-gradient" style="border-radius: 20px;">
      <div style="font-size: 16px; font-weight: 700;">Giving &amp; Impact</div>
      <div style="font-size: 12px; opacity: 0.9;">Empowering the next generation of Ateneans.</div>
    </div>

    <div style="display: flex; justify-content: space-between; align-items: center; margin: 16px 0 8px;">
      <div style="font-weight: 700; font-size: 14px;">Featured Campaigns</div>
      <span class="text-link">Slide to view</span>
    </div>

    <div class="card" style="overflow: hidden; padding: 0;">
      <img src="/campaign-hero.svg" alt="Scholarship Fund" />
      <div style="padding: 14px;">
        <div style="font-weight: 700;">Scholarship Fund 2024</div>
        <div class="page-subtitle">75% Funded - 975k / PHP 1M</div>
        <NuxtLink to="/donations/scholarship-fund-2024" class="button light" style="margin-top: 8px;">View Campaign</NuxtLink>
      </div>
    </div>

    <div style="margin-top: 16px; font-weight: 700; font-size: 14px;">Recent Donation Drives</div>
    <div class="card" style="padding: 14px; margin-top: 10px;">
      <div style="font-weight: 700;">Calamity Relief: Davao</div>
      <div class="page-subtitle">Urgent support for flood victims</div>
      <div class="amount-row" style="margin: 10px 0;">
        <div class="amount-chip">PHP 500</div>
        <div class="amount-chip active">PHP 1000</div>
        <div class="amount-chip">PHP 2000</div>
      </div>
      <NuxtLink to="/donation-checkout" class="button primary">Donate</NuxtLink>
    </div>

    <div class="card" style="padding: 14px; margin-top: 14px;">
      <div style="font-weight: 700;">My Donation History</div>
      <div class="stats-grid" style="margin: 10px 0 0;">
        <div class="stat-card">
          <div style="font-size: 10px; color: var(--slate-500);">TOTAL CONTRIBUTED</div>
          <h5>PHP 5,000</h5>
        </div>
        <div class="stat-card">
          <div style="font-size: 10px; color: var(--slate-500);">CAMPAIGNS SUPPORTED</div>
          <h5>3</h5>
        </div>
      </div>
      <NuxtLink to="/donation-history" class="text-link" style="display: inline-block; margin-top: 10px;">
        View Full History >
      </NuxtLink>
    </div>

    <BottomNav />
  </div>
</template>
