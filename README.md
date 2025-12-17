## Project Overview

This repository contains experiments and visualizations for a 3D reconstruction
project based on Gaussian Splatting. In addition to quantitative evaluation,
we provide animated qualitative comparisons to better illustrate differences
in Gaussian density, training convergence, and view coverage.

- 📄 Report: `report/`
- 📓 Notebooks: `notebooks/`
- 🎞️ Animated visualizations: `media/gifs/`

---

### 🎞️ Animated Qualitative Comparisons
#### Scene 00000 — GT ↔ Reconstruction Toggle

| Configuration | Animation |
|--------------|-----------|
| run_3000 | ![](media/gifs/run_3000_toggle_GT_native_00000.gif) |
| run_10000 | ![](media/gifs/run_10000_toggle_GT_native_00000.gif) |
| run_20000 | ![](media/gifs/run_20000_toggle_GT_native_00000.gif) |
| run_30000 | ![](media/gifs/run_30000_toggle_GT_native_00000.gif) |
| run_40000 | ![](media/gifs/run_40000_toggle_GT_native_00000.gif) |
| run_densify_10k | ![](media/gifs/run_densify_10k_toggle_GT_native_00000.gif) |
| run_densify_full | ![](media/gifs/run_densify_full_toggle_GT_native_00000.gif) |
| run_few_gaussians | ![](media/gifs/run_few_gaussians_toggle_GT_native_00000.gif) |
| run_many_gaussians | ![](media/gifs/run_many_gaussians_toggle_GT_native_00000.gif) |
| run_fewviews_30000 | ![](media/gifs/run_fewviews_30000_toggle_GT_native_00000.gif) |
| run_r2_30000 | ![](media/gifs/run_r2_30000_toggle_GT_native_00000.gif) |
| run_r8_30000 | ![](media/gifs/run_r8_30000_toggle_GT_native_00000.gif) |


#### 🎞️ Scene 00019 — GT ↔ Reconstruction Toggle

| Configuration | Animation |
|--------------|-----------|
| run_3000 | ![](media/gifs/run_3000_toggle_GT_native_00019.gif) |
| run_10000 | ![](media/gifs/run_10000_toggle_GT_native_00019.gif) |
| run_20000 | ![](media/gifs/run_20000_toggle_GT_native_00019.gif) |
| run_30000 | ![](media/gifs/run_30000_toggle_GT_native_00019.gif) |
| run_40000 | ![](media/gifs/run_40000_toggle_GT_native_00019.gif) |
| run_densify_10k | ![](media/gifs/run_densify_10k_toggle_GT_native_00019.gif) |
| run_densify_full | ![](media/gifs/run_densify_full_toggle_GT_native_00019.gif) |
| run_few_gaussians | ![](media/gifs/run_few_gaussians_toggle_GT_native_00019.gif) |
| run_many_gaussians | ![](media/gifs/run_many_gaussians_toggle_GT_native_00019.gif) |
| run_fewviews_30000 | ![](media/gifs/run_fewviews_30000_toggle_GT_native_00019.gif) |
| run_r2_30000 | ![](media/gifs/run_r2_30000_toggle_GT_native_00019.gif) |
| run_r8_30000 | ![](media/gifs/run_r8_30000_toggle_GT_native_00019.gif) |


The animations toggle between the ground-truth image and the reconstructed view
for the same camera pose. They highlight differences in texture sharpness,
surface stability, and view-dependent effects across training duration,
densification strategies, resolution, and camera coverage.
