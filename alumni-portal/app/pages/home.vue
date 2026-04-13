<template>
  <div class="screen">
    <div class="top-gradient">
      <div style="display: flex; align-items: center; justify-content: space-between; gap: 12px;">
        <div>
          <div style="font-size: 11px; opacity: 0.9;">Welcome, Ateneans!</div>
          <div style="font-size: 16px; font-weight: 700;">Sophia Laforteza</div>
          <div style="font-size: 11px; opacity: 0.85;">AB Communications '24</div>
        </div>
        <img class="avatar" src="/avatar.svg" alt="Profile avatar" />
      </div>
      <NuxtLink to="/donations" class="button light" style="margin-top: 14px;">
        Donate Now
      </NuxtLink>
    </div>

    <div class="stats-grid">
      <div class="stat-card">
        <div style="font-size: 10px; color: var(--slate-500);">TOTAL DONATED</div>
        <h5>PHP 12,500.00</h5>
        <p>Blue Knight Scholars Fund</p>
      </div>
      <div class="stat-card">
        <div style="font-size: 10px; color: var(--slate-500);">SCHOLARS SUPPORTED</div>
        <h5>4 Students</h5>
        <p>Batch 2024</p>
      </div>
      <div class="stat-card">
        <div style="font-size: 10px; color: var(--slate-500);">PROGRESS ON DRIVE</div>
        <h5>75%</h5>
        <div class="progress"><span style="width: 75%;"></span></div>
      </div>
      <div class="stat-card">
        <div style="font-size: 10px; color: var(--slate-500);">BATCH RANKING</div>
        <h5>#3 Top Class</h5>
        <p>Based on total giving</p>
      </div>
    </div>

    <div style="display: flex; align-items: center; justify-content: space-between; margin: 18px 0 10px;">
      <h3 style="margin: 0; font-size: 14px;">Latest News</h3>
      <NuxtLink to="/events" class="text-link">See all</NuxtLink>
    </div>

    <div class="news-grid">
      <div class="news-card">
        <span style="font-size: 9px;">OCT 24, 2024</span>
        <h4>Grand Alumni Homecoming 2024</h4>
      </div>
      <div class="news-card" style="background: #bfe2ff;">
        <span style="font-size: 9px;">OCT 12, 2024</span>
        <h4>Scholarship Goal Update</h4>
      </div>
    </div>

    <BottomNav />
  </div>
</template>
