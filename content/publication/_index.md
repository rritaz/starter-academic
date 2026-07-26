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
Keep the Publications page width unchanged.
*/
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/*
Style only the existing Publications title
to match the Contact title.
*/
.universal-wrapper.pt-3 h1,
.universal-wrapper > h1,
h1.page-title,
h1.article-title {
  font-size: 30px !important;
  font-weight: 600 !important;
  line-height: 1.3 !important;
  color: #2f4858 !important;
  margin-bottom: 20px !important;
  padding: 0 !important;
  letter-spacing: normal !important;
  text-transform: none !important;
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

  .universal-wrapper.pt-3 h1,
  .universal-wrapper > h1,
  h1.page-title,
  h1.article-title {
    font-size: 27px !important;
    margin-bottom: 18px !important;
  }

  main .form-row {
    margin-bottom: 30px !important;
  }
}

</style>
