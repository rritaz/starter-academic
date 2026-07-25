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

/* Banner width and visible cropped area */
.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  height: 300px;
  margin: 0 auto;
  padding: 0;
  line-height: 0;
  overflow: hidden;
}

/* Keep the same image but move it upward */
.site-banner img {
  width: 100% !important;
  max-width: 100% !important;
  height: auto !important;
  display: block;
  margin: -110px 0 0 0 !important;
  padding: 0 !important;
  transform: none !important;
  clip-path: none !important;
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
    height: 190px;
  }

  .site-banner img {
    margin-top: -45px !important;
  }
}

</style>

<div class="site-banner">
  <img src="/media/headers/069F1DA0-FEDF-4D42-A750-67C45D83A3B6.png" alt="Chicago skyline">
</div>
