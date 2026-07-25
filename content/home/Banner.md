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
/* Remove all spacing around the banner widget */
#banner,
#banner.home-section {
  margin: 0 !important;
  padding: 0 !important;
}

#banner .container,
#banner .container-fluid,
#banner .row,
#banner [class*="col-"] {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* Make banner span the entire browser width */
.site-banner {
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
  padding: 0;
  line-height: 0;
}

.site-banner img {
  width: 100%;
  height: auto;
  display: block;
  margin: 0;
  padding: 0;
}

/* Remove spacing above the section immediately after the banner */
#banner + section,
#banner + .home-section {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

/* Wowchemy About/Profile section */
#about,
section#about,
.home-section.wg-about,
.home-section.wg-about-avatar {
  padding-top: 20px !important;
  margin-top: 0 !important;
}

@media (max-width: 768px) {
  #about,
  section#about,
  .home-section.wg-about,
  .home-section.wg-about-avatar {
    padding-top: 15px !important;
  }
}
</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.png" alt="Chicago skyline">
</div>
