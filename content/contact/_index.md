---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Remove the theme's automatic empty page heading */
.article-header,
.page-header {
  display: none !important;
}

/* Contact page */
.contact-page {
  width: 100%;
  max-width: 700px;
  margin: 20px 0 60px 0;
  padding: 0;
}

/* Contact title */
.contact-page-title {
  margin: 0 0 18px 0;
  padding: 0;
  color: #2f4858;
  font-size: 30px;
  font-weight: 600;
  line-height: 1.3;
}

/* Horizontal line */
.contact-line {
  width: 100%;
  height: 1px;
  margin: 0 0 30px 0;
  background-color: #dfe5e8;
}

/* Each contact item */
.contact-item {
  display: flex;
  align-items: flex-start;
  margin: 0 0 28px 0;
}

/* Contact icons */
.contact-item-icon {
  width: 26px;
  margin: 3px 18px 0 0;
  color: #58ad9b;
  font-size: 20px;
  line-height: 1;
  text-align: center;
  flex-shrink: 0;
}

/* Email */
.contact-email {
  margin: 0;
  font-size: 17px;
  line-height: 1.6;
}

.contact-email a {
  color: #4f9f90;
  text-decoration: none;
}

.contact-email a:hover {
  color: #397f73;
  text-decoration: underline;
}

/* Address */
.contact-address {
  margin: 0;
  color: #4d5b63;
  font-size: 16px;
  font-style: normal;
  line-height: 1.75;
}

/* Mobile */
@media screen and (max-width: 768px) {

  .contact-page {
    max-width: 100%;
    margin-top: 15px;
  }

  .contact-page-title {
    font-size: 27px;
  }

  .contact-line {
    margin-bottom: 25px;
  }

  .contact-item-icon {
    width: 22px;
    margin-right: 14px;
    font-size: 18px;
  }

  .contact-email {
    font-size: 16px;
  }

  .contact-address {
    font-size: 15px;
  }
}

</style>

<div class="contact-page">

  <div class="contact-page-title">Contact</div>

  <div class="contact-line"></div>

  <div class="contact-item">
    <div class="contact-item-icon">
      <i class="fas fa-envelope"></i>
    </div>

    <p class="contact-email">
      <a href="mailto:rritaz@uic.edu">rritaz@uic.edu</a>
    </p>
  </div>

  <div class="contact-item">
    <div class="contact-item-icon">
      <i class="fas fa-map-marker-alt"></i>
    </div>

    <address class="contact-address">
      Division of Epidemiology and Biostatistics<br>
      School of Public Health<br>
      University of Illinois Chicago<br>
      1603 W. Taylor Street, MC 923<br>
      Chicago, IL 60612
    </address>
  </div>

</div>
