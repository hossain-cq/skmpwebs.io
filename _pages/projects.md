---
layout: default
title: Projects | Hossain Quantum Research
permalink: /projects/
---

<section class="section">
  <div class="section-head">
    <h2>Selected projects</h2>
    <p>
      Representative systems and tools illustrating my approach to
      integrating first-principles simulation, machine learning,
      and quantum algorithms into reproducible research pipelines.
    </p>
  </div>

  <div class="grid">
    {% for project in site.projects %}
      {{ project.content }}
    {% endfor %}
  </div>
</section>


