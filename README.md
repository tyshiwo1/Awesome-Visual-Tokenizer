# Awesome-Visual-Tokenizer

**Categorize by Autoencoder Architecture:**
- [Image Autoencoders](#image-autoencoders)
  - [Continuous 2D CNN Image Autoencoder](#continuous-2d-cnn-image-autoencoder)
  - [Discrete 2D CNN Image Autoencoder](#discrete-2d-cnn-image-autoencoder)
  - [2D Transformer Image Autoencoder](#2d-transformer-image-autoencoder)
  - [1D Image Autoencoder](#1d-image-autoencoder)
  - [Image Autoencoder with Generative Decoder](#image-autoencoder-with-generative-decoder)
- [Video Autoencoders](#video-autoencoders)
  - [Continuous 3D CNN Video Autoencoder](#continuous-3d-cnn-video-autoencoder)
  - [Discrete 3D CNN Video Autoencoder](#discrete-3d-cnn-video-autoencoder)
  - [3D Transformer Video Autoencoder](#3d-transformer-video-autoencoder)
  - [1D Video Autoencoder](#1d-video-autoencoder)
  - [Video Autoencoder with Generative Decoder](#video-autoencoder-with-generative-decoder)

## Image Autoencoders

### Continuous 2D CNN Image Autoencoder
- **Diagnosing and enhancing VAE models**
  - Dai, B., Wipf, D. et al.
  - [arXiv:1903.05789](https://arxiv.org/abs/1903.05789)
  - 2019

- **Deep compression autoencoder for efficient high-resolution diffusion models**
  - Chen, J., Cai, H., Chen, J. et al. 
  - [arXiv:2410.10733](https://arxiv.org/abs/2410.10733)
  - 2024

- **DC-AE 1.5: Accelerating Diffusion Model Convergence with Structured Latent Space**
  - Chen, J., Zou, D., He, W. et al. 
  - [arXiv:2508.00413](https://arxiv.org/abs/2508.00413)
  - 2025


### Discrete 2D CNN Image Autoencoder


- **Taming transformers for high-resolution image synthesis**
  - Esser, P., Rombach, R., Ommer, B. et al. 
  - [**CVPR 2021**](https://arxiv.org/abs/2012.09841)
  - 2021

- **Autoregressive image generation using residual quantization**
  - Lee, D., Kim, C., Kim, S. et al.
  - [**CVPR 2022**](https://arxiv.org/abs/2203.01941)
  - 2022

- **Finite scalar quantization: Vq-vae made simple**
  - Mentzer, F., Minnen, D., Agustsson, E. et al.
  - [arXiv:2309.15505](https://arxiv.org/abs/2309.15505)
  - 2023

- **Language Model Beats Diffusion--Tokenizer is Key to Visual Generation**
  - Yu, L., Lezama, J., Gundavarapu, N.B. et al. 
  - [arXiv:2310.05737](https://arxiv.org/abs/2310.05737)
  - 2023

- **Magvit: Masked generative video transformer**
  - Yu, L., Cheng, Y., Sohn, K. et al.
  - [**CVPR 2023**](https://arxiv.org/abs/2212.05199)
  - 2023

- **Emu3: Next-Token Prediction is All You Need**
  - BAAI, E.T.
  - [arXiv:2409.18869](https://arxiv.org/abs/2409.18869)
  - 2024

- **Visual autoregressive modeling: Scalable image generation via next-scale prediction**
  - Tian, K., Jiang, Y., Yuan, Z. et al.
  - [arXiv:2404.02905](https://arxiv.org/abs/2404.02905)
  - 2024

- **Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation**
  - Sun, P., Jiang, Y., Chen, S. et al.
  - [arXiv:2406.06525](https://arxiv.org/abs/2406.06525)
  - 2024

- **Open-magvit2: An open-source project toward democratizing auto-regressive visual generation**
  - Luo, Z., Shi, F., Ge, Y. et al. 
  - [arXiv:2409.04410](https://arxiv.org/abs/2409.04410)
  - 2024

- **Quantize-then-Rectify: Efficient VQ-VAE Training**
  - Zhang, B., Rao, Q., Zheng, W. et al.
  - [arXiv:2507.10547](https://arxiv.org/abs/2507.10547)
  - 2025

- **Image and video tokenization with binary spherical quantization**
  - Zhao, Y., Xiong, Y., Kr"ahenb"uhl, P. et al.
  - [arXiv:2406.07548](https://arxiv.org/abs/2406.07548)
  - 2024

- **End-to-end vision tokenizer tuning**
  - Wang, W., Zhang, F., Cui, Y. et al. 
  - [arXiv:2505.10562](https://arxiv.org/abs/2505.10562)
  - 2025



### 2D Transformer Image Autoencoder

- **Vision Foundation Models as Effective Visual Tokenizers for Autoregressive Image Generation**
  - Zheng, A., Wen, X., Zhang, X. et al. 
  - [arXiv:2507.08441](https://arxiv.org/abs/2507.08441)
  - 2025

- **Learnings from scaling visual tokenizers for reconstruction and generation**
  - Hansen-Estruch, P., Yan, D., Chung, C. et al.
  - [arXiv:2501.09755](https://arxiv.org/abs/2501.09755)
  - 2025

- **MANZANO: A Simple and Scalable Unified Multimodal Model with a Hybrid Vision Tokenizer**
  - Li, Y., Qian, R., Pan, B. et al.
  - [arXiv:2509.16197](https://arxiv.org/abs/2509.16197)
  - 2025

- **Unitok: A unified tokenizer for visual generation and understanding**
  - Ma, C., Jiang, Y., Wu, J. et al. 
  - [arXiv:2502.20321](https://arxiv.org/abs/2502.20321)
  - 2025

- **UniLiP: Adapting CLIP for Unified Multimodal Understanding, Generation and Editing**
  - Tang, H., Xie, C., Bao, X. et al.
  - [arXiv:2507.23278](https://arxiv.org/abs/2507.23278)
  - 2025

- **Gigatok: Scaling visual tokenizers to 3 billion parameters for autoregressive image generation**
  - Xiong, T., Liew, J.H., Huang, Z. et al.
  - [**ICCV 2025**](https://arxiv.org/abs/2504.08736)
  - 2025

- **Latent Diffusion Model without Variational Autoencoder**
  - Shi, M., Wang, H., Zheng, W. et al. 
  - [arXiv:2510.15301](https://arxiv.org/abs/2510.15301)
  - 2025

- **Diffusion Transformers with Representation Autoencoders**
  - Zheng, B., Ma, N., Tong, S. et al. 
  - [arXiv:2510.11690](https://arxiv.org/abs/2510.11690)
  - 2025

- **Aligning Visual Foundation Encoders to Tokenizers for Diffusion Models**
  - Chen, B., Bi, S., Tan, H. et al.
  - [arXiv:2509.25162](https://arxiv.org/abs/2509.25162)
  - 2025


### 1D Image Autoencoder

- **An image is worth 32 tokens for reconstruction and generation**
  - Yu, Q., Weber, M., Deng, X. et al.
  - [arXiv:2406.07550](https://arxiv.org/html/2406.07550v1)
  - 2024

- **Elastictok: Adaptive tokenization for image and video**
  - Yan, W., Mnih, V., Faust, A. et al.
  - [arXiv:2410.08368](https://arxiv.org/abs/2410.08368)
  - 2024

- **Latent Denoising Makes Good Visual Tokenizers**
  - Yang, J., Li, T., Fan, L. et al.
  - [arXiv:2507.15856](https://arxiv.org/abs/2507.15856)
  - 2025

- **Language-guided image tokenization for generation**
  - Zha, K., Yu, L., Fathi, A. et al.
  - [**CVPR 2025**](https://arxiv.org/abs/2412.05796)
  - 2025

- **Highly Compressed Tokenizer Can Generate Without Training**
  - Beyer, L.L., Li, T., Chen, X. et al.
  - [arXiv:2506.08257](https://arxiv.org/abs/2506.08257)
  - 2025

- **Masked autoencoders are effective tokenizers for diffusion models**
  - Chen, H., Han, Y., Chen, F. et al.
  - [**ICML 2025**](https://arxiv.org/abs/2502.03444)
  - 2025

- **Softvq-vae: Efficient 1-dimensional continuous tokenizer**
  - Chen, H., Wang, Z., Li, X. et al.
  - [**CVPR 2025**](https://arxiv.org/abs/2412.10958)
  - 2025

- **Adaptive length image tokenization via recurrent allocation**
  - Duggal, S., Isola, P., Torralba, A. et al.
  - [**First Workshop on Scalable Optimization for Efficient and Adaptive Foundation Models**](https://arxiv.org/abs/2411.02393)
  - 2024

- **Democratizing text-to-image masked generative models with compact text-aware one-dimensional tokens**
  - Kim, D., He, J., Yu, Q. et al.
  - [arXiv:2501.07730](https://arxiv.org/abs/2501.07730)
  - 2025

- **FlexTok: Resampling Images into 1D Token Sequences of Flexible Length**
  - Bachmann, R., Allardice, J., Mizrahi, D. et al.
  - [**ICML 2025**](https://arxiv.org/abs/2502.13967)
  - 2025

- **Gigatok: Scaling visual tokenizers to 3 billion parameters for autoregressive image generation**
  - Xiong, T., Liew, J.H., Huang, Z. et al.
  - [**ICCV 2025**](https://arxiv.org/abs/2504.08736)
  - 2025

- **DetailFlow: 1D Coarse-to-Fine Autoregressive Image Generation via Next-Detail Prediction**
  - Liu, Y., Qu, L., Zhang, H. et al.
  - [arXiv:2505.21473](https://arxiv.org/abs/2505.21473)
  - 2025

- **One-d-piece: Image tokenizer meets quality-controllable compression**
  - Miwa, K., Sasaki, K., Arai, H. et al.
  - [arXiv:2501.10064](https://arxiv.org/abs/2501.10064)
  - 2025

- **Image Tokenizer Needs Post-Training**
  - Qiu, K., Li, X., Chen, H. et al.
  - [arXiv:2509.12474](https://arxiv.org/abs/2509.12474)
  - 2025

- **AliTok: Towards Sequence Modeling Alignment between Tokenizer and Autoregressive Model**
  - Wu, P., Zhu, K., Liu, Y. et al.
  - [arXiv:2506.05289](https://arxiv.org/abs/2506.05289)
  - 2025


### Image Autoencoder with Generative Decoder

- **epsilon-vae: Denoising as visual decoding**
  - Zhao, L., Woo, S., Wan, Z.
  - [arXiv:2410.04081](https://arxiv.org/abs/2410.04081)
  - 2024

- **Diffusion autoencoders are scalable image tokenizers**
  - Chen, Y., Girdhar, R., Wang, X.
  - [arXiv:2501.18593](https://arxiv.org/abs/2501.18593)
  - 2025

- **FlexTok: Resampling Images into 1D Token Sequences of Flexible Length**
  - Bachmann, R., Allardice, J., Mizrahi, D. et al.
  - [**ICML 2025**](https://arxiv.org/abs/2502.13967)
  - 2025

- **D-AR: Diffusion via Autoregressive Models**
  - Gao, Z., Shou, M.Z.
  - [arXiv:2505.23660](https://arxiv.org/abs/2505.23660)
  - 2025

- **Generative Multimodal Pretraining with Discrete Diffusion Timestep Tokens**
  - Pan, K., Lin, W., Yue, Z.
  - [**CVPR 2025**](https://arxiv.org/abs/2504.14666)
  - 2025

- **Flow to the mode: Mode-seeking diffusion autoencoders for state-of-the-art image tokenization**
  - Sargent, K., Hsu, K., Johnson, J.
  - [arXiv:2503.11056](https://arxiv.org/abs/2503.11056)
  - 2025

- **" Principal Components" Enable A New Language of Images**
  - Wen, X., Zhao, B., Elezi, I.
  - [arXiv:2503.08685](https://arxiv.org/abs/2503.08685)
  - 2025



## Video Autoencoders

### Continuous 3D CNN Video Autoencoder

- **Video generation models as world simulators**
  - Brooks, T., Peebles, B., Holmes, C.
  - [**The SORA**](https://openai.com/index/video-generation-models-as-world-simulators/)
  - 2024

- **Cogvideox: Text-to-video diffusion models with an expert transformer**
  - Yang, Z., Teng, J., Zheng, W.
  - [arXiv:2408.06072](https://arxiv.org/abs/2408.06072)
  - 2024

- **Open-sora plan: Open-source large video generation model**
  - Lin, B., Ge, Y., Cheng, X.
  - [arXiv:2412.00131](https://arxiv.org/abs/2412.00131)
  - 2024

- **Hunyuanvideo: A systematic framework for large video generative models**
  - Kong, W., Tian, Q., Zhang, Z.
  - [arXiv:2412.03603](https://arxiv.org/abs/2412.03603)
  - 2024

- **Wan: Open and advanced large-scale video generative models**
  - Wan, T., Wang, A., Ai, B.
  - [arXiv:2503.20314](https://arxiv.org/abs/2503.20314)
  - 2025

- **Ltx-video: Realtime video latent diffusion**
  - HaCohen, Y., Chiprut, N., Brazowski, B.
  - [arXiv:2501.00103](https://arxiv.org/abs/2501.00103)
  - 2024

- **Cosmos world foundation model platform for physical ai**
  - Agarwal, N., Ali, A., Bala, M.
  - [arXiv:2501.03575](https://arxiv.org/abs/2501.03575)
  - 2025

- **LeanVAE: An Ultra-Efficient Reconstruction VAE for Video Diffusion Models**
  - Cheng, Y., Yuan, F.
  - [arXiv:2503.14325](https://arxiv.org/abs/2503.14325)
  - 2025

- **Wf-vae: Enhancing video vae by wavelet-driven energy flow for latent video diffusion model**
  - Li, Z., Lin, B., Ye, Y.
  - [**CVPR 2025**](https://arxiv.org/abs/2411.17459)
  - 2025

- **Step-video-t2v technical report: The practice, challenges, and future of video foundation model**
  - Ma, G., Huang, H., Yan, K.
  - [arXiv:2502.10248](https://arxiv.org/abs/2502.10248)
  - 2025

- **Waver: Wave Your Way to Lifelike Video Generation**
  - Zhang, Y., Yang, H., Zhang, Y.
  - [arXiv:2508.15761](https://arxiv.org/abs/2508.15761)
  - 2025

- **Vidtwin: Video vae with decoupled structure and dynamics**
  - Wang, Y., Guo, J., Xie, X.
  - [**CVPR 2025**](https://arxiv.org/abs/2412.17726)
  - 2025

### Discrete 3D CNN Video Autoencoder

- **Language Model Beats Diffusion--Tokenizer is Key to Visual Generation**
  - Yu, L., Lezama, J., Gundavarapu, N.B.
  - [arXiv:2310.05737](https://arxiv.org/abs/2310.05737)
  - 2023

- **Videopoet: A large language model for zero-shot video generation**
  - Kondratyuk, D., Yu, L., Gu, X.
  - [arXiv:2312.14125](https://arxiv.org/abs/2312.14125)
  - 2023

- **Loong: Generating minute-level long videos with autoregressive language models**
  - Wang, Y., Xiong, T., Zhou, D.
  - [arXiv:2410.02757](https://arxiv.org/abs/2410.02757)
  - 2024

- **Vidtok: A versatile and open-source video tokenizer**
  - Tang, A., He, T., Guo, J.
  - [arXiv:2412.13061](https://arxiv.org/abs/2412.13061)
  - 2024

- **Omnitokenizer: A joint image-video tokenizer for visual generation**
  - Wang, J., Jiang, Y., Yuan, Z.
  - [arXiv:2406.09399](https://arxiv.org/abs/2406.09399)
  - 2024

- **Cosmos world foundation model platform for physical ai**
  - Agarwal, N., Ali, A., Bala, M.
  - [arXiv:2501.03575](https://arxiv.org/abs/2501.03575)
  - 2025


### 3D Transformer Video Autoencoder

- **MAGI-1: Autoregressive Video Generation at Scale**
  - Teng, H., Jia, H., Sun, L.
  - [arXiv:2505.13211](https://arxiv.org/abs/2505.13211)
  - 2025

- **AToken: A Unified Tokenizer for Vision**
  - Lu, J., Song, L., Xu, M.
  - [arXiv:2509.14476](https://arxiv.org/abs/2509.14476)
  - 2025

- **Hi-VAE: Efficient Video Autoencoding with Global and Detailed Motion**
  - Liu, H., Sun, W., Zhang, Q.
  - [arXiv:2506.07136](https://arxiv.org/abs/2506.07136)
  - 2025

### 1D Video Autoencoder

- **Larp: Tokenizing videos with a learned autoregressive generative prior**
  - Wang, H., Suri, S., Ren, Y.
  - [arXiv:2410.21264](https://arxiv.org/abs/2410.21264)
  - 2024

- **Learning 1D causal visual representation with de-focus attention networks**
  - Tao, C., Zhu, X., Su, S.
  - [**NeurIPS 2025**](https://arxiv.org/abs/2406.04342)
  - 2024


### Video Autoencoder with Generative Decoder

- **Rethinking video tokenization: A conditioned diffusion-based approach**
  - Yang, N., Li, P., Zhao, L.
  - [arXiv:2503.03708](https://arxiv.org/abs/2503.03708)
  - 2025

- **REGEN: Learning Compact Video Embedding with (Re-) Generative Decoder**
  - Zhang, Y., Mai, L., Mahapatra, A.
  - [arXiv:2503.08665](https://arxiv.org/abs/2503.08665)
  - 2025

- **Hi-VAE: Efficient Video Autoencoding with Global and Detailed Motion**
  - Liu, H., Sun, W., Zhang, Q.
  - [arXiv:2506.07136](https://arxiv.org/abs/2506.07136)
  - 2025














