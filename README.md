## Core Architectures & Research References

This project synthesizes and visualizes findings from peer-reviewed Virtual Try-On (VTON) research. All architectural insights, performance metrics, and qualitative observations are derived from published literature and are used strictly for comparative analysis and educational visualization.

### Diffusion-Based Virtual Try-On
- **CatVTON** – *Concatenation Is All You Need for Virtual Try-On with Diffusion Models*  
  Zheng Chong, Xiao Dong, et al. (2024)  
  *Role*: Primary reference for high-fidelity diffusion-based try-on. Reported results inform the “Integrated” system status and the 1024×768 resolution benchmark used in the dashboard.

- **FITMI** – *A Realistic Virtual Try-On Solution*  
  Tassneam M. Samy, et al. (2025)  
  *Role*: Informed latent diffusion and texture-preserving strategies, particularly for fine-grained fabrics such as Indian textiles.

- **MGT** – *Extending Virtual Try-Off to Multi-Garment Scenarios*  
  Riza Velioglu, et al. (2024–2025)  
  *Role*: Provided guidance on multi-garment try-off logic and standardized product image normalization used in dataset curation analysis.

### High-Resolution & Warping Baselines
- **VITON-HD** – *High-Resolution Virtual Try-On via Misalignment-Aware Normalization*  
  Seunghwan Choi, Sunghyun Park, et al. (2021)  
  *Role*: Serves as the high-resolution (1024×768) baseline for accuracy comparison against modern diffusion-based approaches.

- **CP-VTON** – *Toward Characteristic-Preserving Image-based Virtual Try-On Network*  
  Bochao Wang, Huabin Zheng, et al. (2018)  
  *Role*: Referenced as a legacy benchmark illustrating the evolution from TPS-based warping to diffusion-driven synthesis.

- **FashionFit** – *Analysis of Mapping 3D Pose and Neural Body Fit for Custom Virtual Try-On*  
  Mohammad Farukh Hashmi, B. Kiran Kumar Ashish, et al. (2020)  
  *Role*: Contributed to the conceptual foundation for smart body-fit and 3D pose mapping, with emphasis on Indian demographic contexts.

### Technical Metrics (From Literature)
- **SSIM** – Structural Similarity Index (Wang et al., 2004)  
- **FID** – Fréchet Inception Distance (Heusel et al., 2017)  
- **Latency** – Inference targets (≈2.8–3.0s) based on reported benchmarks in CatVTON and MGT on consumer-grade GPUs

> ⚠️ This repository does not redistribute datasets, model weights, or proprietary assets. All data points are synthesized from published sources for research analysis and visualization only.
