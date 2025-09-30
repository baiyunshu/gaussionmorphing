# WhenGaussians Meet Geometry: Semantic-Aware Morphing of 3D Objects

## 📋 Supplementary Materials

This repository contains the supplementary materials for the paper **"WhenGaussians Meet Geometry: Semantic-Aware Morphing of 3D Objects"** submitted anonymously.

## 📖 Abstract

Existing 3D morphing methods struggle with maintaining geometric consistency and texture fidelity. We introduce GaussianMorphing, a novel framework for semantic-aware 3D shape and texture morphing from multi-view images, leveraging mesh-guided 3D Gaussian Splatting (3DGS) for high-fidelity representation.

Our approach employs:
- **Mesh-guided deformation strategy** binding 3DGS points to mesh patches for geometric consistency
- **Semantic Correspondence**: Unsupervised correspondence via mesh topology
- **Dual-Domain Optimization**: Joint geometric and texture interpolation

This integrated approach maintains both local geometric details and global semantic coherence throughout the morphing process without requiring labeled data. Experimental results show that GaussianMorphing outperforms prior 2D/3D morphing methods, with a color consistency (∆E) reduction of 22.2% and an EI reduction of 26.2% on our proposed TexMorph benchmark.


## 🔗 Resources

### 🌐 Project Page
[Visit our project page](./project_page/project_page.html) for detailed information, interactive demos, and additional results.

### 🎥 Demo Video
[Watch our demo video](./demo.mp4) showcasing GaussianMorphing in action with real 3D object morphing sequences.

### 📄 Supplementary Material
[View detailed supplementary material](./When%20Gaussians%20Meet%20Geometry%20Semantic-Aware%20Morphing%20of%203D%20Objects.pdf) including additional experiments, TexMorph benchmark details, and comprehensive results.

### 📊 TexMorph Benchmark
[Access the TexMorph benchmark dataset](./benchmark/lion) - our proposed evaluation benchmark for textured 3D morphing.

### 💻 Code Repository
[Access the full implementation](CODE_REPOSITORY_URL) 

