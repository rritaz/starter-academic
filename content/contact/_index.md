---
title: ""
date: 2023-01-01
draft: false
---

<style>
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}


.contact-section {
  width: 1000px;
  max-width: 100%;
  margin: 20px 0 60px;
}

.contact-heading {
  font-size: 34px;
  font-weight: 600;
  margin: 0 0 28px 0 !important;
}

.contact-card {
  width: 100%;
  background-color: #f4f8f8;
  border-left: 5px solid #58ad9b;
  border-radius: 8px;
  padding: 30px 38px;
  box-sizing: border-box;
  display: grid;
  grid-template-columns: 30px minmax(0, 1fr);
  column-gap: 22px;
  align-items: start;
}

.contact-icon {
  color: #58ad9b;
  font-size: 30px;
  line-height: 1;
  margin: 0 !important;
  padding: 0 !important;
}

.contact-content {
  min-width: 0;
  margin: 0 !important;
  padding: 0 !important;
}

.contact-name {
  color: #2f4858;
  font-size: 23px;
  font-weight: 600;
  line-height: 1.2;
  margin: 0 0 4px 0 !important;
  padding: 0 !important;
}

.contact-email {
  line-height: 1.4;
  margin: 0 0 10px 0 !important;
  padding: 0 !important;
}

.contact-email a {
  color: #58ad9b;
  font-size: 17px;
  font-weight: 600;
  text-decoration: none;
}

.contact-email a:hover {
  text-decoration: underline;
}

.contact-divider {
  border: 0;
  border-top: 1px solid #d8e4e3;
  margin: 10px 0 !important;
  padding: 0 !important;
}

.contact-address {
  line-height: 1.65;
  margin: 0 !important;
  padding: 0 !important;
}

.contact-card p {
  margin-top: 0 !important;
  margin-bottom: 0 !important;
}

@media screen and (max-width: 1000px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 40px) !important;
  }
}

@media screen and (max-width: 768px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 30px) !important;
  }

  .contact-section {
    width: 100%;
    margin: 10px 0 50px;
  }

  .contact-heading {
    font-size: 30px;
    margin-bottom: 22px !important;
  }

  .contact-card {
    padding: 24px 22px;
    grid-template-columns: 26px minmax(0, 1fr);
    column-gap: 16px;
  }

  .contact-icon {
    font-size: 26px;
  }

  .contact-name {
    font-size: 21px;
  }
}
</style>

<div class="contact-section">
<div class="contact-heading"></div>
<div class="contact-card">
<div class="contact-icon"><i class="fas fa-envelope"></i></div>
<div class="contact-content">
<div class="contact-name">Rrita Zejnullahi</div>
<div class="contact-email"><a href="mailto:rritaz@uic.edu">rritaz@uic.edu</a></div>
<hr class="contact-divider">
<p class="contact-address">University of Illinois Chicago<br>School of Public Health<br>Division of Epidemiology and Biostatistics<br>1603 W. Taylor Street<br>Chicago, IL 60612</p>
</div>
</div>
</div>
