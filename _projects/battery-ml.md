---
layout: default
title: Physics-informed ML for battery voltage prediction
---

<article class="card card-gradient">
  <h3>Physics-informed ML for battery voltage prediction</h3>
  <p>
    End-to-end machine-learning pipeline for predicting average voltages
    of alkali-ion battery cathode materials, combining DFT-derived
    physicochemical descriptors with neural network models.
  </p>

  <ul class="project-meta">
    <li><strong>Input:</strong> DFT-derived structural and atomic descriptors</li>
    <li><strong>Output:</strong> Voltage predictions with model interpretability</li>
    <li><strong>Audience:</strong> Battery materials researchers</li>
  </ul>

  <div class="card-footer">
    <a class="link"
       href="https://onlinelibrary.wiley.com/doi/10.1002/smtd.202502076"
       target="_blank" rel="noopener">
      Publication →
    </a>
    <span class="badge">PyTorch</span>
    <span class="badge">FCDNN</span>
    <span class="badge">Feature analysis</span>
  </div>

  <div class="project-visual" data-rotate>
    <img src="{{ '/static/projects/battery_ml/TOC_ACS_AMI_1.jpg' | relative_url }}"
         alt="Workflow diagram" class="active" loading="lazy">
    <img src="{{ '/static/projects/battery_ml/training_testing_new1_plot.jpg' | relative_url }}"
         alt="Training vs testing" loading="lazy">
    <img src="{{ '/static/projects/battery_ml/P2__O3_type_newcomposition_latest.jpg' | relative_url }}"
         alt="New compositions" loading="lazy">
  </div>
</article>
