---
layout: single
author_profile: true
permalink: /
hidden: true
header:
  overlay_image: /assets/images/lili-kovac-JonGFaeFPgg-unsplash.jpg    
---

I'm an AI Fellow at the [Kempner Institute](https://kempnerinstitute.harvard.edu/) at Harvard University. Previously, I earned an S.M. in Data Science at Harvard, advised by [Prof. Yogesh Rathi](https://dms.hms.harvard.edu/people/yogesh-rathi) and [Prof. Todd Zickler](https://zickler.seas.harvard.edu/), and dual B.S. degrees in Computer Science and Data Science from UW–Madison, advised by [Prof. Vikas Singh](https://www.biostat.wisc.edu/~vsingh/).

My research focuses on building robust vision systems that reason about the 3D structure and physics of the world, with applications in medical imaging and robotics.

I have also served as a Teaching Fellow for multiple courses at Harvard and UW-Madison; see [teaching](../_pages/teach.md).

### Projects

<!-- Stereo Shape Priors -->
<div style="margin-bottom:28px;">
  <h4 style="margin-top:0;">Do Deep Stereo Models Learn Shape Priors?</h4>
  <p><strong>Linbo Tang</strong>, Aneel Damaraju, Todd Zickler<br>
  <em>NeurIPS 2026 Workshop on Physical World Models</em></p>
  <p><a href="/">arXiv</a> / <a href="https://github.com/LINBOTANG123/HDIT-Stereo">code</a></p>
</div>

<!-- MRI Denoising -->
<div style="display:flex; align-items:flex-start; gap:20px; margin-bottom:28px;">
  <div style="flex:0 0 220px;">
    <img src="/assets/images/Siemens_image_all.png" width="220" style="border-radius:10px;">
  </div>
  <div style="flex:1;">
    <h4 style="margin-top:0;">Scanner-Adaptive Coil-Level Denoising for Diffusion MRI Using Explicit Noise Priors</h4>
    <p><strong>Linbo Tang</strong>, Qiang Liu, Lipeng Ning, Yogesh Rathi<br>
    <em>ISBI 2026 (Oral)</em></p>
    <p>Developed a scanner-adaptive, coil-level denoising framework that conditions on measured noise statistics for robust performance across scanners and protocols. The method achieved up to a <strong>23% reduction in residual noise</strong> compared to the next best-performing approach on in-vivo multi-coil diffusion MRI data.</p>
    <p><a href="/">project page</a> / <a href="/">arXiv</a> / <a href="https://github.com/linbotang/MRI-Denoising">code</a></p>
  </div>
</div>

<!-- ContextMRI -->
<div style="display:flex; align-items:flex-start; gap:20px; margin-bottom:28px;">
  <div style="flex:0 0 220px;">
    <img src="/assets/images/metadata_matters.png" width="220" style="border-radius:10px;">
  </div>
  <div style="flex:1;">
    <h4 style="margin-top:0;">Metadata Matters: Diffusion-Based MRI Reconstruction with Metadata Conditioning</h4>
    <p>Developed a diffusion-based MRI reconstruction framework that leverages fine-grained metadata embeddings to adapt reconstruction across diverse acquisition settings. Designed a structured embedding architecture and introduced an out-of-distribution training strategy using cardiac MRI data to enhance generalization and interpretability on the fastMRI brain dataset.</p>
    <p><em>Research in progress</em></p>
  </div>
</div>

<!-- Emotion & Multimodal Understanding -->
<div style="margin-bottom:8px;">
  <h4 style="margin-top:0;">Large-Scale Selfie Video Dataset (L-SVD): A Benchmark for Emotion Recognition</h4>
  <p>Curating and releasing a large-scale video dataset for facial emotion recognition and exploring text–image compositionality for structured perception and reasoning.</p>
  <p><em>Dataset release</em><br>
  <a href="https://github.com/PeiranLi0930/EmoVideoNet">github page</a></p>
</div>

