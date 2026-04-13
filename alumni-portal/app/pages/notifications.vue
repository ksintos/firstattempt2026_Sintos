<template>
  <div class="screen">
    <div style="display: flex; align-items: center; justify-content: space-between;">
      <h1 class="page-title" style="margin: 0;">Notifications</h1>
      <button class="button light" style="width: 120px;">Mark all as read</button>
    </div>

    <div class="split-pill" style="margin: 14px 0 8px;">
      <button class="active">All</button>
      <button>Donations</button>
      <button>Admin</button>
      <button>Events</button>
    </div>

    <div class="section-title">URGENT UPDATES</div>

    <div class="list-item" style="border-left: 4px solid #ff6b6b;">
      <div class="list-icon">!</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Emergency Fund: Typhoon Relief</div>
        <div class="page-subtitle">Immediate assistance needed for students affected by the recent flooding in Davao City.</div>
      </div>
      <span class="page-subtitle">2m ago</span>
    </div>

    <div class="list-item">
      <div class="list-icon">HP</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Campaign Milestone</div>
        <div class="page-subtitle">Scholarship Fund for 2024 has reached 90% of its funding goal. Thank you for your support!</div>
      </div>
      <span class="page-subtitle">45m ago</span>
    </div>

    <div class="list-item">
      <div class="list-icon">EV</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Homecoming Tomorrow</div>
        <div class="page-subtitle">Don't forget the Batch 2024 Grand Homecoming at Martin Hall starts at 6:00 PM.</div>
      </div>
      <span class="page-subtitle">2h ago</span>
    </div>

    <div class="list-item">
      <div class="list-icon">RP</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Transparency Report Released</div>
        <div class="page-subtitle">The Annual Alumni Financial Transparency Report for FY 2023-2024 is now available for viewing.</div>
      </div>
      <span class="page-subtitle">5h ago</span>
    </div>

    <div class="list-item">
      <div class="list-icon">OK</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Donation Processed</div>
        <div class="page-subtitle">Your donation of PHP 1,500 to the 'Books for Mindanao' drive has been successfully processed.</div>
      </div>
      <span class="page-subtitle">Yesterday</span>
    </div>

    <div class="list-item">
      <div class="list-icon">VC</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Venue Change: Networking Night</div>
        <div class="page-subtitle">The networking night has been moved to the Arrope Hall Rooftop. Same time, same date.</div>
      </div>
      <span class="page-subtitle">Yesterday</span>
    </div>

    <BottomNav />
  </div>
</template>
