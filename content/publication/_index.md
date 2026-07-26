---
title: ""

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
Align only the main Publications page with the navigation.
This does not change the navigation bar itself.
*/
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/* Publications title: matches the Contact page title */
.publications-page-heading {
  font-size: 30px;
  font-weight: 600;
  line-height: 1.3;
  color: #2f4858;
  margin: 0 0 20px;
}

/*
Keep the search and filter controls properly separated
from the publication entries.
*/
main .form-row {
  margin-bottom: 38px !important;
}

/* Medium screens */
@media screen and (max-width: 1000px) {
  main .container,
  main .universal-wrapper {
    width: calc(100% - 40px) !important;
  }
}

/* Mobile screens */
@media screen and (max-width: 768px) {
  main .container,
  main .universal-wrapper {
    width: calc(100% - 30px) !important;
  }

  .publications-page-heading {
    font-size: 27px;
    margin-bottom: 18px;
  }

  main .form-row {
    margin-bottom: 30px !important;
  }
}

</style>

<div class="publications-page-heading">Publications</div>
