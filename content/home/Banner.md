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

/* Remove the default Wowchemy width and padding */
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

/* Match approximately the width of the navigation area */
.site-banner {
  width: calc(100% - 100px);
  max-width: 1350px;
  margin: 0 auto;
  padding: 0;
  line-height: 0;
  overflow: hidden;
}

/*
Keep the complete width of the image.
Crop only 55px from the top.
*/
.site-banner img {
  width: 100%;
  height: auto;
  display: block;
  margin-top: -55px;
  clip-path: inset(55px 0 0 0);
}

/* Remove the space created by the clipped portion */
.site-banner {
  margin-bottom: -55px;
}

/* Keep the About section close to the banner */
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
    margin-bottom: -25px;
  }

  .site-banner img {
    margin-top: -25px;
    clip-path: inset(25px 0 0 0);
  }

}

</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.jpeg" alt="Chicago skyline">
</div>
