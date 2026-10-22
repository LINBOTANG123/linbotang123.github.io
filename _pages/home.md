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

<hr style="margin:48px 0 32px;">

### Projects

<style>
.proj { display:flex; align-items:flex-start; gap:20px; margin-bottom:28px; }
.proj .proj-img { flex:0 0 220px; }
.proj .proj-img img { width:100%; border-radius:10px; }
.proj .proj-text { flex:1; min-width:0; }
.proj .proj-text p { font-size:0.8em; line-height:1.5; margin:0 0 0.7em; text-align:left; }
.proj .proj-text h4 { font-size:0.95em; margin:0 0 0.5em; }
@media (min-width:64em) { .proj { margin-right:-2em; } }
</style>

<!-- Stereo Shape Priors -->
<div class="proj">
  <div class="proj-img">
    <img src="/assets/images/stereo.png">
  </div>
  <div class="proj-text">
    <h4>Do Deep Stereo Models Learn Shape Priors?</h4>
    <p><strong>Linbo Tang</strong>, Aneel Damaraju, Todd Zickler<br>
    <em>NeurIPS 2026 Workshop on Physical World Models</em></p>
    <p>Studied whether state-of-the-art deep stereo models produce object boundaries consistent with simple shape priors when local image and disparity cues are weak. On a synthetic stereo dataset of objects from a highly constrained shape family, existing models retain systematic boundary errors, even after finetuning or training from scratch. We introduce a simple generative stereo model that jointly predicts disparity and a distance field of object boundaries, improving boundary localization and yielding contours that better adhere to the underlying shape space.</p>
    <p><a href="/">arXiv</a> / <a href="https://github.com/LINBOTANG123/HDIT-Stereo">code</a></p>
  </div>
</div>

<!-- MRI Denoising -->
<div class="proj">
  <div class="proj-img">
    <img src="/assets/images/Siemens_image_all.png">
  </div>
  <div class="proj-text">
    <h4>Scanner-Adaptive Coil-Level Denoising for Diffusion MRI Using Explicit Noise Priors</h4>
    <p><strong>Linbo Tang</strong>, Qiang Liu, Lipeng Ning, Yogesh Rathi<br>
    <em>ISBI 2026 (Oral)</em></p>
    <p>Developed a scanner-adaptive, coil-level denoising framework that conditions on measured noise statistics for robust performance across scanners and protocols. The method achieved up to a <strong>23% reduction in residual noise</strong> compared to the next best-performing approach on in-vivo multi-coil diffusion MRI data.</p>
    <p><a href="/">project page</a> / <a href="/">arXiv</a> / <a href="https://github.com/linbotang/MRI-Denoising">code</a></p>
  </div>
</div>

<!-- ContextMRI -->
<div class="proj">
  <div class="proj-img">
    <img src="/assets/images/metadata_matters.png">
  </div>
  <div class="proj-text">
    <h4>Metadata Matters: Diffusion-Based MRI Reconstruction with Metadata Conditioning</h4>
    <p>Developed a diffusion-based MRI reconstruction framework that leverages fine-grained metadata embeddings to adapt reconstruction across diverse acquisition settings. Designed a structured embedding architecture and introduced an out-of-distribution training strategy using cardiac MRI data to enhance generalization and interpretability on the fastMRI brain dataset.</p>
    <p><em>Research in progress</em></p>
  </div>
</div>

<!-- Emotion & Multimodal Understanding -->
<div class="proj" style="margin-bottom:8px;">
  <div class="proj-text">
  <h4>Large-Scale Selfie Video Dataset (L-SVD): A Benchmark for Emotion Recognition</h4>
  <p>Curating and releasing a large-scale video dataset for facial emotion recognition and exploring text–image compositionality for structured perception and reasoning.</p>
  <p><em>Dataset release</em><br>
  <a href="https://github.com/PeiranLi0930/EmoVideoNet">github page</a></p>
  </div>
</div>

