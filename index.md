---
layout: default
title: Brad Huttash
---

<div class="profile" id="profile">
  <img class="profile-photo" src="{{ '/assets/img/me.jpg' | relative_url }}" alt="Your Name">
  <div class="profile-info">
    <strong>Brad Huttash</strong>
    <span>
      <a href="mailto:you@bhuttash@gmail.com" target="_blank">bhuttash@gmail.com</a> ·
      <a href="https://linkedin.com/in/bradhuttash" target="_blank">LinkedIn</a> ·
      <a href="https://github.com/bhuttash" target="_blank">GitHub</a>
    </span>
  </div>
</div>

<script>
  (function () {
    var profile = document.getElementById('profile');
    var RANGE = 200; // px of scrolling over which the animation plays
    var ticking = false;

    function update() {
      var t = Math.min(Math.max(window.scrollY / RANGE, 0), 1);
      var p = t * t * (3 - 2 * t); // smoothstep easing
      profile.style.setProperty('--p', p.toFixed(4));
      ticking = false;
    }

    window.addEventListener('scroll', function () {
      if (!ticking) {
        window.requestAnimationFrame(update);
        ticking = true;
      }
    }, { passive: true });

    update();
  })();
</script>

# Brad Huttash
#### SOFTWARE ENGINEER
Data-driven engineering professional with a proven record of automating processes, improving yields, and standardizing systems across global teams. Expert in data analysis, process optimization, and scalable solutions, with a proven record of reducing planning cycles by 50%+ and unifying global test standards.

---

#### TECHNICAL SKILLS
AWS | Python (Pandas, NumPy) | Selenium | Linux/Bash | ETL Scripting | Exensio | Excel | VBA/VB | Git | SVN | 8D | 5 Whys | Jira | Confluence | SharePoint 

---

#### EDUCATION
**Master of Science in Computer Science** \| Western Governors University - August 2026

**Bachelor of Science in Electrical Engineering** \| Boise State University

---

#### ACADEMIC PROJECTS
##### AI/ML Data Pipeline & Model Selection (Python)
Created an end-to-end data cleaning script using Pandas/NumPy/Scikit-Learn to programmatically address duplications, missing values, and feature normalization.
##### Linux System Automation (Bash)
Built scripts for user account creation/deletion/configuration and shell optimization utilizing user interaction, conditional logic, and error-handling.
##### Emerging System Design
Developed and analyzed performance of a hypothetical remote smart health monitoring system using a combination of off-the-shelf and custom components.
##### Mobile/Ubiquitous Design
Designed a mobile and web app for a hypothetical university using user personas, detailed system requirements, user workflows, and wireframes.
##### Cloud Computing
Devised and implemented an Amazon Web Services (AWS) cloud environment to host a simple Python/Flask web app using the Elastic Beanstalk Platform-as-a-Service (PaaS).
##### Software Architecture and Design
Converted and expanded a sample monolithic shopping cart into a microservices architecture with an orchestrator service coordinating between cart, inventory, and payment services using Python, FastAPI, and Docker Compose.

---

#### PROFESSIONAL EXPERIENCE
##### Onsemi, Meridian, ID
**Member Technical Staff, Test Engineering - August 2022 - June 2025**
- Led strategic projects of highly variable scope and complexity, with emphasis on targeting automation and process integration opportunities.
- Established a robust change management and automated publishing process for internal library of 45+ test standard documents.
- Aligned three business groups under a single global test process standard, reducing 65-page specification volume by 15% and enabling consistent company-wide test metrics.
- Defined and applied a project documentation process and toolset across the test organization.

**Senior Manager, Test Engineering	April 2019 - August 2022**
- Managed a global, matrixed team to deliver best-in-class test development for automotive CMOS image sensors.
- Boosted on-time New Product Development (NPD) checklist completion by 40%+ and cut missed items by ~90% by integrating the checklist into GitLab repositories and automating task creation within engineers’ daily workflow, preventing readiness-related delays.
- Improved manufacturing yield by an estimated 1%-3% by enabling re-probe testing for products with One-Time Programmable Memory (OTPM).
- Cut resource planning cycle time by over 50% through development of an automated resource allocation model.

##### Aptina, LLC, Boise, ID
**Manager, Test Engineering - August 2010 - April 2019**
- Directed TE responsibilities for 30+ new CMOS image sensor device introductions across industrial, commercial, medical, and automotive market segments. 
- Introduced consistency in device test and validation through a cross-functional initiative that produced 45+ company-wide test standards, standardized test flows, and unified terminology across teams.
- Minimized production test gaps by introducing a common test plan format and review process to align cross-functional teams during test planning.
- Instituted an NPD Test Engineering checklist to govern lifecycle deliverables and tasks, ensuring consistent execution, and serving as audit documentation for ISO 26262 / IATF 16949 compliance.
- Architected a restartable data workflow within SharePoint, reducing processing stoppages by ~95% and cutting approval times from hours to minutes.

##### Micron, Boise, ID
**Test Development Engineer**
- Worked cross-functionally with all device and hardware engineering teams to develop test plans, test software, and test hardware (wafer sort and package test) for production test and device validation of CMOS image sensors. 
- Improved test program release software, reducing wait times by over 80%.
- Enhanced engineering control features for VB/GPIB remote tester software, eliminating manual production dependencies and saving hours of combined engineering and operator time daily. 
- Investigated, identified, and resolved a major source of test inconsistency, reducing illuminator-related variation by over 60% across 25+ testers.
- Led 5 first silicon projects and supported 6 others, achieving functional silicon debug and initial sample runs within 72 hours to enable a short time to market.
