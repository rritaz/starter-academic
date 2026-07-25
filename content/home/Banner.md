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
  width: 100% !important;
  max-width: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

#banner .row,
#banner [class*="col-"] {
  width: 100% !important;
  max-width: 100% !important;
  margin: 0 !important;
  padding: 0 !important;
}

.site-banner {
  width: calc(100% - 110px);
  max-width: 1600px;
  margin: 0 auto;
  line-height: 0;
}

.site-banner img {
  width: 100%;
  height: auto;
  display: block;
  margin: 0;
}

/* Remove the large gap below the banner */
#banner + section {
  padding-top: 20px !important;
}

/* Also reduce any bottom spacing added to the banner section */
#banner {
  padding-bottom: 0 !important;
}

@media (max-width: 768px) {
  .site-banner {
    width: calc(100% - 30px);
  }

  #banner + section {
    padding-top: 15px !important;
  }
}
</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.png" alt="Chicago skyline">
</div>
