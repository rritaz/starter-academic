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

.site-banner {
  width: 100vw;
  height: 180px;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
  overflow: hidden;
  line-height: 0;
}

.site-banner img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  object-position: center 72%;
  display: block;
  margin: 0;
  padding: 0;
}

#banner + section,
#banner + .home-section,
#about,
section#about,
.home-section.wg-about,
.home-section.wg-about-avatar {
  margin-top: 0 !important;
  padding-top: 20px !important;
}

@media (max-width: 768px) {
  .site-banner,
  .site-banner img {
    height: 130px;
  }

  #banner + section,
  #banner + .home-section,
  #about,
  section#about,
  .home-section.wg-about,
  .home-section.wg-about-avatar {
    padding-top: 15px !important;
  }
}
</style>

<div class="site-banner">
  <img src="/media/headers/bubbles-wide.jpeg" alt="Chicago skyline">
</div>
