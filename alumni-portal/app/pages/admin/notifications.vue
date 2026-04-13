<template>
  <div class="screen admin-screen">
    <div class="admin-top">
      <div class="admin-page-title">Notifications</div>
      <button class="admin-pill">Mark all as read</button>
    </div>

    <div class="admin-tabs pills">
      <span class="active">All</span>
      <span>Campaigns</span>
      <span>User Reports</span>
    </div>

    <div class="admin-section">
      <div class="admin-section-title">URGENT UPDATES</div>
      <div class="admin-alert">
        <div class="admin-alert-icon">!</div>
        <div>
          <div class="admin-alert-title">System Alert: Server Maintenance</div>
          <div class="admin-alert-meta">Maintenance is scheduled for midnight (12:00 AM PST). Core donation services may be briefly unavailable.</div>
        </div>
        <div class="admin-alert-time">Scheduled</div>
      </div>

      <div class="admin-notice">
        <div class="admin-notice-icon">HP</div>
        <div>
          <div class="admin-alert-title">New Campaign Request</div>
          <div class="admin-alert-meta">Sarah Jenkins submitted 'Clean Water Initiative' for approval. Review required.</div>
        </div>
        <div class="admin-alert-time">12m ago</div>
      </div>

      <div class="admin-notice">
        <div class="admin-notice-icon">VR</div>
        <div>
          <div class="admin-alert-title">Verification Pending</div>
          <div class="admin-alert-meta">14 new donor identities are waiting for manual verification in the admin queue.</div>
        </div>
        <div class="admin-alert-time">2h ago</div>
      </div>

      <div class="admin-notice">
        <div class="admin-notice-icon">GR</div>
        <div>
          <div class="admin-alert-title">Goal Reached: Typhoon Relief</div>
          <div class="admin-alert-meta">Success! The Typhoon relief fund has reached its target of PHP 50,000. Campaign closed.</div>
        </div>
        <div class="admin-alert-time">5h ago</div>
      </div>
    </div>

    <AdminNav />
  </div>
</template>
