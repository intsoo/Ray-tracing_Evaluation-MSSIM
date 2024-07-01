# RayTracing_MSSIM
<p> This project explores the application of quantization to the traditional FP32 arithmetic operations used in Ray Tracing algorithms. By reducing the precision of mantissa and exponent bits, we experimented with various levels of reduced precision. To evaluate the quality of images rendered with these reduced precision levels, we used the Mean Structural Similarity Index Measure (M-SSIM) to compare the original image with the quantized image. While SSIM is a metric for measuring the similarity between two images, M-SSIM is a variation that offers improved accuracy. This repository includes the source code and documentation for the experimental resources used in our evaluation. </p>

-----
# REFERENCES
* https://medium.com/srm-mic/all-about-structural-similarity-index-ssim-theory-code-in-pytorch-6551b455541e
