---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Match the width of the rest of the website */
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/* Main contact section */
.contact-section {
  width: 100%;
  max-width: 650px;
  margin: 25px 0 60px;
}

/* Page title */
.contact-title {
  margin: 0;
  color: #2f4858;
  font-size: 30px;
  font-weight: 600;
  line-height: 1.25;
}

/* Line below the title */
.contact-divider {
  width: 100%;
  height: 1px;
  margin: 22px 0 30px;
  background: #e5eaed;
}

/* Contact rows */
.contact-row {
  display: flex;
  align-items: flex-start;
  margin-bottom: 28px;
}

.contact-row:last-child {
  margin-bottom: 0;
}

/* Icons */
.contact-icon {
  width: 26px;
  margin-right: 18px;
  padding-top: 3px;
  color: #58ad9b;
  font-size: 20px;
  line-height: 1;
  text-align: center;
  flex-shrink: 0;
}

/* Text beside the icons */
.contact-content {
  flex: 1;
  min-width: 0;
}

/* Email */
.contact-email {
  margin: 0;
}

.contact-email a {
  color: #4f9f90;
  font-size: 17px;
  font-weight: 500;
  line-height: 1.6;
  text-decoration: none;
  overflow-wrap: anywhere;
}

.contact-email a:hover {
  color: #397f73;
  text-decoration: underline;
}

/* Mailing address */
.contact-address {
  margin: 0;
  color: #4d5b63;
  font-size: 16px;
  font-style: normal;
  line-height: 1.75;
}

/* Tablet */
@media screen and (max-width: 1000px) {

  main .container,
  main .universal-wrapper {
    width: calc(100% - 40px) !important;
  }
}

/* Mobile */
@media screen and (max-width: 768px) {

  main .container,
  main .universal-wrapper {
    width: calc(100% - 30px) !important;
  }

  .contact-section {
    margin-top: 20px;
  }

  .contact-title {
    font-size: 27px;
  }

  .contact-divider {
    margin: 20px 0 26px;
  }

  .contact-icon {
    width: 24px;
    margin-right: 15px;
    font-size: 19px;
  }

  .contact-email a {
    font-size: 16px;
  }

  .contact-address {
    font-size: 15px;
  }
}

</style>

<div class="contact-section">

  <h1 class="contact-title">Contact</h1>

  <div class="contact-divider"></div>

  <div class="contact-row">

    <div class="contact-icon">
      <i class="fas fa-envelope"></i>
    </div>

    <div class="contact-content">
      <p class="contact-email">
        <a href="mailto:rritaz@uic.edu">rritaz@uic.edu</a>
      </p>
    </div>

  </div>

  <div class="contact-row">

    <div class="contact-icon">
      <i class="fas fa-map-marker-alt"></i>
    </div>

    <div class="contact-content">
      <address class="contact-address">
        Division of Epidemiology and Biostatistics<br>
        School of Public Health<br>
        University of Illinois Chicago<br>
        1603 W. Taylor Street, MC 923<br>
        Chicago, IL 60612
      </address>
    </div>

  </div>

</div>
