---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Align the page with the rest of the website */
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/* Contact section */
.contact-section {
  width: 100%;
  margin: 35px 0 60px;
}

/* Centered contact card */
.contact-card {
  width: 100%;
  max-width: 700px;
  margin: 0 auto;
  padding: 50px 60px;
  background: #ffffff;
  border: 1px solid #e5eaed;
  border-radius: 10px;
  box-shadow: 0 3px 14px rgba(0, 0, 0, 0.05);
  box-sizing: border-box;
}

/* University affiliation */
.contact-affiliation {
  margin: 0;
  color: #2f3c42;
  font-size: 18px;
  line-height: 1.7;
}

/* Divider */
.contact-divider {
  width: 100%;
  height: 1px;
  margin: 30px 0;
  background: #e5eaed;
}

/* Contact rows */
.contact-row {
  display: flex;
  align-items: flex-start;
  margin-bottom: 30px;
}

.contact-row:last-child {
  margin-bottom: 0;
}

/* Icons */
.contact-icon {
  width: 28px;
  margin-right: 22px;
  padding-top: 3px;
  color: #58ad9b;
  font-size: 22px;
  line-height: 1;
  text-align: center;
  flex-shrink: 0;
}

/* Row content */
.contact-content {
  flex: 1;
  min-width: 0;
}

/* Email */
.contact-email {
  margin: 0;
}

.contact-email a {
  color: #3f8f81;
  font-size: 18px;
  font-weight: 500;
  line-height: 1.6;
  text-decoration: none;
  overflow-wrap: anywhere;
}

.contact-email a:hover {
  color: #2f7166;
  text-decoration: underline;
}

/* Mailing address */
.contact-address {
  margin: 0;
  color: #2f3c42;
  font-size: 17px;
  font-style: normal;
  line-height: 1.75;
}

/* Tablet */
@media screen and (max-width: 1000px) {

  main .container,
  main .universal-wrapper {
    width: calc(100% - 40px) !important;
  }

  .contact-card {
    padding: 45px;
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

  .contact-card {
    padding: 35px 28px;
  }

  .contact-affiliation {
    font-size: 17px;
  }

  .contact-divider {
    margin: 25px 0;
  }

  .contact-icon {
    width: 25px;
    margin-right: 15px;
    font-size: 20px;
  }

  .contact-email a {
    font-size: 17px;
  }

  .contact-address {
    font-size: 16px;
  }
}

</style>

<div class="contact-section">

<div class="contact-card">

<p class="contact-affiliation">
University of Illinois Chicago<br>
School of Public Health
</p>

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

</div>
