---
layout: page
title: Low-Rank Approximation 
description: Singular Value Decomposition and Canonical Polyadic Decomposition for low-rank approximations of 4-D kernel tensors.
img: assets/img/Wolves.png
importance: 2
category: class
giscus_comments: false
---

For the final project in my Numerical Linear Algebra class, my colleague Mostafa Sedky and I tested two decomposition techniques to accelerate the inference time of the Enhanced Super Resolution Generative Adversarial Network {% cite wang2018esrgan %}. Inference times improved on the order of 1% for the CP-Decomposition and 3% for the SVD. "image to column" was also implemented to make use of BLAS3 GEMM operations, but significantly increased inference time due to memory overhead. Our final report is available upon request. The code was developed in Python with the PyTorch and Tensorly libraries. 


<div style="display: flex; justify-content: space-between;">
  <div style="flex: 1; text-align: center; margin-right: 10px;">
    <img src="../../assets/img/Wolves.png" alt="Wolves Image" style="max-width: 100%; height: auto;">
    <p style="text-align: center; margin-top: 5px;">Left: Comparison of enhanced resolutions with the original image.</p>
  </div>
  <div style="flex: 1; text-align: center; margin-left: 10px;">
    <img src="../../assets/img/BarGraph221.png" alt="Bar Graph" style="max-width: 100%; height: auto;">
    <p style="text-align: center; margin-top: 5px;">Right: Bar graph showing the performance metrics.</p>
  </div>
</div>
