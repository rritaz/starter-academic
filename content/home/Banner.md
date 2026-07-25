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
.home-section.wg-blank {
  padding: 0 !important;
  margin: 0 !important;
}

/* Remove Wowchemy container constraints */
.home-section.wg-blank .container,
.home-section.wg-blank .container-fluid,
.home-section.wg-blank .row,
.home-section.wg-blank [class*="col-"] {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* Banner */
.site-banner{
    width:100%;
    text-align:center;
    line-height:0;
    margin:0;
    padding:0;
}

/* IMPORTANT: do NOT set a fixed height */
.site-banner img{
    width:100%;
    height:auto;
    display:block;
    margin:0 auto;
}
</style>

<div class="site-banner">
    <img src="/media/headers/bubbles-wide.jpeg" alt="Chicago skyline">
</div>
