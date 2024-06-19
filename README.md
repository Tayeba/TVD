# THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS

[Paper]()  [Project]()
### Brief
This is an official implementation of **THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS** by PyTorch.

We list the hyperparameters, training configurations, and computational resources utilized for our TVDv1 model.

- Base channels: 256
- Optimizer: Adam (β1 = 0.9, β2 = 0.99)
- Channel multipliers: 1, 2, 4, 8
- Learning rate: 0.0003
- Blocks per resolution: 2
- Batch size: 16
- Attention resolutions: 8, 16, 32
- EMA: 0.9999
- Attention head dimension: 64
- Dropout: 0.0
- Training hardware: NVIDA RTX A6000 48GB GPU
- Training steps: 500000
- Diffusion noise schedule: cosine
- Noise schedule log SNR range: [−20, 20]
- Sampling timesteps: 1000
- Video resolution: 16x64x64
- Sampling log-variance interpolation: γ = 0.3
- Weight decay: 0.0 

### Prerequisites

### Getting Started

#### Installation

#### Data Preparation

#### Training

#### Evaluation

### Citation

If you find our work useful in your research, please cite the following:

### Contact

For questions about our paper or code, please contact ([qazitayeba@gmail.com](https://github.com/ashutosh1807)) or raise an issue on GitHub.

### Acknowledge

Our code is built upon the work of:
- [Image Super-Resolution via Iterative Refinement](https://arxiv.org/pdf/2104.07636.pdf)
- [https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement]()

