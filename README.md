# THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS

[Paper]() [Project]()
### Brief
This is an official implementation of **THERMAL VIDEODIFF (TVD): A DIFFUSION ARCHITECTURE FOR THERMAL VIDEO SYNTHESIS ** by PyTorch.

Some of the implementation details of the paper are as follows:

- We adapted the U-Net architecture used in `Guided-Diffusion`, which gives a substantial boost to sample quality.
- We used the attention mechanism in low-resolution features (16×16) like vanilla `DDPM`.
- We encode the 𝛾 rather than 𝑡 in `Palette` and embed it with affine transformation.
- We fix the variance $𝛴__𝜃(𝑥__𝑡,𝑡)$ to a constant during the inference as described in `Palette`.

### Abstract

Machine perception gathers information about its surroundings through sophisticated sensors. Thermal sensors offer scalable perception in conditions of low visibility such as nighttime, smoke, or fog. However, integrating thermal data with deep learning algorithms is a challenge because of the scarcity of thermal data due to the high cost of thermal sensors.
In this paper, we propose for the first time, a deep learning-based framework for thermal video synthesis as an affordable alternative to purchasing costly thermal imaging devices.
Here, we have introduced a diffusion model for estimating thermal videos from videos in the visible spectrum. Results show that our Thermal VideoDiff (TVD) is capable of synthesizing high-fidelity video samples and capturing temperature variations from thermal data effectively. Our work addresses the challenge posed by the scarcity of thermal data, as well as brings deep learning to the domain of infrared video generation, enabling research and development in the infrared domain.
