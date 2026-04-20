# SemMorph3D: Unsupervised Semantic-Aware 3D Morphing via Mesh-Guided Gaussians

<p align="center">
  <a href="https://arxiv.org/abs/2510.02034"><img src="https://img.shields.io/badge/arXiv-2510.02034-b31b1b.svg" alt="arXiv"></a>
  <a href="#"><img src="https://img.shields.io/badge/Project-Page-7c5cff.svg" alt="Project Page"></a>
  <a href="https://github.com/baiyunshu/gaussionmorphing"><img src="https://img.shields.io/badge/Code-Coming%20Soon-23d5ab.svg" alt="Code"></a>
</p>

<p align="center">
  <b>Mengtian Li</b><sup>1,4</sup>,
  <b>Yunshu Bai</b><sup>1</sup>,
  <b>Yimin Chu</b><sup>1</sup>,
  <b>Xinru Guo</b><sup>1</sup>,
  <b>Haolin Liu</b><sup>3</sup>,
  <b>Zhifeng Xie</b><sup>1,4</sup>,
  <b>Chaofeng Chen</b><sup>2,†</sup>
</p>

<p align="center">
  <sup>1</sup>Shanghai University &nbsp;·&nbsp;
  <sup>2</sup>School of Artificial Intelligence, Wuhan University &nbsp;·&nbsp;
  <sup>3</sup>Tencent &nbsp;·&nbsp;
  <sup>4</sup>Shanghai Engineering Research Center of Motion Picture Special Effects
  <br><sub>† Corresponding author</sub>
</p>

---

## 📖 Abstract

Existing 3D morphing methods struggle with maintaining geometric consistency and texture fidelity. We introduce **SemMorph3D**, a novel framework for semantic-aware 3D shape and texture morphing from multi-view images, leveraging mesh-guided 3D Gaussian Splatting (3DGS) for high-fidelity representation.

Our approach employs:

- **Mesh-guided deformation** — binds 3DGS points to mesh patches for geometric consistency
- **Semantic correspondence** — unsupervised correspondence via mesh topology
- **Dual-domain optimization** — joint geometric and texture interpolation

This integrated approach maintains both local geometric details and global semantic coherence throughout the morphing process, without requiring labeled data. Experimental results show that SemMorph3D outperforms prior 2D/3D morphing methods, with a color consistency (ΔE) reduction of **22.2%** and an EI reduction of **26.2%** on our proposed **TexMorph** benchmark.

---

## 🔗 Resources

### 🌐 Project Page

Visit our [**project page**](./index.html) for detailed information, interactive demos, and additional results.

### 💻 Code Repository

Coming soon…

---

## 📚 Citation

If you find our work useful in your research, please consider citing:

```bibtex
Citation will be available upon publication.
```

