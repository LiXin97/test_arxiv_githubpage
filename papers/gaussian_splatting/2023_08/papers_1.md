# gaussian splatting - 2023_08

## Navigation

[Home](https://lixin97.github.io/arXivRadar) / [Papers](https://lixin97.github.io/arXivRadar/papers) / [gaussian splatting](https://lixin97.github.io/arXivRadar/papers/gaussian_splatting)

- Part 1

## Papers

| **Paper** | **Date** | **Comment** |
| --- | --- | --- |
| **[3D Gaussian Splatting for Real-Time Radiance Field Rendering](http://arxiv.org/abs/2308.04079v1)**<details>Radiance Field methods have recently revolutionized novel-view synthesis of scenes captured with multiple photos or videos. However, achieving high visual quality still requires neural networks that are costly to train and render, while recent faster methods inevitably trade off speed for quality. For unbounded and complete scenes (rather than isolated objects) and 1080p resolution rendering, no current method can achieve real-time display rates. We introduce three key elements that allow us to achieve state-of-the-art visual quality while maintaining competitive training times and importantly allow high-quality real-time (>= 30 fps) novel-view synthesis at 1080p resolution. First, starting from sparse points produced during camera calibration, we represent the scene with 3D Gaussians that preserve desirable properties of continuous volumetric radiance fields for scene optimization while avoiding unnecessary computation in empty space; Second, we perform interleaved optimization/density control of the 3D Gaussians, notably optimizing anisotropic covariance to achieve an accurate representation of the scene; Third, we develop a fast visibility-aware rendering algorithm that supports anisotropic splatting and both accelerates training and allows realtime rendering. We demonstrate state-of-the-art visual quality and real-time rendering on several established datasets.</details> | 2023-08-08 | <details>https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/</details> |
