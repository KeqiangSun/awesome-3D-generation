# Awesome 3D Generation

## Point Cloud Generation

### GAN-based Model

- Learning representations and generative models for 3d point clouds <br>
  [ICML 2018](https://arxiv.org/abs/1707.02392) / [Code](https://github.com/optas/latent_3d_points)
- 3d point cloud generative adversarial network based on tree structured graph convolutions <br>
  [ICCV 2019](https://arxiv.org/abs/1905.06292) / [Code](https://github.com/prajwalsingh/TreeGCN-GAN)
- Point cloud gan <br>
  [ICLR 2019](https://arxiv.org/abs/1810.05795)
- Spectral-gans for high-resolution 3d point-cloud generation <br>
  [IROS 2020](https://arxiv.org/abs/1912.01800) / [Code](https://github.com/samgregoost/Spectral-GAN)
- Progressive point cloud deconvolution generation network <br>
  [ECCV 2020](https://arxiv.org/abs/2007.05361) / [Code](https://github.com/fpthink/PDGN)
- MRGAN: MultiRooted 3D Shape Generation with Unsupervised Part Disentanglement <br>
  [ICCVW 2021](https://arxiv.org/abs/2007.12944)
- A progressive conditional generative adversarial network for generating dense and colored 3D point clouds <br>
  [3DV 2020](https://arxiv.org/abs/2010.05391) / [Code](https://github.com/robotic-vision-lab/Progressive-Conditional-Generative-Adversarial-Network)
- SP-GAN: Sphere-guided 3D shape generation and manipulation <br>
  [SIGGRAPH 2021](https://arxiv.org/abs/2108.04476) / [Code](https://github.com/liruihui/sp-gan)
- Multimodal shape completion via conditional generative adversarial networks <br>
  [ECCV 2020](https://arxiv.org/abs/2003.07717) / [Code](https://github.com/ChrisWu1997/Multimodal-Shape-Completion)
- Learning localized generative models for 3d point clouds via graph convolution <br>
  [ICLR 2019](https://openreview.net/pdf?id=SJeXSo09FQ) / [Code](https://github.com/diegovalsesia/GraphCNN-GAN)

### Flow-based Model

- Learning gradient fields for shape generation <br>
  [ECCV 2020](https://arxiv.org/abs/2008.06520) / [Code](https://github.com/RuojinCai/ShapeGF)
- PointFlow : 3D Point Cloud Generation with Continuous Normalizing Flows <br>
  [ICCV 2019](https://arxiv.org/abs/1906.12320) / [Code](https://github.com/stevenygd/PointFlow)
- SoftFlow: Probabilistic framework for normalizing flow on manifolds <br>
  [NeurIPS 2020](https://arxiv.org/abs/2006.04604) / [Code](https://github.com/ANLGBOY/SoftFlow)
- Discrete point flow networks for efficient point cloud generation <br>
  [ECCV 2020](https://arxiv.org/abs/2007.10170) / [Code](https://github.com/Regenerator/dpf-nets)

### Auto-regressive Model

- Pointgrow: Autoregressively learned point cloud generation with self-attention <br>
  [WACV 2020](https://arxiv.org/abs/1810.05591) / [Code](https://github.com/syb7573330/PointGrow)

### VAE

- Multiresolution tree networks for 3d point cloud processing <br>
  [ECCV 2018](https://openaccess.thecvf.com/content_ECCV_2018/papers/Matheus_Gadelha_Multiresolution_Tree_Networks_ECCV_2018_paper.pdf) / [Code](https://github.com/matheusgadelha/MRTNet)
- Adversarial autoencoders for generating 3d point clouds <br>
  [ICLR 2020](https://arxiv.org/abs/1811.07605) / [Code](https://github.com/MaciejZamorski/3d-AAE)

## Voxel Grids

- Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling <br>
  [NeurIPS 2016](https://arXiv.org/abs/1610.07584) / [Code](https://github.com/zck119/3dgan-release)
- Generalized Autoencoder for Volumetric Shape Generation <br>
  [CVPRW 2020](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w17/Guan_Generalized_Autoencoder_for_Volumetric_Shape_Generation_CVPRW_2020_paper.pdf) / [Code](https://github.com/IsaacGuan/3D-GAE)
- PQ-NET: A Generative Part Seq2Seq Network for 3D Shapes <br>
  [CVPR 2020](https://arxiv.org/abs/1911.10949) / [Code](https://github.com/ChrisWu1997/PQ-NET)
- DECOR-GAN: 3D Shape Detailization by Conditional Refinement <br>
  [CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_DECOR-GAN_3D_Shape_Detailization_by_Conditional_Refinement_CVPR_2021_paper.pdf) / [Code](https://github.com/czq142857/DECOR-GAN)
- 3d shapenets: A deep representation for volumetric shapes <br>
  [CVPR 2015](https://arxiv.org/abs/1406.5670) / [Code](https://github.com/zhirongw/3DShapeNets)
- Learning part generation and assembly for structure-aware shape synthesis <br>
  [AAAI 2020](https://arxiv.org/abs/1906.06693)
- SAGNet: Structure-aware Generative Network for 3D-Shape Modeling
  [SIGGRAPH 2019](https://dilincv.github.io/papers/SAGNet_sig2019.pdf) / [Code](https://github.com/zhijieW94/SAGNet)
- Generative VoxelNet: learning energy-based models for 3D shape synthesis and analysis <br>
  [TPAMI 2020](http://www.stat.ucla.edu/~jxie/3DDescriptorNet/3DDescriptorNet_file/doc/3DDescriptorNet.pdf) / [Code](https://github.com/jianwen-xie/3DDescriptorNet)
- Octree Transformer: Autoregressive 3D Shape Generation on Hierarchically Structured Sequences <br>
  [arXiv 2021](https://arxiv.org/abs/2111.12480)
- DLGAN: Depth-Preserving Latent Generative Adversarial Network for 3D Reconstruction <br>
  [TMM 2020](https://ieeexplore.ieee.org/document/9174748)
- Shape completion using 3d-encoder-predictor cnns and shape synthesis <br>
  [CVPR 2017](https://arxiv.org/abs/1612.00101) / [Code](https://github.com/angeladai/cnncomplete)
- Scancomplete: Large-scale scene completion and semantic segmentation for 3d scans <br>
  [CVPR 2018](https://arxiv.org/abs/1712.10215) / [Code](https://github.com/angeladai/ScanComplete)
- Generative and discriminative voxel modeling with convolutional neural networks <br>
  [arXiv 2016](https://arxiv.org/abs/1608.04236) / [Code](https://github.com/ajbrock/Generative-and-Discriminative-Voxel-Modeling)
- Octree generating networks: Efficient convolutional architectures for high-resolution 3d outputs <br>
  [ICCV 2017](https://openaccess.thecvf.com/content_ICCV_2017/papers/Tatarchenko_Octree_Generating_Networks_ICCV_2017_paper.pdf) / [Code](https://github.com/lmb-freiburg/ogn)
- Deep octree-based cnns with output-guided skip connections for 3d shape and scene completion <br>
  [CVPR 2020](https://arxiv.org/abs/2006.03762) / [Code](https://github.com/microsoft/O-CNN)

## Mesh

- Sdm-net: Deep generative network for structured deformable mesh <br>
  [SIGGRAPH Asia 2019](https://arxiv.org/abs/1908.04520) / [Code](http://geometrylearning.com/sdm-net/)

## Implicit function

- Learning Implicit Fields for Generative Shape Modeling <br>
  [CVPR 2019](https://arxiv.org/abs/1812.02822) / [Code](https://github.com/czq142857/implicit-decoder)
- Adversarial generation of continuous implicit shape representations <br>
  [arXiv 2020](https://arxiv.org/abs/2002.00349) / [Code](https://github.com/marian42/shapegan)
- DualSDF: Semantic Shape Manipulation using a Two-Level Representation <br>
  [CVPR 2020](https://arxiv.org/abs/2004.02869) / [Code](https://github.com/zekunhao1995/DualSDF)
- SurfGen: Adversarial 3D Shape Synthesis with Explicit Surface Discriminators <br>
  [ICCV 2021](https://arxiv.org/abs/2201.00112)
- 3d shape generation with grid-based implicit functions <br>
  [CVPR 2021](https://arxiv.org/abs/2107.10607)
- gDNA: Towards Generative Detailed Neural Avatars <br>
  [CVPR 2022](https://arxiv.org/abs/2201.04123) / [Code](https://github.com/xuchen-ethz/gdna)
- Deformed implicit field: Modeling 3d shapes with learned dense correspondence <br>
  [CVPR 2021](https://arxiv.org/abs/2011.13650) / [Code](https://github.com/microsoft/DIF-Net)

## Parametric surface

- Multi-chart generative surface modeling <br>
  [SIGGRAPH Asia 2018](https://arxiv.org/abs/1806.02143) / [Code](https://github.com/helibenhamu/multichart3dgans)

## Primitive shapes

- Physically-aware generative network for 3d shape modeling <br>
  [CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Mezghanni_Physically-Aware_Generative_Network_for_3D_Shape_Modeling_CVPR_2021_paper.html)

## Hybrid representation

- Deep Marching Tetrahedra: a Hybrid Representation for High-Resolution 3D Shape Synthesis <br>
  [NeurIPS 2021](https://arxiv.org/abs/2111.04276)
- Coupling explicit and implicit surface representations for generative 3d modeling <br>
  [ECCV 2020](https://arxiv.org/abs/2007.10294)

## Program

- Shapeassembly: Learning to generate programs for 3d shape structure synthesis <br>
  [SIGGRAPH Asia 2020](https://arxiv.org/abs/2009.08026) / [Code](https://github.com/rkjones4/ShapeAssembly)

## 3D-aware Image Synthesis

### Explicit representation

- HoloGAN: Unsupervised Learning of 3D representations from Natural Images <br>
  [ICCV 2019](https://arXiv.org/abs/1904.01326) / [Code](https://github.com/thunguyenphuoc/HoloGAN)
- Points2Pix: 3D Point-Cloud to Image Translation using conditional Generative Adversarial Networks <br>
  [arXiv 2019](https://arXiv.org/abs/1901.09280)
- BlockGAN: Learning 3D Object-aware Scene Representations from Unlabelled Images <br>
  [NeurIPS 2020](https://arXiv.org/abs/2002.08988) / [Code](https://github.com/thunguyenphuoc/BlockGAN)

### Image-space rendering

- Generative Image Modeling using Style and Structure Adversarial Networks <br>
  [ECCV 2016](https://arXiv.org/abs/1603.05631) / [Code](https://github.com/xiaolonw/ss-gan)
- Geometric Image Synthesis <br>
  [ACCV 2018](https://arXiv.org/abs/1809.04696)
- RGBD-GAN: Unsupervised 3D Representation Learning From Natural Image Datasets via RGBD Image Synthesis <br>
  [ICLR 2020](https://arXiv.org/abs/1909.12573) / [Code](https://github.com/nogu-atsu/RGBD-GAN)
- Towards a Neural Graphics Pipeline for Controllable Image Generation <br>
  [Computer Graphics Forum 2021](https://arXiv.org/abs/2006.10569)
- 3D-Aware Indoor Scene Synthesis with Depth Priors <br>
  [arXiv 2022](https://arXiv.org/abs/2202.08553) / [Code](https://github.com/VivianSZF/depthgan)

### Implicit Function

- GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis <br>
  [NeurIPS 2020](https://arXiv.org/abs/2007.02442) / [Code](https://github.com/autonomousvision/graf)
- GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields <br>
  [CVPR 2021](https://arXiv.org/abs/2011.12100) / [Code](https://github.com/autonomousvision/giraffe)
- pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis <br>
  [CVPR 2021](https://arXiv.org/abs/2012.00926) / [Code](https://github.com/marcoamonteiro/pi-GAN)
- Unconstrained Scene Generation with Locally Conditioned Radiance Fields <br>
  [ICCV 2021](https://arXiv.org/abs/2104.00670) / [Code](https://github.com/apple/ml-gsn)
- A Shading-Guided Generative Implicit Model for Shape-Accurate 3D-Aware Image Synthesis <br>
  [NeurIPS 2021](https://arXiv.org/abs/2110.15678) / [Code](https://github.com/xingangpan/shadegan)
- StyleNeRF: A Style-based 3D-Aware Generator for High-resolution Image Synthesis <br>
  [ICLR 2022](https://arXiv.org/abs/2110.08985) / [Code](https://github.com/facebookresearch/StyleNeRF)
- Efficient Geometry-aware 3D Generative Adversarial Networks <br>
  [CVPR 2022](https://arXiv.org/abs/2112.07945) / [Code](https://github.com/NVlabs/eg3d)
- 3D-aware Image Synthesis via Learning Structural and Textural Representations <br>
  [CVPR 2022](https://arXiv.org/abs/2112.10759) / [Code](https://github.com/genforce/volumegan)
- StyleSDF: High-Resolution 3D-Consistent Image and Geometry Generation <br>
  [CVPR 2022](https://arXiv.org/abs/2112.11427) / [Code](https://github.com/royorel/StyleSDF)
- GRAM: Generative Radiance Manifolds for 3D-Aware Image Generation <br>
  [CVPR 2022](https://arXiv.org/abs/2112.08867)
- Campari: Camera-aware Decomposed Generative Neural Radiance Fields <br>
  [3DV 2021](https://arXiv.org/abs/2103.17269)
- CIPS-3D: A 3D-Aware Generator of GANs Based on Conditionally-Independent Pixel Synthesis <br>
  [arXiv 2021](https://arXiv.org/abs/2110.09788) / [Code](https://github.com/PeterouZh/CIPS-3D)
- GANcraft: Unsupervised 3D Neural Rendering of Minecraft Worlds <br>
  [ICCV 2021](https://arXiv.org/abs/2104.07659) / [Code](https://github.com/NVlabs/GANcraft)
- Generative Occupancy Fields for 3D Surface-Aware Image Synthesis <br>
  [NeurIPS 2021](https://arXiv.org/abs/2111.00969) / [Code](https://github.com/SheldonTsui/GOF_NeurIPS2021)
- 3D-Aware Semantic-Guided Generative Model for Human Synthesis <br>
  [arXiv 2021](https://arXiv.org/abs/2112.01422)

### Per-scene optimization with a discriminator

- Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis <br>
  [ICCV 2021](https://arXiv.org/abs/2104.00677) / [Code](https://github.com/codestella/putting-nerf-on-a-diet)
- GNeRF: GAN-based Neural Radiance Field without Posed Camera <br>
  [ICCV 2021](https://arXiv.org/abs/2103.15606) / [Code](https://github.com/MQ66/gnerf)
- RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs <br>
  [CVPR 2022](https://arXiv.org/abs/2112.00724) / [Code](https://github.com/google-research/google-research/tree/master/regnerf)

### 3D editing

- Learning Realistic Human Reposing using Cyclic Self-Supervision with 3D Shape, Pose, and Appearance Consistency <br>
  [ICCV 2021](https://arXiv.org/abs/2110.05458)
- FENeRF: Face Editing in Neural Radiance Fields <br>
  [arXiv 2021](https://arXiv.org/abs/2111.15490)
- Pix2NeRF: Unsupervised Conditional π-GAN for Single Image to Neural Radiance Fields Translation <br>
  [CVPR 2022](https://arXiv.org/abs/2202.13162)

### Others

- Visual Object Networks: Image Generation with Disentangled 3D Representation <br>
  [NeurIPS 2018](https://arXiv.org/abs/1812.02725)
