<template>
  <div class="screen">
    <div style="display: flex; align-items: center; gap: 10px;">
      <NuxtLink to="/donations/scholarship-fund-2024" class="text-link">Back</NuxtLink>
      <h1 class="page-title" style="margin: 0;">Secure Checkout</h1>
    </div>

    <div class="card" style="padding: 14px; margin-top: 16px; display: flex; gap: 12px; align-items: center;">
      <img src="/campaign-hero.svg" alt="Scholarship Fund 2024" style="width: 56px; height: 56px; border-radius: 12px;" />
      <div>
        <div style="font-weight: 700;">Scholarship Fund 2024</div>
        <div class="page-subtitle">Campaign Donation</div>
      </div>
    </div>

    <div class="section-title">SELECT AMOUNT</div>
    <div class="amount-row">
      <div class="amount-chip">PHP 500</div>
      <div class="amount-chip active">PHP 1,000</div>
      <div class="amount-chip">PHP 5,000</div>
    </div>
    <div class="amount-chip" style="margin-top: 10px; text-align: left; padding-left: 14px;">Custom Amount</div>

    <div class="section-title">EMAIL RECEIPT</div>
    <input class="input" type="email" placeholder="Email Address" />
    <div class="page-subtitle" style="margin-top: 6px;">Required for your digital donation receipt.</div>

    <div class="section-title">DONATE ANONYMOUSLY</div>
    <div style="display: flex; align-items: center; justify-content: space-between;">
      <div>
        <div style="font-weight: 600;">Donate Anonymously</div>
        <div class="page-subtitle">Your name won't be shown publicly.</div>
      </div>
      <div class="toggle"></div>
    </div>

    <div class="section-title">PAYMENT METHOD</div>
    <div class="payment-option active">
      <div class="list-icon">G</div>
      <div style="font-weight: 700;">GCash</div>
      <span style="margin-left: auto;">●</span>
    </div>
    <div class="payment-option">
      <div class="list-icon">M</div>
      <div style="font-weight: 700;">Maya</div>
      <span style="margin-left: auto;">○</span>
    </div>
    <div class="payment-option">
      <div class="list-icon">CC</div>
      <div style="font-weight: 700;">Credit / Debit Card</div>
      <span style="margin-left: auto;">○</span>
    </div>

    <button class="button primary" style="margin-top: 16px;">Proceed to Pay</button>
  </div>
</template>
