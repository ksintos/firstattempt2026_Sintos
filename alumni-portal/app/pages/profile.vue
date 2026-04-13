<template>
  <div class="screen">
    <div class="center">
      <img src="/avatar.svg" alt="Profile avatar" style="width: 96px; height: 96px; border-radius: 50%;" />
      <h1 class="page-title">Sophia Laforteza</h1>
      <p class="page-subtitle">AB Communications, Batch 2024</p>
      <p class="page-subtitle" style="margin-top: -6px;">Ateneo de Davao University</p>
      <button class="button light" style="max-width: 260px;">Edit Profile</button>
    </div>

    <div class="section-title">ACADEMIC &amp; RECORDS</div>
    <div class="list-item">
      <div class="list-icon">TR</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Transcript of Records</div>
        <div class="page-subtitle">Official digital copy (e-TOR)</div>
      </div>
    </div>
    <div class="list-item">
      <div class="list-icon">CO</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Committees &amp; Orgs</div>
        <div class="page-subtitle">SAMAHAN, BKV (Active)</div>
      </div>
    </div>
    <div class="list-item">
      <div class="list-icon">PD</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Past Donations</div>
        <div class="page-subtitle">Blue Knight Scholars Fund</div>
      </div>
    </div>

    <div class="section-title">ACCOUNT SETTINGS</div>
    <div class="list-item">
      <div class="list-icon">AS</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">App Settings</div>
        <div class="page-subtitle">Preferences and notifications</div>
      </div>
    </div>
    <div class="list-item">
      <div class="list-icon">CP</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Change Password</div>
        <div class="page-subtitle">Update account security</div>
      </div>
    </div>
    <div class="list-item">
      <div class="list-icon">HC</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Help Center</div>
        <div class="page-subtitle">Get assistance and FAQs</div>
      </div>
    </div>
    <div class="list-item" style="border: 1px solid #ffd7d7;">
      <div class="list-icon" style="color: #d94141;">LO</div>
      <div>
        <div style="font-weight: 700; font-size: 13px; color: #d94141;">Log Out</div>
        <div class="page-subtitle">Sign out of your account</div>
      </div>
    </div>

    <BottomNav />
  </div>
</template>
