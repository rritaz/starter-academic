---
widget: blank
headless: true
active: true
weight: 1
title: ""

design:
  columns: "1"
  spacing:
    padding:
      - "0"
      - "0"
      - "0"
      - "0"
---

<style>
#banner {
  padding: 0 !important;
  margin: 0 !important;
}

#banner .container,
#banner .container-fluid {
  max-width: 100% !important;
  width: 100% !important;
  padding: 0 !important;
  margin: 0 !important;
}

#banner .row {
  margin: 0 !important;
}

#banner [class*="col-"] {
  max-width: 100% !important;
  flex: 0 0 100% !important;
  padding: 0 !important;
}

.site-banner {
  width: calc(100% - 100px);
  max-width: 1620px;
  height: 250px;
  margin: 0 auto;
  overflow: hidden;
  line-height: 0;
}

.site-banner img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;
  display: block;
  margin: 0;
}
</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.png" alt="Chicago skyline">
</div>
