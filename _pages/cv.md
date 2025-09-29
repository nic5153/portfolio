---
layout: default
title: "CV"
permalink: /cv/
---

{% capture cv_url %}{{ '/files/main.pdf' | relative_url }}{% endcapture %}

<div style="margin: 0 0 1rem 0;">
  <a class="btn btn--primary" href="{{ cv_url }}" target="_blank" rel="noopener">Download CV (PDF)</a>
</div>

<object data="{{ cv_url }}" type="application/pdf" width="100%" height="1100px">
  <iframe src="{{ cv_url }}" width="100%" height="1100px">
    <p>Your browser can’t display embedded PDFs. 
       <a href="{{ cv_url }}">Open the CV</a> instead.</p>
  </iframe>
</object>

