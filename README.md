# Autonomous Driving Papers :car:

This repository contains papers on autonomous driving. 

### :book: ICLR 2025

I might have missed some works as I only skimmed through the titles :pray:

#### :sparkles: Perception

- Cocoon: Robust Multi-Modal Perception with Uncertainty-Aware Sensor Fusion 
    - [OpenReview](https://openreview.net/forum?id=DKgAFfCs5F)
    - Keywords: sensor fusion, uncertainty quantification
    - Datasets: nuScenes

- MamBEV: Enabling State Space Models to Learn Birds-Eye-View Representations 
    - [OpenReview](https://openreview.net/forum?id=MvEkN2ejZ1)
    - Keywords: BEV, state space model, causal attention
    - Datasets: nuScenes

- MGMapNet: Multi-Granularity Representation Learning for End-to-End Vectorized HD
Map Construction
    - [OpenReview](https://openreview.net/forum?id=E8S5Upr6oO)
    - Keywords: online HD Map construction, lane detection, multi-granularity representation
    - Datasets: nuScenes, Argoverse2

- MOS: Model Synergy for Test-Time Adaptation on LiDAR-Based 3D Object Detection 
    - [OpenReview](https://openreview.net/forum?id=Y6aHdDNQYD)
    - Keywords: test-time adaptation
    - Datasets: KITTI, Waymo, nuScenes, KITTI-C

- Predictive Uncertainty Quantification for Bird's Eye View Segmentation: A Benchmark and Novel Loss Function 
    - [OpenReview](https://openreview.net/forum?id=k3y0oyK7sn)
    - Keywords: uncertainty quantification, BEV segmentation
    - Datasets: CALRA, nuScenes, Lyft, nuScenes-C

- RobuRCDet: Enhancing Robustness of Radar-Camera Fusion in Bird's Eye View for 3D Object Detection 
    - [OpenReview](https://openreview.net/forum?id=9xHlhKLu1h)
    - Keywords: radar-camera 3D object detection, robust detection
    - Datasets: 

- TAU-106K: A New Dataset for Comprehensive Understanding of Traffic Accident 
    - [OpenReview](https://openreview.net/forum?id=Fb0q2uI4Ha)
    - Keywords: traffic accident detection, MLLM
    - Datasets: TAU-106K (proposed)

- Uni^2Det: Unified and Universal Framework for Prompt-Guided Multi-dataset 3D Detection 
    - [OpenReview](https://openreview.net/forum?id=AcVpLS86RT)
    - Keywords: multi-dataset training
    - Datasets: KITTI, Waymo, nuScenes

- UniDrive: Towards Universal Driving Perception Across Camera Configurations 
    - [OpenReview](https://openreview.net/forum?id=jVDPq9EdzT) / [Code](https://github.com/ywyeli/UniDrive)
    - Keywords: cross domain perception, sensor configuration
    - Datasets: CARLA

#### :sparkles: Prediction

- Leveraging Driver Field-of-View for Multimodal Ego-Trajectory Prediction 
    - [OpenReview](https://openreview.net/forum?id=LLWj8on4Rv)
    - Keywords: ego-trajectory prediction, gaze, driver FOV
    - GEM (proposed; ego-motion dataset with driver positions and perspective)

- Trajectory-LLM: A Language-based Data Generator for Trajectory Prediction in Autonomous Driving
    - [OpenReview](https://openreview.net/forum?id=UapxTvxB3N)
    - Keywords: vehicle trajectory generator, language interface
    - Datasets: L2T (proposed), WOMD

- OccProphet: Pushing the Efficiency Frontier of Camera-Only 4D Occupancy Forecasting with an Observer-Forecaster-Refiner Framework 
    - [OpenReview](https://openreview.net/forum?id=vC7AlY1ytz)
    - Keywords: camera-only occupancy forecasting
    - Datasets: nuScenes, nuScenes-Occupancy, Lyft-Level5

- Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving 
    - [OpenReview](https://openreview.net/forum?id=rCX9l4OTCT)
    - Keywords: occupancy prediction, occupancy forecasting, semi-supervised

#### :sparkles: Planning

- AdaWM: Adaptive World Model based Planning for Autonomous Driving 
    - [OpenReview](https://openreview.net/forum?id=NEu8wgPctU)
    - Keywords: reinforcement learning, world model, adaptive finetuning
    - Datasets: Bench2Drive, CARLA

- Diffusion-Based Planning for Autonomous Driving with Flexible Guidance 
    - [OpenReview](https://openreview.net/forum?id=wM2sfVgMDH) / [Code](https://github.com/ZhengYinan-AIR/Diffusion-Planner)
    - Keywords: diffusion model, flexible guidance
    - Datasets: nuPlan, Delivery-vehicle Dataset (proposed)

#### :sparkles: Generation/Reconstruction

- DynamicCity: Large-Scale LiDAR Generation from Dynamic Scenes 
    - [OpenReview](https://openreview.net/forum?id=M7KyLjuN0A) / [Code](https://github.com/3DTopia/DynamicCity)
    - Keywords: 4D occupancy generation, HexPlane, DiT, conditional generation
    - Datasets: Occ3D-Waymo, Occ3D-nuScenes, CarlaSC

- FreeVS: Generative View Synthesis on Free Driving Trajectory 
    - [OpenReview](https://openreview.net/forum?id=dTGH9vUVdf) / [Code](https://github.com/esdolo/FreeVS)
    - Keywords: novel view synthesis, generative model, novel trajectory
    - Datasets: WOD

- Glad: A Streaming Scene Generator for Autonomous Driving 
    - [OpenReview](https://openreview.net/forum?id=ZFxpclrCCf)
    - Keywords: streaming video generation, diffusion models
    - Datasets: nuScenes

- GPUDrive: Data-driven, multi-agent driving simulation at 1 million FPS 
    - [OpenReview](https://openreview.net/forum?id=ERv8ptegFi) / [Code](https://github.com/Emerge-Lab/gpudrive)
    - Keywords: simulation, benchmark, multi-agent reinforcement learning, planning

- GS-LiDAR: Generating Realistic LiDAR Point Clouds with Panoramic Gaussian Splatting 
    - [OpenReview](https://openreview.net/forum?id=RMaRBE9s2H) / [Code](https://github.com/fudan-zvg/gs-lidar)
    - Keywords: novel view synthesis, LiDAR simulation, gaussian splatting
    - Datasets: KITTI-360, nuScenes

- OmniRe: Omni Urban Scene Reconstruction 
    - [OpenReview](https://openreview.net/forum?id=11xgiMEI5o) / [Project page](https://ziyc.github.io/omnire/)
    - Keywords: dynamic scene modeling, human modeling, gaussian splatting
    - Datasets: WOD, nuScenes, Argoverse2, PandaSet, KITTI, nuPlan

- X-Drive: Cross-modality Consistent Multi-Sensor Data Synthesis for Driving Scenarios 
    - [OpenReview](https://openreview.net/forum?id=IEMmEd5Jgm) / [Code](https://github.com/yichen928/X-Drive)
    - Keywords: multimodal generation, diffusion models 
    - Datasets: nuScenes

#### :sparkles: End-to-End Driving

- DriveTransformer: Unified Transformer for Scalable End-to-End Autonomous Driving 
    - [OpenReview](https://openreview.net/forum?id=M42KR4W9P5)
    - Keywords: task parallelism, sparse representation, streaming processing
    - Datasets: Bench2Drive, nuScenes

- Enhancing End-to-End Autonomous Driving with Latent World Model 
    - [OpenReview](https://openreview.net/forum?id=fd2u60ryG0) / [Code](https://github.com/BraveGroup/LAW)
    - Keywords: world model, self-supervised future latent prediction
    - Datasets: nuScenes, NAVSIM, CARLA

- Navigation-Guided Sparse Scene Representation for End-to-End Autonomous Driving 
    - [OpenReview](https://openreview.net/forum?id=Vv76fCYffN) / [Code](https://github.com/PeidongLi/SSR)
    - Keywords: (navigation-guided) sparse scene representation, self-supervised future feature prediction
    - Datasets: nuScenes, CARLA

#### :sparkles: Collaborative Driving

- Learning 3D Perception from Others' Predictions 
    - [OpenReview](https://openreview.net/forum?id=Ylk98vWQuQ) / [code](https://github.com/jinsuyoo/rnb-pop)
    - Keywords: label-efficient learning, domain adaptation, curriculum learning
    - Datasets: V2V4Real, OPV2V

- Point Cluster: A Compact Message Unit for Communication-Efficient Collaborative Perception 
    - [OpenReview](https://openreview.net/forum?id=54XlM8Clkg)
    - Keywords: communication efficiency, sparse detectors
    - Datasets: V2X-Set, OPV2V, DAIR-V2X

- STAMP: Scalable Task- And Model-agnostic Collaborative Perception 
    - [OpenReview](https://openreview.net/forum?id=8NdNniulYE)
    - Keywords: heterogeneous collaborative perception
    - Datasets: OPV2V, V2V4Real

#### General (haven't categorized yet..)

- 3D StreetUnveiler with Semantic-aware 2DGS - a simple baseline [[OpenReview](https://openreview.net/forum?id=G6aJyS0ZV0)]

- Adversarial Generative Flow Network for Solving Vehicle Routing Problems [[OpenReview](https://openreview.net/forum?id=tBom4xOW1H)]

- Boosting Neural Combinatorial Optimization for Large-Scale Vehicle Routing Problems [[OpenReview](https://openreview.net/forum?id=TbTJJNjumY)]

- Cocoon: Robust Multi-Modal Perception with Uncertainty-Aware Sensor Fusion [[OpenReview](https://openreview.net/forum?id=DKgAFfCs5F)]

- CoMotion: Concurrent Multi-person 3D Motion [[OpenReview](https://openreview.net/forum?id=qKu6KWPgxt)]

- CityAnchor: City-scale 3D Visual Grounding with Multi-modality LLMs [[OpenReview](https://openreview.net/forum?id=7nOl5W6xU4)]

- Learning to Generate Diverse Pedestrian Movements from Web Videos with Noisy Labels [[OpenReview](https://openreview.net/forum?id=DydCqKa6AH)]


- LoRA3D: Low-Rank Self-Calibration of 3D Geometric Foundation models [[OpenReview](https://openreview.net/forum?id=LSp4KBhAom)]


- MGMapNet: Multi-Granularity Representation Learning for End-to-End Vectorized HD Map Construction [[OpenReview](https://openreview.net/forum?id=E8S5Upr6oO)]





- Rethinking Light Decoder-based Solvers for Vehicle Routing Problems [[OpenReview](https://openreview.net/forum?id=4pRwkYpa2u)]


- Samba: Synchronized Set-of-Sequences Modeling for Multiple Object Tracking [[OpenReview](https://openreview.net/forum?id=OeBY9XqiTz)]


- SlowFast-VGen: Slow-Fast Learning for Action-Driven Long Video Generation [[OpenReview](https://openreview.net/forum?id=UL8b54P96G)]





#### (Potentially) Related

- 3D-AffordanceLLM: Harnessing Large Language Models for Open-Vocabulary Affordance Detection in 3D Worlds [[OpenReview](https://openreview.net/forum?id=GThTiuXgDC)]

- 4K4DGen: Panoramic 4D Generation at 4K Resolution [[OpenReview](https://openreview.net/forum?id=qxRoo7ULCo)]

- CityGaussianV2: Efficient and Geometrically Accurate Reconstruction for Large-Scale Scenes [[OpenReview](https://openreview.net/forum?id=a3ptUbuzbW)]

- Depth Any Video with Scalable Synthetic Data [[OpenReview](https://openreview.net/forum?id=gWqFbnKsqR)]

- Depth Pro: Sharp Monocular Metric Depth in Less Than a Second [[OpenReview](https://openreview.net/forum?id=aueXfY0Clv)]

- EmbodiedSAM: Online Segment Any 3D Thing in Real Time [[OpenReview](https://openreview.net/forum?id=XFYUwIyTxQ)]

- Gaussian-Det: Learning Closed-Surface Gaussians for 3D Object Detection [[OpenReview](https://openreview.net/forum?id=DtFCIfvAFc)]

- GOPS: Learning Generative Object Priors for Unsupervised 3D Instance Segmentation [[OpenReview](https://openreview.net/forum?id=wXSshrxlP4)]

- Interactive Adjustment for Human Trajectory Prediction with Individual Feedback [[OpenReview](https://openreview.net/forum?id=DCpukR83sw)]

- MetaUrban: An Embodied AI Simulation Platform for Urban Micromobility [[OpenReview](https://openreview.net/forum?id=kFsWpSxkFz)]

- MonST3R: A Simple Approach for Estimating Geometry in the Presence of Motion [[OpenReview](https://openreview.net/forum?id=lJpqxFgWCM)]

- MTSAM: Multi-Task Fine-Tuning for Segment Anything Model [[OpenReview](https://openreview.net/forum?id=6N4QMbeVaO)]

- Multimodality Helps Few-Shot 3D Point Cloud Semantic Segmentation [[OpenReview](https://openreview.net/forum?id=jXvwJ51vcK)]

- OVTR: End-to-End Open-Vocabulary Multiple Object Tracking with Transformer [[OpenReview](https://openreview.net/forum?id=GDS5eN65QY)]

- PointOBB-v2: Towards Simpler, Faster, and Stronger Single Point Supervised Oriented Object Detection [[OpenReview](https://openreview.net/forum?id=R22JPTQYWV)]

- Point-SAM: Promptable 3D Segmentation Model for Point Clouds [[OpenReview](https://openreview.net/forum?id=yXCTDhZDh6)]

- RMP-SAM: Towards Real-Time Multi-Purpose Segment Anything[[OpenReview](https://openreview.net/forum?id=1pXzC30ry5)]

- SAMRefiner: Taming Segment Anything Model for Universal Mask Refinement [[OpenReview](https://openreview.net/forum?id=JlDx2xp01W)]

- SAM-CP: Marrying SAM with Composable Prompts for Versatile Segmentation [[OpenReview](https://openreview.net/forum?id=UiEjzBRYeI)]

- Segment Any 3D Object with Language [[OpenReview](https://openreview.net/forum?id=ENv1CeTwxc)]

- Stable Segment Anything Model [[OpenReview](https://openreview.net/forum?id=ooxj2Audlq)]

- State Space Model Meets Transformer: A New Paradigm for 3D Object Detection [[OpenReview](https://openreview.net/forum?id=Tisu1L0Jwt)]

- TAPE3D: Tracking All Pixels Efficiently in 3D [[OpenReview](https://openreview.net/forum?id=d9iHI1eimo)]

- Track-On: Transformer-based Online Point Tracking with Memory [[OpenReview](https://openreview.net/forum?id=oRlANEuqG5)]

- TSC-Net: Predict Pedestrian Trajectory by Trajectory-Scene-Cell Classification [[OpenReview](https://openreview.net/forum?id=Xmh5gdMfRJ)]

- Union-over-Intersections: Object Detection beyond Winner-Takes-All [[OpenReview](https://openreview.net/forum?id=HqLHY4TzGj)]
