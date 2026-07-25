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

/* Remove spacing around banner */
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

/* Banner container */
.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  height: 180px;          /* Reduce or increase this if desired */
  margin: 0 auto;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  line-height: 0;
}

/* Banner image */
.site-banner img {
  width: 100%;
  height: auto;
  display: block;
  transform: scale(0.90);
  transform-origin: top center;
}

/* Reduce gap before About section */
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
    height: 120px;
  }

  .site-banner img {
    transform: scale(0.95);
  }

}

</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.jpeg" alt="Chicago skyline">
</div>
