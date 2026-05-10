# Results

## Quantitative Performance (Mean DSC)

| Model | Mean DSC | Median DSC |
|---|---|---|
| 2D U-Net | 0.9278 | — |
| Custom 3D U-Net | 0.9009 | — |
| Enhanced nnU-Net | **0.9266** | **0.9318** |
| Antonelli et al. 2022 *(benchmark)* | 0.9250 | — |

> Enhanced nnU-Net exceeded the published benchmark (0.9250)
> on constrained hardware (NVIDIA RTX 4060, 8GB VRAM).

## Visual Results
Segmentation output images and training curves will be 
added to this folder.

## Notes
- Dataset: MSD Task02 Heart (20 volumetric LGE-MRI scans)
- Metric: Dice Similarity Coefficient (DSC)
- Higher DSC = better segmentation overlap with ground truth
