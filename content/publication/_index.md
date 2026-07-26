---
title: "Publications"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image relative to the static/img folder.
header:
  caption: ""
  image: ""
---

<style>

/*
Keep the Publications heading and search/filter controls
at the theme's original width.

Only widen the publication entries below the filters.
*/
#container-publications {
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  width: calc(100vw - 60px) !important;
  max-width: 1540px !important;
  box-sizing: border-box;
}

/* Make each publication entry use the widened container */
#container-publications .pub-list-item {
  width: 100% !important;
  max-width: none !important;
  box-sizing: border-box;
}

/* Medium screens */
@media screen and (max-width: 1000px) {
  #container-publications {
    width: calc(100vw - 40px) !important;
  }
}

/* Mobile screens */
@media screen and (max-width: 768px) {
  #container-publications {
    width: calc(100vw - 30px) !important;
  }
}

</style>
