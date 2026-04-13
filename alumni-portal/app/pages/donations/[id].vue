<template>
  <div class="screen full">
    <div style="display: flex; align-items: center; justify-content: space-between; margin-bottom: 10px;">
      <NuxtLink to="/donations" class="text-link">Back</NuxtLink>
      <button class="button light" style="width: 70px; height: 32px; padding: 0;">Share</button>
    </div>

    <div class="card" style="overflow: hidden; padding: 0;">
      <img src="/campaign-hero.svg" alt="Scholarship Fund 2024" />
      <div style="padding: 16px;">
        <div class="badge blue">Education</div>
        <h1 class="page-title" style="margin-top: 8px;">Scholarship Fund 2024</h1>
        <p class="page-subtitle">Goal: PHP 1,000,000.00</p>
      </div>
    </div>

    <div class="card" style="padding: 16px; margin-top: 14px;">
      <h3 style="margin: 0 0 8px; font-size: 14px;">The Story</h3>
      <p class="page-subtitle">
        Every year, hundreds of bright and deserving students face the risk of dropping out due to
        financial constraints. The Scholarship Fund 2024 aims to provide full tuition coverage for
        50 incoming freshmen from underprivileged backgrounds in Mindanao.
      </p>
      <p class="page-subtitle">
        Your contribution ensures that the Blue Knight spirit continues to soar, breaking cycles of
        poverty through quality Jesuit education.
      </p>
    </div>

    <div class="card" style="padding: 16px; margin-top: 12px;">
      <h3 style="margin: 0 0 8px; font-size: 14px;">Donor Impact</h3>
      <div class="list-item" style="box-shadow: none; background: #f6f9ff;">
        <div class="list-icon">QT</div>
        <div>
          <div style="font-size: 12px;">"I was a scholar once, and now it's my turn to pay it forward. AdDU gave me the foundation I needed."</div>
          <div class="page-subtitle">Class of '98 Alumni</div>
        </div>
      </div>
      <div class="list-item" style="box-shadow: none; background: #f6f9ff;">
        <div class="list-icon">HR</div>
        <div>
          <div style="font-size: 12px;">"Small acts of generosity can transform lives. I am proud to support the next generation."</div>
          <div class="page-subtitle">Anonymous Donor</div>
        </div>
      </div>
    </div>

    <NuxtLink to="/donation-checkout" class="button primary" style="margin-top: 16px;">
      Donate Now
    </NuxtLink>
  </div>
</template>
