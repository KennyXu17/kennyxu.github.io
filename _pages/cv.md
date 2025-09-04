---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D., Mechanical Engineering**  
  Arizona State University, 2020 – 2024  
  GPA: 4.0 / 4.0

* **M.S., Mechanical Engineering**  
  Washington University in St. Louis, 2018 – 2020  
  GPA: 3.8 / 4.0

* **B.E., Mechanical Engineering**  
  Tianjin University, China, 2014 – 2018  
  GPA: 3.7 / 4.0

Work Experience
======
* **AI Engineer**  
  WindQuiet Technology, Inc., Mountain View, CA  
  Dec 2024 – Present  
  - Developed and deployed LLM-powered RAG systems for real-time telemetry and documentation querying  
  - Built automated ML pipelines using Docker, AWS, and GitHub Actions  
  - Integrated NLP-based transformers into microgrid control platforms

* **AI Researcher**  
  OriGen.AI, Inc., Hoboken, NJ  
  May 2024 – Aug 2024  
  - Designed GCN/CNN models for reservoir simulation  
  - Automated AI workflows for rapid deployment with Docker and AWS  
  - Built anomaly detection systems with dashboard visualizations

* **AI Researcher**  
  Prognostic Analysis & Reliability Assessment Lab, Tempe, AZ  
  Aug 2020 – May 2024  
  - Developed transformer-based models with domain-specific physics constraints  
  - Led predictive maintenance system design using CI/CD pipelines  
  - Collaborated on interdisciplinary projects with NASA, DOE, DOT

Skills
======
* **Languages**: Python, C++, SQL, R, MATLAB, Java, JavaScript, TypeScript, HTML, CSS, Assembly  
* **Frameworks**: PyTorch, TensorFlow, Hugging Face, LangChain, OpenAI API  
* **Tools**: Docker, Git, AWS, Azure, GCP, CI/CD, VSCode, OpenCV

Publications
======
<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Talks
======
<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>

Teaching
======
<ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Service and Leadership
======
* Reviewer, IEEE Transactions on Intelligent Transportation Systems  
* Research Mentor, Undergraduate Research Experience at ASU  
* Lead Developer, AI4Microgrid Open Source Project
