# RayTracing_MSSIM
<p> This project explores the <b>application of quantization</b> to the traditional FP32 arithmetic operations used in <b>Ray Tracing</b> algorithms. By reducing the precision of mantissa and exponent bits, we experimented with <b>various levels of reduced precision</b>. <ins>To evaluate the quality of images rendered with these reduced precision levels, we used the <b>Mean Structural Similarity Index Measure (M-SSIM)</b> to compare the original image with the quantized image</ins>. While <b>SSIM</b> is a metric for measuring the similarity between two images, <b>M-SSIM</b> is a variation that offers improved accuracy. This repository includes the <ins>source code and documentation for the experimental resources used in our evaluation</ins>. </p>

-----
## REFERENCES
* https://medium.com/srm-mic/all-about-structural-similarity-index-ssim-theory-code-in-pytorch-6551b455541e
