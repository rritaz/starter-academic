---
# Display name
title: Rrita Zejnullahi

# Username
authors:
  - admin

# Primary user
superuser: true

# Role/position
role: Clinical Assistant Professor of Biostatistics

# Organization
organizations:
  - name: University of Illinois Chicago

# Social and academic links
social:
  - icon: envelope
    icon_pack: fas
    link: "mailto:rritaz@uic.edu"

  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.com/citations?user=1DLY2Z8AAAAJ&hl=en

  - icon: github
    icon_pack: fab
    link: https://github.com/rritaz

  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/rrita-zejnullahi-79307b21b/

  - icon: cv
    icon_pack: ai
    link: /files/cv.pdf

# Email
email: "rritaz@uic.edu"

# Organizational groups
user_groups:
  - Researchers
  - Visitors
---

I am a Clinical Assistant Professor of Biostatistics at the University of Illinois Chicago, with appointments in the [School of Public Health, Division of Epidemiology and Biostatistics](https://publichealth.uic.edu/profiles/zejnullahi-rrita/) (primary), the [College of Applied Health Sciences](https://ahs.uic.edu/profiles/zejnullahi-rrita/) (joint), and a Statistician in the [Office of Research](https://ahs.uic.edu/inside-ahs/office-of-research/), College of Applied Health Sciences.

I develop and apply statistical methods to support evidence-based policy and decision-making in public health and social policy. This includes

- extensions of meta-analysis methods to small sample situations,
- the formulation of effect sizes and effect-size estimators for randomized and quasi-experiments when adjusting for covariates, and
- the development and application of statistical methods to support refugee populations.

To date, I have worked on a range of substantive areas, including

- human rights statistics,
- sports epidemiology,
- mobility improvement among older adults and people with neurological disorders,
- lifestyle interventions that promote mental health, and
- the physiological mechanisms governing skeletal muscle blood flow during physical activity.

<style>
.faculty-role-link {
  color: inherit !important;
  text-decoration: none !important;
}

.faculty-role-link:hover {
  color: #58ad9b !important;
  text-decoration: underline !important;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const roleHeadings = document.querySelectorAll(".portrait-title h3");

  roleHeadings.forEach(function (heading) {
    if (heading.textContent.trim() === "Clinical Assistant Professor of Biostatistics") {
      const link = document.createElement("a");

      link.href = "https://publichealth.uic.edu/profiles/zejnullahi-rrita/";
      link.target = "_blank";
      link.rel = "noopener";
      link.className = "faculty-role-link";
      link.textContent = "Clinical Assistant Professor of Biostatistics";

      heading.textContent = "";
      heading.appendChild(link);
    }
  });
});
</script>
