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

/* Remove Wowchemy container restrictions */
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

/* Banner width */
.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  margin: 0 auto;
  padding: 0;
  line-height: 0;
}

/* Crop 169px from the top and 26px from the bottom */
.site-banner img {
  width: 100% !important;
  max-width: 100% !important;
  height: auto !important;
  display: block;
  padding: 0 !important;

  clip-path: inset(169px 0 26px 0) !important;
  margin-top: -169px !important;
  margin-bottom: -26px !important;

  object-fit: contain !important;
  object-position: center !important;
  transform: none !important;
}

/* Reduce the space before the About section */
#about,
section#about,
.home-section.wg-about,
.home-section.wg-about-avatar {
  margin-top: 0 !important;
  padding-top: 8px !important;
}

/* Mobile */
@media (max-width: 768px) {

  .site-banner {
    width: calc(100% - 30px);
  }

  .site-banner img {
    clip-path: inset(84px 0 13px 0) !important;
    margin-top: -84px !important;
    margin-bottom: -13px !important;
  }

}

</style>

<div class="site-banner">
  <img src="/media/headers/069F1DA0-FEDF-4D42-A750-67C45D83A3B6.png" alt="Chicago skyline">
</div>
