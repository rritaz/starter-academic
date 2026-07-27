---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Align page with the rest of the site */
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
  max-width: 700px;
  margin: 0 auto;
  padding: 55px 60px;
  background: #fff;
  border: 1px solid #e5eaed;
  border-radius: 10px;
  box-shadow: 0 3px 14px rgba(0,0,0,.05);
}

/* Name */
.contact-name {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 42px;
  font-weight: 400;
  color: #222;
  line-height: 1.2;
  margin: 0 0 14px;
}

/* Position */
.contact-position {
  font-size: 15px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #666;
  margin: 0;
}

/* Divider */
.contact-divider {
  height: 1px;
  background: #e5eaed;
  margin: 32px 0;
}

/* University */
.contact-affiliation {
  font-size: 18px;
  line-height: 1.7;
  color: #2f3c42;
  margin: 0;
}

/* Rows */
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
  color: #58ad9b;
  font-size: 22px;
  text-align: center;
  flex-shrink: 0;
}

/* Content */
.contact-content {
  flex: 1;
}

/* Email */
.contact-email {
  margin: 0;
}

.contact-email a {
  color: #3f8f81;
  text-decoration: none;
  font-size: 18px;
  font-weight: 500;
}

.contact-email a:hover {
  text-decoration: underline;
}

/* Address */
.contact-address {
  margin: 0;
  font-style: normal;
  font-size: 17px;
  line-height: 1.75;
  color: #2f3c42;
}

/* Tablet */
@media (max-width:1000px){

main .container,
main .universal-wrapper{
width:calc(100% - 40px)!important;
}

.contact-card{
padding:45px;
}

}

/* Mobile */
@media (max-width:768px){

main .container,
main .universal-wrapper{
width:calc(100% - 30px)!important;
}

.contact-card{
padding:35px 28px;
}

.contact-name{
font-size:34px;
}

.contact-position{
font-size:13px;
letter-spacing:1.5px;
}

.contact-affiliation{
font-size:17px;
}

.contact-address{
font-size:16px;
}

.contact-email a{
font-size:17px;
}

.contact-divider{
margin:25px 0;
}

}

</style>

<div class="contact-section">

<div class="contact-card">

<div class="contact-name">
Rrita Zejnullahi
</div>

<p class="contact-position">
Clinical Assistant Professor of Biostatistics
</p>

<div class="contact-divider"></div>

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
University of Illinois Chicago<br>
School of Public Health<br>
Division of Epidemiology and Biostatistics<br>
1603 W. Taylor Street, MC 923<br>
Chicago, IL 60612
</address>

</div>

</div>

</div>

</div>
