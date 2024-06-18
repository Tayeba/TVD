# THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS

[Paper]()  [Project]()
### Brief
This is an official implementation of **THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS** by PyTorch.

Some of the implementation details of the paper are as follows:

- We adapted the U-Net architecture used in `Guided-Diffusion`, which gives a substantial boost to sample quality.
- We used the attention mechanism in low-resolution features (16×16) like vanilla `DDPM`.
- We encode the 𝛾 rather than 𝑡 in `Palette` and embed it with affine transformation.
- We fix the variance $𝛴__𝜃(𝑥__𝑡,𝑡)$ to a constant during the inference as described in `Palette`.

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
[Image Super-Resolution via Iterative Refinement](https://arxiv.org/pdf/2104.07636.pdf)
[https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement]()

