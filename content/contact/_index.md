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

/* Contact section */
.contact-section {
  width: 100%;
  margin: 30px 0 60px;
}

/* Left-aligned card */
.contact-card {
  width: 100%;
  max-width: 650px;
  margin-left: 0;
  margin-right: auto;
  padding: 48px 52px;
  background: #ffffff;
  border: 1px solid #e6eaec;
  border-radius: 10px;
  box-shadow: 0 3px 12px rgba(0,0,0,.05);
  box-sizing: border-box;
}

/* University */
.contact-affiliation {
  margin: 0;
  color: #2f4858;
  font-size: 18px;
  line-height: 1.7;
}

/* Divider */
.contact-divider {
  height: 1px;
  background: #e6eaec;
  margin: 28px 0;
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
  color: #58ad9b;
  font-size: 21px;
  text-align: center;
  flex-shrink: 0;
  padding-top: 3px;
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
  color: #4f9f90;
  text-decoration: none;
  font-size: 17px;
  font-weight: 500;
}

.contact-email a:hover {
  text-decoration: underline;
}

/* Address */
.contact-address {
  margin: 0;
  font-style: normal;
  color: #4d5b63;
  font-size: 16px;
  line-height: 1.75;
}

/* Tablet */
@media (max-width:1000px){

main .container,
main .universal-wrapper{
width:calc(100% - 40px)!important;
}

.contact-card{
max-width:650px;
padding:42px;
}

}

/* Mobile */
@media (max-width:768px){

main .container,
main .universal-wrapper{
width:calc(100% - 30px)!important;
}

.contact-card{
padding:32px 26px;
}

.contact-affiliation{
font-size:17px;
}

.contact-email a{
font-size:16px;
}

.contact-address{
font-size:15px;
}

.contact-divider{
margin:24px 0;
}

.contact-icon{
font-size:20px;
margin-right:15px;
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
