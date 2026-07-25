+++
widget = "blank"
headless = true
active = true
weight = 1
title = ""

[design]
columns = "1"

[design.spacing]
padding = ["0", "0", "0", "0"]
+++

<style>
/* Remove spacing around the banner section */
#banner,
#banner.home-section,
.home-section.wg-blank {
  margin: 0 !important;
  padding: 0 !important;
}

/* Allow the widget content to use the full section width */
#banner .container,
#banner .container-fluid,
#banner .row,
#banner [class*="col-"],
.home-section.wg-blank .container,
.home-section.wg-blank .container-fluid,
.home-section.wg-blank .row,
.home-section.wg-blank [class*="col-"] {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* Align banner with the site name and navigation */
.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  margin: 0 auto;
  padding: 0;
  line-height: 0;
}

/* Show the full image without cropping */
.site-banner img {
  width: 100%;
  height: auto;
  display: block;
  margin: 0;
  padding: 0;
}

/* Reduce space between banner and About section */
#about,
section#about,
.home-section.wg-about,
.home-section.wg-about-avatar {
  margin-top: 0 !important;
  padding-top: 10px !important;
}

/* Mobile layout */
@media (max-width: 768px) {
  .site-banner {
    width: calc(100% - 30px);
  }

  #about,
  section#about,
  .home-section.wg-about,
  .home-section.wg-about-avatar {
    padding-top: 10px !important;
  }
}
</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.jpeg" alt="Chicago skyline">
</div>
