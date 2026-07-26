---
title: "Publications"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

header:
  caption: ""
  image: ""
---

<style>

/*
Align the complete Publications page with the navigation bar.
The navigation content is approximately 1500px wide.
*/
.universal-wrapper {
  width: 100% !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
  box-sizing: border-box !important;
}

/*
Reset the publication list rules from the previous code.
This prevents publications from overlapping the filters.
*/
#container-publications {
  position: static !important;
  left: auto !important;
  right: auto !important;
  transform: none !important;
  width: 100% !important;
  max-width: 100% !important;
  margin: 40px 0 0 0 !important;
  padding: 0 !important;
  box-sizing: border-box !important;
  clear: both !important;
}

/* Each publication uses the full aligned width */
#container-publications .pub-list-item {
  position: static !important;
  width: 100% !important;
  max-width: 100% !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
  box-sizing: border-box !important;
}

/* Keep the search and filter row above the publications */
.pub-filters {
  position: static !important;
  width: 100% !important;
  margin-bottom: 35px !important;
  clear: both !important;
}

/* Tablet */
@media screen and (max-width: 1540px) {
  .universal-wrapper {
    width: calc(100% - 60px) !important;
  }
}

/* Smaller screens */
@media screen and (max-width: 1000px) {
  .universal-wrapper {
    width: calc(100% - 40px) !important;
  }
}

/* Mobile */
@media screen and (max-width: 768px) {
  .universal-wrapper {
    width: calc(100% - 30px) !important;
  }

  #container-publications {
    margin-top: 30px !important;
  }
}

</style>
