---
title: ""
date: 2023-01-01
draft: false
---

<style>

/* Make the Teaching page narrower */
.article-container,
.universal-wrapper,
.page-body {
  width: calc(100% - 60px) !important;
  max-width: 1280px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  box-sizing: border-box;
}

.teaching-areas-box {
  background-color: #f4f8f8;
  border-left: 5px solid #58ad9b;
  border-radius: 8px;
  padding: 24px 36px;
  margin: 10px 0 42px;
  width: 100%;
  max-width: 100%;
  box-sizing: border-box;
  display: flex;
  align-items: flex-start;
  overflow: visible;
}

.teaching-areas-box > div:last-child {
  flex: 1;
  min-width: 0;
}

.teaching-areas-icon {
  color: #58ad9b;
  font-size: 30px;
  line-height: 1;
  margin-right: 18px;
  padding-top: 3px;
  flex-shrink: 0;
}

.teaching-areas-title {
  font-size: 21px;
  font-weight: 600;
  margin-bottom: 20px;
  padding-bottom: 12px;
  border-bottom: 1px solid #d8e4e3;
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
  line-height: 1.7;
  min-width: 0;
  overflow-wrap: normal;
  word-break: normal;
}

.courses-heading {
  margin-top: 42px;
  margin-bottom: 28px;
}

.university-heading {
  font-size: 24px;
  font-weight: 600;
  margin-top: 34px;
  margin-bottom: 6px;
}

.college-heading {
  color: #2f4858;
  font-size: 21px;
  font-weight: 600;
  margin-top: 8px;
  margin-bottom: 18px;
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
  background-color: #ffffff;
  border: 1px solid #e1e7ea;
  border-radius: 10px;
  padding: 23px 24px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.05);
  height: 100%;
  box-sizing: border-box;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.course-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.course-code {
  color: #58ad9b;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 0.03em;
  margin-bottom: 5px;
}

.course-title {
  color: #2f4858;
  font-size: 19px;
  font-weight: 600;
  line-height: 1.35;
  margin-bottom: 8px;
}

.course-semester {
  color: #687780;
  font-size: 14px;
  font-weight: 500;
  margin-bottom: 14px;
}

.course-description {
  line-height: 1.65;
  margin: 0;
}

@media screen and (max-width: 1000px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 40px) !important;
  }

  .teaching-grid {
    grid-template-columns: 190px minmax(0, 1fr);
    column-gap: 22px;
  }
}

@media screen and (max-width: 768px) {
  .article-container,
  .universal-wrapper,
  .page-body {
    width: calc(100% - 30px) !important;
  }

  .course-grid {
    grid-template-columns: 1fr;
  }

  .teaching-areas-box {
    width: 100%;
    max-width: 100%;
    margin: 10px 0 42px;
    padding: 20px;
  }

  .teaching-areas-icon {
    font-size: 26px;
    margin-right: 14px;
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
}

</style>

<div class="teaching-areas-box">
<div class="teaching-areas-icon"><i class="fas fa-graduation-cap"></i></div>
<div>
<div class="teaching-areas-title">Teaching Areas</div>
<div class="teaching-grid">

<div class="teaching-label">Biostatistics</div>
<div class="teaching-value">Descriptive &amp; inferential statistics, regression modeling, and categorical &amp; longitudinal data analysis</div>

<div class="teaching-label">Research Methods</div>
<div class="teaching-value">Design of experimental &amp; observational studies, causal inference, bias, and confounding</div>

<div class="teaching-label">Statistical Computing</div>
<div class="teaching-value">Applied data analysis using R statistical software</div>

</div>
</div>
</div>

<h3 class="courses-heading">Courses</h3>

<div class="university-heading">University of Illinois Chicago</div>

<div class="college-heading">School of Public Health</div>

<div class="course-grid">

<div class="course-card">
<div class="course-code">BSTT 535</div>
<div class="course-title">Categorical Data Analysis</div>
<div class="course-semester">Spring 2026 | Graduate level</div>
<p class="course-description">Covers contingency tables, measures of association, stratified analysis, logistic regression, generalized linear models, Poisson regression, log-linear models, matched data, marginal homogeneity, and methods for ordinal outcomes.</p>
</div>

<div class="course-card">
<div class="course-code">IPHS 454–455</div>
<div class="course-title">Quantitative Methods and Analysis I &amp; II</div>
<div class="course-semester">Fall 2025–Spring 2026 | Graduate level</div>
<p class="course-description">Two-course sequence providing a foundation in quantitative and research methods for evidence-based public health, with emphasis on study design, statistical reasoning, data analysis, and interpretation of findings.</p>
</div>

<div class="course-card">
<div class="course-code">IPHS 405</div>
<div class="course-title">Analytic and Research Methods in Public Health, Part II</div>
<div class="course-semester">Spring 2025 | Graduate level</div>
<p class="course-description">Second course in a graduate-level sequence emphasizing the selection of appropriate statistical methods, interpretation of findings, and communication of public health research results.</p>
</div>

<div class="course-card">
<div class="course-code">IPHS 402</div>
<div class="course-title">Analytic and Research Methods in Public Health</div>
<div class="course-semester">Fall 2023 and Fall 2024 | Graduate level</div>
<p class="course-description">Introduces students to the analytic and research methods used to carry out the core functions of evidence-based public health.</p>
</div>

</div>

<div class="college-heading">College of Applied Health Sciences</div>

<div class="course-grid-single">

<div class="course-card">
<div class="course-code">AHS 511–512</div>
<div class="course-title">Biostatistics I &amp; II</div>
<div class="course-semester">Fall 2023–2025; Spring 2024–2026 | Graduate level</div>
<p class="course-description">Two-course sequence covering biostatistical reasoning and applied data analysis. Topics include descriptive statistics, probability, statistical inference, ANOVA and ANCOVA, linear and logistic regression, clinical trial design, nonparametric and categorical methods, factor and cluster analysis, and longitudinal and repeated-measures approaches.</p>
</div>

</div>
