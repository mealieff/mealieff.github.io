---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-pdf-container {
    width: 100%;
    height: 100vh;
    min-height: 800px;
    margin: 20px 0;
  }
  
  .cv-pdf-container iframe {
    width: 100%;
    height: 100%;
    border: none;
  }
  
  .cv-download-link {
    text-align: center;
    margin-top: 20px;
  }
</style>

<div class="cv-pdf-container">
  <iframe src="{{ base_path }}/files/Lieffers_Melissa_CV.pdf" type="application/pdf">
    <p>Your browser does not support PDFs. <a href="{{ base_path }}/files/Lieffers_Melissa_CV.pdf">Download the CV</a> instead.</p>
  </iframe>
</div>

<div class="cv-download-link">
  <a href="{{ base_path }}/files/Lieffers_Melissa_CV.pdf" class="btn btn--primary" download>Download CV as PDF</a>
</div>
