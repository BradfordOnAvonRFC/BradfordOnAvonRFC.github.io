---
title: Fixtures
layout: collection
permalink: /fixtures/
entries_layout: grid
classes: wide
---
<style>
.grid-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between; /* Adjust as needed */
}

.grid-item {
  flex: 0 1 calc(30% - 10px); /* Adjust width and margin */
  margin-bottom: 10px; /* Adjust margin between items */
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  padding: 10px;
}

.grid-item:last-child {
  margin-right: 0; /* Remove margin on the last item to prevent overflow */
}
</style>
The pitch plan, rules and fixture lists for all age groups are provided below:
## Pitch Plan
<div class="map-container">
    <!-- Replace the src attribute with the URL of your map image -->
    <img src="/assets/images/maps/pitchplan_dry_v1.png" alt="Pitch Plan" width=930>
</div>

### Rules
All games will be played in accordance to RFU rules and can be found <a href="https://www.englandrugby.com/participation/coaching/age-grade-rugby" target="_blank">here</a>

## Fixtures
Fixture lists are currently being finalised and will be available soon
{% assign fixtures = site.data.fixtures %}

<div class="grid-container">
  {% assign fixtures = site.data.fixtures %}
  {% for fixture in fixtures %}
    <div class="grid-item">
      <h2>{{ fixture.name }}</h2>
      <p><a href="{{ fixture.fixture_plan_pdf }}" target="_blank" class="btn btn--primary" onclick="return false;">{{ fixture.text }}</a></p>
    </div>
  {% endfor %}
</div>