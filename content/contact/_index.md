---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Keep the contact page aligned with the rest of the website */
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/* Contact page section */
.contact-section {
  width: 100%;
  margin: 25px 0 60px;
}

/* Single contact card */
.contact-card {
  width: 100%;
  max-width: 850px;
  margin: 0 auto;
  padding: 55px 65px 45px;
  background-color: #ffffff;
  border: 1px solid #e1e7ea;
  border-radius: 10px;
  box-shadow: 0 3px 14px rgba(0, 0, 0, 0.05);
  box-sizing: border-box;
}

/* Name */
.contact-name {
  color: #222222;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 42px;
  font-weight: 400;
  line-height: 1.2;
  margin: 0 0 14px;
}

/* Academic title */
.contact-position {
  color: #59646a;
  font-size: 15px;
  font-weight: 500;
  line-height: 1.5;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin: 0;
}

/* Dividing lines */
.contact-divider {
  width: 100%;
  height: 1px;
  margin: 30px 0;
  background-color: #e1e7ea;
}

/* University information */
.contact-affiliation {
  color: #303b41;
  font-size: 18px;
  line-height: 1.65;
  margin: 0;
}

/* Individual contact rows */
.contact-row {
  display: flex;
  align-items: flex-start;
  margin-bottom: 28px;
}

/* Do not add extra space after the final row */
.contact-row:last-child {
  margin-bottom: 0;
}

/* Icons */
.contact-icon {
  width: 30px;
  margin-right: 20px;
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

/* Mailing-address heading */
.contact-label {
  color: #59646a;
  font-size: 16px;
  font-weight: 500;
  margin: 0 0 6px;
}

/* Mailing address */
.contact-address {
  color: #303b41;
  font-size: 17px;
  font-style: normal;
  line-height: 1.65;
  margin: 0;
}

/* Social links */
.contact-socials {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 0;
  flex-wrap: wrap;
}

.contact-social-link {
  display: inline-flex;
  align-items: center;
  color: #303b41;
  font-size: 16px;
  font-weight: 500;
  text-decoration: none;
  padding-right: 25px;
  margin-right: 25px;
  border-right: 1px solid #dfe5e8;
}

.contact-social-link:last-child {
  padding-right: 0;
  margin-right: 0;
  border-right: none;
}

.contact-social-link i {
  color: #58ad9b;
  font-size: 20px;
  margin-right: 9px;
}

.contact-social-link:hover {
  color: #3f8f81;
  text-decoration: none;
}

/* Tablet layout */
@media screen and (max-width: 1000px) {

  main .container,
  main .universal-wrapper {
    width: calc(100% - 40px) !important;
  }

  .contact-card {
    max-width: 760px;
    padding: 48px 50px 40px;
  }
}

/* Mobile layout */
@media screen and (max-width: 768px) {

  main .container,
  main .universal-wrapper {
    width: calc(100% - 30px) !important;
  }

  .contact-section {
    margin-top: 15px;
  }

  .contact-card {
    padding: 35px 27px 30px;
  }

  .contact-name {
    font-size: 34px;
  }

  .contact-position {
    font-size: 13px;
    letter-spacing: 1.4px;
  }

  .contact-divider {
    margin: 25px 0;
  }

  .contact-affiliation {
    font-size: 17px;
  }

  .contact-icon {
    width: 25px;
    margin-right: 15px;
    font-size: 20px;
  }

  .contact-address,
  .contact-email a {
    font-size: 16px;
  }

  .contact-socials {
    align-items: flex-start;
    flex-direction: column;
    gap: 15px;
  }

  .contact-social-link {
    padding-right: 0;
    margin-right: 0;
    border-right: none;
  }
}

</style>

<div class="contact-section">

  <div class="contact-card">

    <!-- Name and position -->
    <div class="contact-name">
      Rrita Zejnullahi
    </div>

    <p class="contact-position">
      Clinical Assistant Professor of Biostatistics
    </p>

    <div class="contact-divider"></div>

    <!-- University affiliation -->
    <p class="contact-affiliation">
      University of Illinois Chicago<br>
      School of Public Health
    </p>

    <div class="contact-divider"></div>

    <!-- Email -->
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

    <!-- Mailing address -->
    <div class="contact-row">

      <div class="contact-icon">
        <i class="fas fa-map-marker-alt"></i>
      </div>

      <div class="contact-content">

        <div class="contact-label">
          Mailing Address
        </div>

        <address class="contact-address">
          University of Illinois Chicago<br>
          School of Public Health<br>
          Division of Epidemiology and Biostatistics<br>
          1603 W. Taylor Street<br>
          Chicago, IL 60612
        </address>

      </div>

    </div>

    <!-- Social links -->
    <div class="contact-divider"></div>

    <div class="contact-socials">

      <a class="contact-social-link"
         href="YOUR-GOOGLE-SCHOLAR-LINK"
         target="_blank"
         rel="noopener">
        <i class="fas fa-graduation-cap"></i>
        Google Scholar
      </a>

      <a class="contact-social-link"
         href="YOUR-LINKEDIN-LINK"
         target="_blank"
         rel="noopener">
        <i class="fab fa-linkedin"></i>
        LinkedIn
      </a>

      <a class="contact-social-link"
         href="YOUR-GITHUB-LINK"
         target="_blank"
         rel="noopener">
        <i class="fab fa-github"></i>
        GitHub
      </a>

    </div>

  </div>

</div>
