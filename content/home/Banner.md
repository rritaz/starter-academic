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

#banner,
#banner.home-section,
.home-section.wg-blank {
  margin: 0 !important;
  padding: 0 !important;
}

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

.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  margin: 0 auto;
  padding: 0;
  line-height: 0;
  height: auto !important;
  overflow: visible !important;
}

.site-banner img {
  width: 100% !important;
  max-width: 100% !important;
  height: auto !important;
  object-fit: contain !important;
  object-position: center !important;
  margin: 0 !important;
  clip-path: none !important;
  transform: none !important;
  display: block;
}

#about,
section#about,
.home-section.wg-about,
.home-section.wg-about-avatar {
  margin-top: 0 !important;
  padding-top: 8px !important;
}

@media (max-width: 768px) {
  .site-banner {
    width: calc(100% - 30px);
  }
}

</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide-cropped.jpeg" alt="Chicago skyline">
</div>
