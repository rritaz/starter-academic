---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Match the width of the Publications and Contact pages */
main .container,
main .universal-wrapper {
  width: calc(100% - 60px) !important;
  max-width: 1500px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box !important;
}

/* Hide any automatic theme-generated page heading */
.article-header,
.page-header {
  display: none !important;
}

/* Manual page title matching Contact and Publications */
.teaching-page-heading {
  margin: 20px 0 30px !important;
  padding: 0 !important;
  color: #2f4858;
  font-size: 30px;
  font-weight: 600;
  line-height: 1.25;
}

/* Teaching areas box */
.teaching-areas-box {
  width: 100%;
  max-width: 100%;
  margin: 0 0 42px;
  padding: 24px 36px;
  box-sizing: border-box;
  display: flex;
  align-items: flex-start;
  overflow: visible;
  background-color: #f4f8f8;
  border-left: 5px solid #58ad9b;
  border-radius: 8px;
}

.teaching-areas-content {
  flex: 1;
  min-width: 0;
}

.teaching-areas-icon {
  flex-shrink: 0;
  margin-right: 18px;
  padding-top: 3px;
  color: #58ad9b;
  font-size: 30px;
  line-height: 1;
}

.teaching-areas-title {
  margin: 0 0 20px;
  padding: 0 0 12px;
  border-bottom: 1px solid #d8e4e3;
  color: #2f4858;
  font-size: 21px;
  font-weight: 600;
  line-height: 1.3;
}

.teaching-grid {
  display: grid;
  grid-template-columns: 210px minmax(0, 1fr);
  column-gap: 28px;
  row-gap: 18px;
  align-items: start;
  width: 100%;
  min-width: 0;
}

.teaching-label {
  color: #2f4858;
  font-weight: 600;
  line-height: 1.7;
}

.teaching-value {
  min-width: 0;
  line-height: 1.7;
  overflow-wrap: normal;
  word-break: normal;
}

/* Courses section */
.courses-heading {
  margin: 42px 0 14px;
  padding: 0 0 12px;
  border-bottom: 1px solid #d8e4e3;
  color: #2f4858;
  font-size: 24px;
  font-weight: 600;
  line-height: 1.3;
}

.university-heading {
  margin: 0 0 6px;
  color: #2f4858;
  font-size: 24px;
  font-weight: 600;
  line-height: 1.35;
}

.college-heading {
  margin: 8px 0 18px;
  color: #2f4858;
  font-size: 21px;
  font-weight: 600;
  line-height: 1.35;
}

.course-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin-bottom: 42px;
}

.course-grid-single {
  display: grid;
  grid-template-columns: minmax(0, 1fr);
  gap: 22px;
  margin-bottom: 42px;
}

.course-card {
  height: 100%;
  padding: 23px 24px;
  box-sizing: border-box;
  background-color: #ffffff;
  border: 1px solid #e1e7ea;
  border-radius: 10px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.course-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.course-code {
  margin-bottom: 5px;
  color: #58ad9b;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 0.03em;
}

.course-title {
  margin-bottom: 8px;
  color: #2f4858;
  font-size: 19px;
  font-weight: 600;
  line-height: 1.35;
}

.course-semester {
  margin-bottom: 14px;
  color: #687780;
  font-size: 14px;
  font-weight: 500;
  line-height: 1.4;
}

.course-description {
  margin: 0;
  line-height: 1.65;
}

/* Tablet */
@media screen and (max-width: 1000px) {
  main .container,
  main .universal-wrapper {
    width: calc(100% - 40px) !important;
  }

  .teaching-grid {
    grid-template-columns: 190px minmax(0, 1fr);
    column-gap: 22px;
  }
}

/* Mobile */
@media screen and (max-width: 768px) {
  main .container,
  main .universal-wrapper {
    width: calc(100% - 30px) !important;
  }

  .teaching-page-heading {
    margin: 20px 0 26px !important;
    font-size: 27px;
  }

  .teaching-areas-box {
    width: 100%;
    max-width: 100%;
    margin: 0 0 42px;
    padding: 20px;
  }

  .teaching-areas-icon {
    margin-right: 14px;
    font-size: 26px;
  }

  .teaching-grid {
    grid-template-columns: 1fr;
    row-gap: 4px;
  }

  .teaching-label {
    margin-top: 12px;
  }

  .teaching-label:first-child {
    margin-top: 0;
  }

  .teaching-value {
    margin-bottom: 4px;
  }

  .course-grid {
    grid-template-columns: 1fr;
  }

  .university-heading {
    font-size: 22px;
  }

  .college-heading {
    font-size: 20px;
  }
}

</style>

<h1 class="teaching-page-heading">Teaching</h1>

<div class="teaching-areas-box"><div class="teaching-areas-icon"><i class="fas fa-graduation-cap"></i></div><div class="teaching-areas-content"><div class="teaching-areas-title">Teaching Areas</div><div class="teaching-grid"><div class="teaching-label">Biostatistics</div><div class="teaching-value">Descriptive &amp; inferential statistics, regression modeling, and categorical &amp; longitudinal data analysis</div><div class="teaching-label">Research Methods</div><div class="teaching-value">Design of experimental &amp; observational studies, causal inference, bias, confounding, and effect modification</div><div class="teaching-label">Statistical Computing</div><div class="teaching-value">Applied data analysis using R statistical software</div></div></div></div>

<h2 class="courses-heading">Courses</h2>

<div class="university-heading">University of Illinois Chicago</div>

<div class="college-heading">School of Public Health</div>

<div class="course-grid"><div class="course-card"><div class="course-code">BSTT 535</div><div class="course-title">Categorical Data Analysis</div><div class="course-semester">Spring 2026 | Graduate level</div><p class="course-description">Covers contingency tables, measures of association, stratified analysis, logistic regression, generalized linear models, Poisson regression, log-linear models, matched data, marginal homogeneity, and methods for ordinal outcomes.</p></div><div class="course-card"><div class="course-code">IPHS 454–455</div><div class="course-title">Quantitative Methods and Analysis I &amp; II</div><div class="course-semester">Fall 2025–Spring 2026 | Graduate level</div><p class="course-description">Two-course sequence providing a foundation in quantitative and research methods for evidence-based public health, with emphasis on study design, statistical reasoning, data analysis, and interpretation of findings.</p></div><div class="course-card"><div class="course-code">IPHS 405</div><div class="course-title">Analytic and Research Methods in Public Health, Part II</div><div class="course-semester">Spring 2025 | Graduate level</div><p class="course-description">Second course in a graduate-level sequence emphasizing the selection of appropriate statistical methods, interpretation of findings, and communication of public health research results.</p></div><div class="course-card"><div class="course-code">IPHS 402</div><div class="course-title">Analytic and Research Methods in Public Health</div><div class="course-semester">Fall 2023 and Fall 2024 | Graduate level</div><p class="course-description">Introduces students to the analytic and research methods used to carry out the core functions of evidence-based public health.</p></div></div>

<div class="college-heading">College of Applied Health Sciences</div>

<div class="course-grid-single"><div class="course-card"><div class="course-code">AHS 511–512</div><div class="course-title">Biostatistics I &amp; II</div><div class="course-semester">Fall 2023–2025; Spring 2024–2026 | Graduate level</div><p class="course-description">Two-course sequence covering biostatistical reasoning and applied data analysis. Topics include descriptive statistics, probability, statistical inference, ANOVA and ANCOVA, linear and logistic regression, clinical trial design, nonparametric and categorical methods, factor and cluster analysis, and longitudinal and repeated-measures approaches.</p></div></div>
