Some projects from my Computational Imaging class. 

1. Compressive sensing on Audio
   We try to reconstruct the signal using only 5% of the original sound using convex minimization solvers.

2. Compressive sensing on Image
   We divide the original image into non-overlappings blocks of 8x8 pixels. For each block, we perform compressive sensing using the Discrete Cosine Transform as basis
   and measure the quality of the recovered image using Structural Similarity Index Measure (SSIM).

3. Photoactivation Localization Microscopy
   We superresolve a blurry and pixelated image by fitting 2D Gaussians on the bright spots using available multivariate normal distribution fitting routines and Expectation Maximization Gaussian Mixture Models

4. Radon transform
  We create an image of several circles with different sizes and take its Radon transform and recover the image using the inverse Radon transform.
  We compare the SSIM index of using different filter on recovered images.
