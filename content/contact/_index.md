---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Contact page width */
.article-container,
.universal-wrapper,
.page-body {
  width: calc(100% - 60px) !important;
  max-width: 1204px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box;
}

/* Main contact section */
.contact-section {
  width: 100%;
  margin: 10px 0 50px;
}

/* Page heading */
.contact-page-heading {
  font-size: 30px;
  font-weight: 600;
  color: #2f4858;
  margin: 0 0 20px;
}

/* Two-column layout */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  align-items: stretch;
}

/* Individual cards */
.contact-card {
  background-color: #ffffff;
  border: 1px solid #e1e7ea;
  border-radius: 10px;
  padding: 25px 27px;
  box-sizing: border-box;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.05);
  display: flex;
  align-items: flex-start;
  min-width: 0;
}

/* Icons */
.contact-icon {
  color: #58ad9b;
  font-size: 25px;
  line-height: 1;
  margin-right: 18px;
  padding-top: 2px;
  flex-shrink: 0;
}

/* Card content */
.contact-card-content {
  flex: 1;
  min-width: 0;
}

/* Card titles */
.contact-card-title {
  color: #2f4858;
  font-size: 20px;
  font-weight: 600;
  line-height: 1.3;
  margin: 0 0 12px;
  padding-bottom: 10px;
  border-bottom: 1px solid #e1e7ea;
}

/* Name */
.contact-name {
  color: #2f4858;
  font-size: 18px;
  font-weight: 600;
  line-height: 1.4;
  margin: 0 0 5px;
}

/* Email */
.contact-email {
  margin: 0;
  line-height: 1.6;
}

.contact-email a {
  color: #4f9f90;
  font-size: 17px;
  font-weight: 500;
  text-decoration: none;
  overflow-wrap: anywhere;
}

.contact-email a:hover {
  color: #397c70;
  text-decoration: underline;
}

/* Address */
.contact-address {
  color: #4d5b63;
  font-style: normal;
  font-size: 16px;
  line-height: 1.7;
  margin: 0;
}

/* Tablet layout */
@media screen and (max-width: 1000px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 40px) !important;
  }
}

/* Mobile layout */
@media screen and (max-width: 768px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 30px) !important;
  }

  .contact-page-heading {
    font-size: 27px;
    margin-bottom: 18px;
  }

  .contact-grid {
    grid-template-columns: 1fr;
    gap: 18px;
  }

  .contact-card {
    padding: 22px 21px;
  }

  .contact-icon {
    font-size: 23px;
    margin-right: 15px;
  }

  .contact-card-title {
    font-size: 19px;
  }
}

</style>

<div class="contact-section">

<div class="contact-page-heading">Contact</div>

<div class="contact-grid">

<!-- University Address: left card -->
<div class="contact-card">

<div class="contact-icon">
<i class="fas fa-map-marker-alt"></i>
</div>

<div class="contact-card-content">

<div class="contact-card-title">University Address</div>

<address class="contact-address">
<strong>University of Illinois Chicago</strong><br>
School of Public Health<br>
Division of Epidemiology and Biostatistics<br>
1603 W Taylor Street<br>
Chicago, IL 60612
</address>

</div>
</div>

<!-- Email: right card -->
<div class="contact-card">

<div class="contact-icon">
<i class="fas fa-envelope"></i>
</div>

<div class="contact-card-content">

<div class="contact-card-title">Email</div>

<div class="contact-name">Rrita Zejnullahi</div>

<p class="contact-email">
<a href="mailto:rritaz@uic.edu">rritaz@uic.edu</a>
</p>

</div>
</div>

</div>

</div>
