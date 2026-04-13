<template>
  <div class="screen">
    <div style="display: flex; align-items: center; gap: 10px;">
      <NuxtLink to="/donations" class="text-link">Back</NuxtLink>
      <h1 class="page-title" style="margin: 0;">Donation History</h1>
    </div>

    <div class="card" style="padding: 16px; margin-top: 16px;">
      <div style="font-weight: 700;">Giving Summary</div>
      <div style="display: flex; gap: 18px; margin-top: 10px;">
        <div>
          <div style="font-size: 12px; color: var(--slate-500);">Total Donated</div>
          <div style="font-weight: 700; font-size: 18px;">PHP 12,500</div>
        </div>
        <div>
          <div style="font-size: 12px; color: var(--slate-500);">Campaigns Supported</div>
          <div style="font-weight: 700; font-size: 18px;">8</div>
        </div>
      </div>
      <div class="chart">
        <span style="height: 22px;"></span>
        <span style="height: 36px;"></span>
        <span style="height: 28px;"></span>
        <span style="height: 52px;" class="active"></span>
        <span style="height: 66px;" class="active"></span>
        <span style="height: 48px;" class="active"></span>
        <span style="height: 60px;" class="active"></span>
        <span style="height: 78px;" class="active"></span>
      </div>
      <div style="display: flex; justify-content: space-between; font-size: 10px; color: var(--slate-400);">
        <span>JAN</span><span>JUN</span><span>DEC</span>
      </div>
    </div>

    <div style="margin-top: 16px; font-weight: 700;">Recent Transactions</div>
    <div class="list-item">
      <div class="list-icon">SF</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Scholarship Fund</div>
        <div class="page-subtitle">Oct 24, 2024 · GCash</div>
      </div>
      <div style="font-weight: 700;">PHP 2,500</div>
    </div>
    <div class="list-item">
      <div class="list-icon">CR</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Calamity Relief</div>
        <div class="page-subtitle">Sep 12, 2024 · Maya</div>
      </div>
      <div style="font-weight: 700;">PHP 1,500</div>
    </div>
    <div class="list-item">
      <div class="list-icon">CH</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Chapel Renovation</div>
        <div class="page-subtitle">Aug 05, 2024 · Visa</div>
      </div>
      <div style="font-weight: 700;">PHP 5,000</div>
    </div>

    <div style="margin-top: 16px; font-weight: 700;">Your Impact</div>
    <div class="list-item" style="justify-content: space-between;">
      <div style="text-align: center;">
        <div style="font-size: 18px; font-weight: 700;">5</div>
        <div style="font-size: 11px; font-weight: 700;">Supported Campaigns</div>
      </div>
      <div style="text-align: center; opacity: 0.6;">
        <div style="font-size: 18px; font-weight: 700;">100k</div>
        <div style="font-size: 11px; font-weight: 700;">PHP Milestone</div>
      </div>
      <div style="text-align: center; opacity: 0.4;">
        <div style="font-size: 18px; font-weight: 700;">M</div>
        <div style="font-size: 11px; font-weight: 700;">Monthly Donor</div>
      </div>
    </div>

    <BottomNav />
  </div>
</template>
