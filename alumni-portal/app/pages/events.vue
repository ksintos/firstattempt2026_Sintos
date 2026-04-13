<template>
  <div class="screen">
    <div style="display: flex; align-items: center; gap: 10px;">
      <NuxtLink to="/home" class="text-link">Back</NuxtLink>
      <h1 class="page-title" style="margin: 0;">Events Calendar</h1>
    </div>

    <div class="split-pill" style="margin: 14px 0 12px;">
      <button class="active">Calendar</button>
      <button>List View</button>
    </div>

    <div class="calendar">
      <div style="display: flex; align-items: center; justify-content: space-between;">
        <div style="font-weight: 700;">October 2024</div>
        <div style="display: flex; gap: 6px;">
          <button class="button light" style="width: 28px; height: 28px; padding: 0;">&lt;</button>
          <button class="button light" style="width: 28px; height: 28px; padding: 0;">&gt;</button>
        </div>
      </div>
      <div class="calendar-grid" style="margin-top: 12px; font-weight: 600;">
        <div>Sun</div><div>Mon</div><div>Tue</div><div>Wed</div><div>Thu</div><div>Fri</div><div>Sat</div>
        <div style="opacity: 0.4;">29</div><div style="opacity: 0.4;">30</div><div>1</div><div>2</div><div>3</div><div>4</div><div>5</div>
        <div>6</div><div>7</div><div class="active">8</div><div>9</div><div>10</div><div>11</div><div>12</div>
        <div>13</div><div>14</div><div>15</div><div>16</div><div>17</div><div>18</div><div>19</div>
        <div>20</div><div>21</div><div>22</div><div>23</div><div>24</div><div>25</div><div>26</div>
        <div>27</div><div>28</div><div>29</div><div>30</div><div>31</div><div style="opacity: 0.4;">1</div><div style="opacity: 0.4;">2</div>
      </div>
    </div>

    <div style="display: flex; align-items: center; justify-content: space-between; margin: 16px 0 8px;">
      <h3 style="margin: 0; font-size: 14px;">Upcoming This Week</h3>
      <NuxtLink to="/events" class="text-link">View All</NuxtLink>
    </div>

    <div class="list-item">
      <div class="list-icon">OCT 08</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Blue Knights Reach Out</div>
        <div class="page-subtitle">Reach Out program for Barangay...</div>
      </div>
      <button class="button light" style="width: 70px;">RSVP</button>
    </div>

    <div class="list-item">
      <div class="list-icon">OCT 11</div>
      <div>
        <div style="font-weight: 700; font-size: 13px;">Davao River Cleanup</div>
        <div class="page-subtitle">Community service outreach at...</div>
      </div>
      <button class="button light" style="width: 70px;">View</button>
    </div>

    <BottomNav />
  </div>
</template>
