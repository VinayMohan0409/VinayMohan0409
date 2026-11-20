# Vinay Mohan

Machine Learning Engineer focused on 3D world models, robot learning, and generative modelling. My research explores cross-embodiment latent action representations for zero-shot robotic manipulation, combining Point Transformer architectures, learned dynamics, and planning in latent space. I also develop vision-based robotic systems and end-to-end machine learning applications, with experience spanning spatial AI, deep learning, and reliable ML deployment.

## Research

### [DexLatentWorld — 3D Cross-Embodiment Latent Action World Models](https://github.com/VinayMohan0409/DexLatentWorld)

Developed a 3D world model for zero-shot robotic manipulation using particle-based scene representations and Point Transformer V3. Learned shared latent actions across human and robot-hand embodiments with inverse and forward dynamics models and cross-embodiment contrastive learning. Evaluated latent-space planning with CEM in simulated manipulation tasks, including the DexWM benchmark.

## Selected Projects

### [Humanoid: Spatial AI & Navigation Challenge](https://github.com/VinayMohan0409/humanoid-spatial)

Built a 3D scene change-detection system using VGGT Omega for reconstruction from two viewpoints and DINOv3 features for 3D segmentation. Detects added, removed, and moved objects while accounting for viewpoint differences, occlusion, and incomplete observations.

### [Humanoid: Robot Learning Research](https://github.com/VinayMohan0409/humanoid-submission)

Collected 64 egocentric human video clips and co-trained a world model with 30 simulated Panda demonstrations. Used frozen DINOv3 features as latent states and learned latent actions to represent changes between frames. Evaluated goal-image planning for reaching and carrying in simulation using a separately trained inverse dynamics model.

### [Real-Time Clinical Monitoring and AKI Detection](https://github.com/VinayMohan0409/SWEMLS)

End-to-end ML system consuming HL7 streams, performing PyTorch inference, and issuing real-time clinical alerts. Containerised with Docker and tested through service-level integration tests.

### [Patronising and Condescending Language Detection](https://github.com/VinayMohan0409/NLP_PCL_detection)

Reframed binary classification as natural-language inference using DeBERTa, focal loss, and layer-wise learning-rate decay.

### [Mammographic Density Prediction](https://github.com/VinayMohan0409/MLI_mammographic_density_prediction)

Compared convolutional and transfer-learning architectures for density classification from mammography images.

### [Math4ML: Kryptonite-2](https://github.com/FelixBaastadBerg/Math4ML)

Investigated the Kryptonite-2 binary-classification challenge using tuned MLPs, MLP ensembles, CNNs, and RBF-kernel SVMs across six dataset sizes. Evaluated calibration, ensemble uncertainty, and generalisation bounds, with a tuned MLP reaching about 97% accuracy on the largest dataset.

### Latent Diffusion for Image Generation

Implemented a DDPM in the latent space of a pretrained VAE, including noise schedules, a time-conditioned U-Net, reverse-process sampling, and end-to-end training. Trained the model to generate plausible hot-dog images and evaluated samples using an independent image classifier.

_Implementation remains private due to university assessment restrictions._
