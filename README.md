# awesome-point-cloud-analysis [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

for anyone who wants to do research about 3D point cloud.   

If you find the awesome paper/code/dataset or have some suggestions, please contact linhua2017@ia.ac.cn. Thanks for your valuable contribution to the research community :smiley:   

<h1> 

```diff
- Recent papers (from 2017)
```

</h1>

<h3> Keywords </h3>

__`dat.`__: dataset &emsp; | &emsp; __`cls.`__: classification &emsp; | &emsp; __`rel.`__: retrieval &emsp; | &emsp; __`seg.`__: segmentation     
__`det.`__: detection &emsp; | &emsp; __`tra.`__: tracking &emsp; | &emsp; __`pos.`__: pose &emsp; | &emsp; __`dep.`__: depth     
__`reg.`__: registration &emsp; | &emsp; __`rec.`__: reconstruction &emsp; | &emsp; __`aut.`__: autonomous driving     
__`oth.`__: other, including normal-related, correspondence, mapping, matching, alignment, compression, generative model...

Statistics: :fire: code is available & stars >= 100 &emsp;|&emsp; :star: citation >= 50

---
## 2017
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Qi_PointNet_Deep_Learning_CVPR_2017_paper.pdf)] PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation. [[tensorflow](https://github.com/charlesq34/pointnet)][[pytorch](https://github.com/fxia22/pointnet.pytorch)] [__`cls.`__ __`seg.`__ __`det.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Simonovsky_Dynamic_Edge-Conditioned_Filters_CVPR_2017_paper.pdf)] Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs. [__`cls.`__] :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yi_SyncSpecCNN_Synchronized_Spectral_CVPR_2017_paper.pdf)] SyncSpecCNN: Synchronized Spectral CNN for 3D Shape Segmentation. [[torch](https://github.com/ericyi/SyncSpecCNN)] [__`seg.`__ __`oth.`__] :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)] ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes. [[project](http://www.scan-net.org/)][[git](http://www.scan-net.org/)] [__`dat.`__ __`cls.`__ __`rel.`__ __`seg.`__ __`oth.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Mostegel_Scalable_Surface_Reconstruction_CVPR_2017_paper.pdf)] Scalable Surface Reconstruction from Point Clouds with Extreme Scale and Density Diversity. [__`oth.`__] 
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Straub_Efficient_Global_Point_CVPR_2017_paper.pdf)] Efficient Global Point Cloud Alignment using Bayesian Nonparametric Mixtures. [[code]( http://people.csail.mit.edu/jstraub/)] [__`oth.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Vongkulbhisal_Discriminative_Optimization_Theory_CVPR_2017_paper.pdf)] Discriminative Optimization: Theory and Applications to Point Cloud Registration. [__`reg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Elbaz_3D_Point_Cloud_CVPR_2017_paper.pdf)] 3D Point Cloud Registration for Localization using a Deep Neural Network Auto-Encoder. [[git](https://github.com/gilbaz/LORAX)] [__`reg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Multi-View_3D_Object_CVPR_2017_paper.pdf)] Multi-View 3D Object Detection Network for Autonomous Driving. [[tensorflow](https://github.com/bostondiditeam/MV3D)] [__`det.`__ __`aut.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_3DMatch_Learning_Local_CVPR_2017_paper.pdf)] 3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions. [[code](https://github.com/andyzeng/3dmatch-toolbox)] [__`dat.`__ __`pos.`__ __`reg.`__ __`rec.`__ __`oth.`__] :fire: :star:
-
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Klokov_Escape_From_Cells_ICCV_2017_paper.pdf)] Escape from Cells: Deep Kd-Networks for the Recognition of 3D Point Cloud Models. [[pytorch](https://github.com/fxia22/kdnet.pytorch)] [__`cls.`__ __`rel.`__ __`seg.`__] :star:
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_3DCNN-DQN-RNN_A_Deep_ICCV_2017_paper.pdf)] 3DCNN-DQN-RNN: A Deep Reinforcement Learning Framework for Semantic Parsing of Large-scale 3D Point Clouds. [[code](https://github.com/CKchaos/scn2pointcloud_tool)] [__`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Park_Colored_Point_Cloud_ICCV_2017_paper.pdf)] Colored Point Cloud Registration Revisited. [__`reg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Nan_PolyFit_Polygonal_Surface_ICCV_2017_paper.pdf)] PolyFit: Polygonal Surface Reconstruction from Point Clouds. [[code](https://github.com/LiangliangNan/PolyFit)] [__`rec.`__] :fire:
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Ladicky_From_Point_Clouds_ICCV_2017_paper.pdf)] From Point Clouds to Mesh using Regression. [__`rec.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_3D_Graph_Neural_ICCV_2017_paper.pdf)] 3D Graph Neural Networks for RGBD Semantic Segmentation. [[pytorch](https://github.com/yanx27/3DGNN_pytorch)] [__`seg.`__]
- 
- [[NeurIPS](https://papers.nips.cc/paper/7095-pointnet-deep-hierarchical-feature-learning-on-point-sets-in-a-metric-space)] PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space. [[tensorflow](https://github.com/charlesq34/pointnet2)][[pytorch](https://github.com/erikwijmans/Pointnet2_PyTorch)] [__`cls.`__ __`seg.`__] :fire: :star:
- [[NeurIPS](https://papers.nips.cc/paper/6931-deep-sets)] Deep Sets. [[pytorch](https://github.com/manzilzaheer/DeepSets)] [__`cls.`__] :star:
- 
- [[ICRA](https://ieeexplore.ieee.org/document/7989161)] Vote3Deep: Fast object detection in 3D point clouds using efficient convolutional neural networks. [[code](https://github.com/lijiannuist/Vote3Deep_lidar)] [__`det.`__ __`aut.`__] :star:
- [[ICRA](https://ieeexplore.ieee.org/document/7989591)] Fast segmentation of 3D point clouds: A paradigm on LiDAR data for autonomous vehicle applications. [[code](https://github.com/VincentCheungM/Run_based_segmentation)] [__`seg.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/document/7989618)] SegMatch: Segment based place recognition in 3D point clouds. [__`seg.`__ __`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/document/7989664)] Using 2 point+normal sets for fast registration of point clouds with small overlap. [__`reg.`__]
- 
- [[IROS](https://ieeexplore.ieee.org/document/8202234)] Car detection for autonomous vehicle: LIDAR and vision fusion approach through deep learning framework. [__`det.`__ __`aut.`__]
- [[IROS](https://ieeexplore.ieee.org/document/8202239)] 3D object classification with point convolution network. [__`cls.`__]
- [[IROS](https://ieeexplore.ieee.org/document/8205955)] 3D fully convolutional network for vehicle detection in point cloud. [[tensorflow](https://github.com/yukitsuji/3D_CNN_tensorflow)] [__`det.`__ __`aut.`__] :fire: :star:
- [[IROS](https://ieeexplore.ieee.org/document/8206488)] Deep learning of directional truncated signed distance function for robust 3D object recognition. [__`det.`__ __`pos.`__]
- [[IROS](https://ieeexplore.ieee.org/document/8206584)] Analyzing the quality of matched 3D point clouds of objects. [__`oth.`__]
-
- [[3DV](http://segcloud.stanford.edu/segcloud_2017.pdf)] SEGCloud: Semantic Segmentation of 3D Point Clouds. [[project](http://segcloud.stanford.edu/)] [__`seg.`__ __`aut.`__] :star:
-
- [[TPAMI](https://ieeexplore.ieee.org/ielx7/34/8454009/08046026.pdf?tp=&arnumber=8046026&isnumber=8454009&ref=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8=)] Structure-aware Data Consolidation. [__`oth.`__]

---
## 2018
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Su_SPLATNet_Sparse_Lattice_CVPR_2018_paper.pdf)] SPLATNet: Sparse Lattice Networks for Point Cloud Processing. [[caffe](https://github.com/NVlabs/splatnet)] [__`seg.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xie_Attentional_ShapeContextNet_for_CVPR_2018_paper.pdf)] Attentional ShapeContextNet for Point Cloud Recognition. [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shen_Mining_Point_Cloud_CVPR_2018_paper.pdf)] Mining Point Cloud Local Structures by Kernel Correlation and Graph Pooling. [[code](http://www.merl.com/research/license#KCNet)] [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_FoldingNet_Point_Cloud_CVPR_2018_paper.pdf)] FoldingNet: Point Cloud Auto-encoder via Deep Grid Deformation. [[code](http://www.merl.com/research/license#FoldingNet)] [__`cls.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hua_Pointwise_Convolutional_Neural_CVPR_2018_paper.pdf)] Pointwise Convolutional Neural Networks. [[tensorflow](https://github.com/scenenn/pointwise)] [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_PU-Net_Point_Cloud_CVPR_2018_paper.pdf)] PU-Net: Point Cloud Upsampling Network. [[tensorflow](https://github.com/yulequan/PU-Net)] [__`rec.`__ __`oth.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_SO-Net_Self-Organizing_Network_CVPR_2018_paper.pdf)] SO-Net: Self-Organizing Network for Point Cloud Analysis. [[pytorch](https://github.com/lijx10/SO-Net)] [__`cls.`__ __`seg.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Recurrent_Slice_Networks_CVPR_2018_paper.pdf)] Recurrent Slice Networks for 3D Segmentation of Point Clouds. [[pytorch](https://github.com/qianguih/RSNet)] [__`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Graham_3D_Semantic_Segmentation_CVPR_2018_paper.pdf)] 3D Semantic Segmentation with Submanifold Sparse Convolutional Networks. [[pytorch](https://github.com/facebookresearch/SparseConvNet)] [__`seg.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Deep_Parametric_Continuous_CVPR_2018_paper.pdf)] Deep Parametric Continuous Convolutional Neural Networks. [__`seg.`__ __`aut.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf)] PIXOR: Real-time 3D Object Detection from Point Clouds. [[pytorch](https://github.com/ankita-kalra/PIXOR)] [__`det.`__ __`aut.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_SGPN_Similarity_Group_CVPR_2018_paper.pdf)] SGPN: Similarity Group Proposal Network for 3D Point Cloud Instance Segmentation. [[tensorflow](https://github.com/laughtervv/SGPN)] [__`seg.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Landrieu_Large-Scale_Point_Cloud_CVPR_2018_paper.pdf)] Large-scale Point Cloud Semantic Segmentation with Superpoint Graphs. [[pytorch](https://github.com/loicland/superpoint_graph)] [__`seg.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_VoxelNet_End-to-End_Learning_CVPR_2018_paper.pdf)] VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection. [[tensorflow](https://github.com/tsinghua-rll/VoxelNet-tensorflow)] [__`det.`__ __`aut.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yun_Reflection_Removal_for_CVPR_2018_paper.pdf)] Reflection Removal for Large-Scale 3D Point Clouds. [__`oth.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ge_Hand_PointNet_3D_CVPR_2018_paper.pdf)] Hand PointNet: 3D Hand Pose Estimation using Point Sets. [[pytorch](https://github.com/3huo/Hand-Pointnet)] [__`pos.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Uy_PointNetVLAD_Deep_Point_CVPR_2018_paper.pdf)] PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition. [[tensorflow](https://github.com/mikacuy/pointnetvlad.git)] [__`rel.`__] :fire:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Roveri_A_Network_Architecture_CVPR_2018_paper.pdf)] A Network Architecture for Point Cloud Classification via Automatic Depth Images Generation. [__`cls.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lawin_Density_Adaptive_Point_CVPR_2018_paper.pdf)] Density Adaptive Point Set Registration. [[code](https://github.com/felja633/DARE)] [__`reg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Birdal_A_Minimalist_Approach_CVPR_2018_paper.pdf)] A Minimalist Approach to Type-Agnostic Detection of Quadrics in Point Clouds. [__`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Vongkulbhisal_Inverse_Composition_Discriminative_CVPR_2018_paper.pdf)] Inverse Composition Discriminative Optimization for Point Cloud Registration. [__`reg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Reddy_CarFusion_Combining_Point_CVPR_2018_paper.pdf)] CarFusion: Combining Point Tracking and Part Detection for Dynamic 3D Reconstruction of Vehicles. [__`tra.`__ __`det.`__ __`rec.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_PPFNet_Global_Context_CVPR_2018_paper.pdf)] PPFNet: Global Context Aware Local Features for Robust 3D Point Matching. [__`oth.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Le_PointGrid_A_Deep_CVPR_2018_paper.pdf)] PointGrid: A Deep Network for 3D Shape Understanding. [[tensorflow](https://github.com/trucleduc/PointGrid)] [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf)] PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation. [[code](https://github.com/malavikabindhi/CS230-PointFusion)] [__`det.`__ __`aut.`__]
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf)] Frustum PointNets for 3D Object Detection from RGB-D Data. [[tensorflow](https://github.com/charlesq34/frustum-pointnets)] [__`det.`__ __`aut.`__] :fire: :star:
- [[CVPR](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tatarchenko_Tangent_Convolutions_for_CVPR_2018_paper.pdf)] Tangent Convolutions for Dense Prediction in 3D. [[tensorflow](https://github.com/tatarchm/tangent_conv)] [__`seg.`__ __`aut.`__]
- 
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Matheus_Gadelha_Multiresolution_Tree_Networks_ECCV_2018_paper.pdf)] Multiresolution Tree Networks for 3D Point Cloud Processing. [[pytorch](https://github.com/matheusgadelha/MRTNet)] [__`cls.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lequan_Yu_EC-Net_an_Edge-aware_ECCV_2018_paper.pdf)] EC-Net: an Edge-aware Point set Consolidation Network. [[tensorflow](https://github.com/yulequan/EC-Net)] [__`oth.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaoqing_Ye_3D_Recurrent_Neural_ECCV_2018_paper.pdf)] 3D Recurrent Neural Networks with Context Fusion for Point Cloud Semantic Segmentation. [__`seg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lei_Zhou_Learning_and_Matching_ECCV_2018_paper.pdf)] Learning and Matching Multi-View Descriptors for Registration of Point Clouds. [__`reg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zi_Jian_Yew_3DFeat-Net_Weakly_Supervised_ECCV_2018_paper.pdf)] 3DFeat-Net: Weakly Supervised Local 3D Features for Point Cloud Registration. [[tensorflow](https://github.com/yewzijian/3DFeatNet)] [__`reg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Chu_Wang_Local_Spectral_Graph_ECCV_2018_paper.pdf)] Local Spectral Graph Convolution for Point Set Feature Learning. [[tensorflow](https://github.com/fate3439/LocalSpecGCN)] [__`cls.`__ __`seg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yifan_Xu_SpiderCNN_Deep_Learning_ECCV_2018_paper.pdf)] SpiderCNN: Deep Learning on Point Sets with Parameterized Convolutional Filters. [[tensorflow](https://github.com/xyf513/SpiderCNN)] [__`cls.`__ __`seg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yinlong_Liu_Efficient_Global_Point_ECCV_2018_paper.pdf)] Efficient Global Point Cloud Registration by Matching Rotation Invariant Features Through Translation Search. [__`reg.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Kejie_Li_Efficient_Dense_Point_ECCV_2018_paper.pdf)] Efficient Dense Point Cloud Object Reconstruction using Deformation Vector Fields. [__`rec.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Dario_Rethage_Fully-Convolutional_Point_Networks_ECCV_2018_paper.pdf)] Fully-Convolutional Point Networks for Large-Scale Point Clouds. [[tensorflow](https://github.com/drethage/fully-convolutional-point-network)] [__`seg.`__ __`oth.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ming_Liang_Deep_Continuous_Fusion_ECCV_2018_paper.pdf)] Deep Continuous Fusion for Multi-Sensor 3D Object Detection. [__`det.`__]
- [[ECCV](http://openaccess.thecvf.com/content_ECCV_2018/papers/Benjamin_Eckart_Fast_and_Accurate_ECCV_2018_paper.pdf)] HGMR: Hierarchical Gaussian Mixtures for Adaptive 3D Registration. [__`reg.`__]
- 
- [[AAAI](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16530/16302)] Learning Efficient Point Cloud Generation for Dense 3D Object Reconstruction. [[tensorflow](https://github.com/chenhsuanlin/3D-point-cloud-generation)] [__`rec.`__] :fire:
- [[AAAI](https://ai.tencent.com/ailab/media/publications/aaai/junzhou_-AAAI-Adaptive_Graph_Convolutional_Neural_NetworksI.pdf)] Adaptive Graph Convolutional Neural Networks. [__`cls.`__]
- 
- [[NeurIPS](https://papers.nips.cc/paper/7545-unsupervised-learning-of-shape-and-pose-with-differentiable-point-clouds)] Unsupervised Learning of Shape and Pose with Differentiable Point Clouds. [[tensorflow](https://github.com/eldar/differentiable-point-clouds)] [__`pos.`__]
- [[NeurIPS](https://papers.nips.cc/paper/7362-pointcnn-convolution-on-x-transformed-points)] PointCNN: Convolution On X-Transformed Points. [[tensorflow](https://github.com/yangyanli/PointCNN)][[pytorch](https://github.com/hxdengBerkeley/PointCNN.Pytorch)] [__`cls.`__ __`seg.`__] :fire:
- 
- [[SIGGRAPH](https://arxiv.org/abs/1803.10091)] Point Convolutional Neural Networks by Extension Operators. [[tensorflow](https://github.com/matanatz/pcnn)] [__`cls.`__ __`seg.`__]
- [[SIGGRAPH](https://arxiv.org/abs/1803.09263)] P2P-NET: Bidirectional Point Displacement Net for Shape Transform. [[tensorflow](https://github.com/kangxue/P2P-NET)] [__`oth.`__]
- [[SIGGRAPH Asia](https://arxiv.org/abs/1806.01759)] Monte Carlo Convolution for Learning on Non-Uniformly Sampled Point Clouds. [[tensorflow](https://github.com/viscom-ulm/MCCNN)] [__`cls.`__ __`seg.`__ __`oth.`__]
- [[SIGGRAPH](https://arxiv.org/abs/1706.04496)] Learning local shape descriptors from part correspondences with multi-view convolutional networks. [[project](https://people.cs.umass.edu/~hbhuang/local_mvcnn/index.html)] [__`seg.`__ __`oth.`__] 
-
- [[MM](https://arxiv.org/abs/1808.07659)] PVNet: A Joint Convolutional Network of Point Cloud and Multi-View for 3D Shape Recognition. [__`cls.`__ __`rel.`__]
- [[MM](https://arxiv.org/abs/1806.02952)] RGCNN: Regularized Graph CNN for Point Cloud Segmentation. [[tensorflow](https://github.com/tegusi/RGCNN)] [__`seg.`__]
- [[MM](https://arxiv.org/abs/1804.10783)] Hybrid Point Cloud Attribute Compression Using Slice-based Layered Structure and Block-based Intra Prediction. [__`oth.`__]
-
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8462884)] End-to-end Learning of Multi-sensor 3D Tracking by Detection. [__`det.`__ __`tra.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460837)] Multi-View 3D Entangled Forest for Semantic Segmentation and Mapping. [__`seg.`__ __`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8462926)] SqueezeSeg: Convolutional Neural Nets with Recurrent CRF for Real-Time Road-Object Segmentation from 3D LiDAR Point Cloud. [[tensorflow](https://github.com/priyankanagaraj1494/Squeezseg)] [__`seg.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461257)] Robust Real-Time 3D Person Detection for Indoor and Outdoor Applications. [__`det.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461048)] High-Precision Depth Estimation with the 3D LiDAR and Stereo Fusion. [__`dep.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461095)] Sampled-Point Network for Classification of Deformed Building Element Point Clouds. [__`cls.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460532)] Gemsketch: Interactive Image-Guided Geometry Extraction from Point Clouds. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460605)] Signature of Topologically Persistent Points for 3D Point Cloud Description. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461232)] A General Pipeline for 3D Detection of Vehicles. [__`det.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460716)] Robust and Fast 3D Scan Alignment Using Mutual Information. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460940)] Delight: An Efficient Descriptor for Global Localisation Using LiDAR Intensities. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460862)] Surface-Based Exploration for Autonomous 3D Modeling. [__`oth.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460554)] Deep Lidar CNN to Understand the Dynamics of Moving Vehicles. [__`oth.`__ __`aut.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460887)] Dex-Net 3.0: Computing Robust Vacuum Suction Grasp Targets in Point Clouds Using a New Analytic Model and Deep Learning. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460639)] Real-Time Object Tracking in Sparse Point Clouds Based on 3D Interpolation. [__`tra.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460825)] Robust Generalized Point Cloud Registration Using Hybrid Mixture Model. [__`reg.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461049)] A General Framework for Flexible Multi-Cue Photometric Point Cloud Registration. [__`reg.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461000)] Efficient Continuous-Time SLAM for 3D Lidar-Based Online Mapping. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461102)] Direct Visual SLAM Using Sparse Depth for Camera-LiDAR System. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460910)] Spatiotemporal Learning of Dynamic Gestures from 3D Point Cloud Data. [__`cls.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460204)] Asynchronous Multi-Sensor Fusion for 3D Mapping and Localization. [__`oth.`__]
- [[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460834)] Complex Urban LiDAR Data Set. [[video](https://www.youtube.com/watch?v=IguZjmLf5V0&feature=youtu.be)] [__`dat.`__ __`oth.`__]
- 
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593693)] CalibNet: Geometrically Supervised Extrinsic Calibration using 3D Spatial Transformer Networks.[[tensorflow](https://github.com/epiception/CalibNet)] [__`oth.`__ __`aut.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593839)] Dynamic Scaling Factors of Covariances for Accurate 3D Normal Distributions Transform Registration. [__`reg.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593733)] A 3D Laparoscopic Imaging System Based on Stereo-Photogrammetry with Random Patterns. [__`rec.`__ __`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593558)] Robust Generalized Point Cloud Registration with Expectation Maximization Considering Anisotropic Positional Uncertainties. [__`reg.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594024)] Octree map based on sparse point cloud and heuristic probability distribution for labeled images. [__`oth.`__ __`aut.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593854)] PoseMap: Lifelong, Multi-Environment 3D LiDAR Localization. [__`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593953)] Scan Context: Egocentric Spatial Descriptor for Place Recognition Within 3D Point Cloud Map. [__`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594299)] LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain.[[code](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM)] [__`pos.`__ __`oth.`__] :fire:
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593741)] Classification of Hanging Garments Using Learned Features Extracted from 3D Point Clouds. [__`cls.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594362)] Stereo Camera Localization in 3D LiDAR Maps. [__`pos.`__ __`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594362)] Joint 3D Proposal Generation and Object Detection from View Aggregation. [__`det.`__] :star:
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594318)] Joint Point Cloud and Image Based Localization for Efficient Inspection in Mixed Reality. [__`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593910)] Edge and Corner Detection for Unorganized 3D Point Clouds with Application to Robotic Welding. [__`det.`__ __`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594175)] NDVI Point Cloud Generator Tool Using Low-Cost RGB-D Sensor. [[code](https://github.com/CTTCGeoLab/VI_ROS)][__`oth.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593837)] A 3D Convolutional Neural Network Towards Real-Time Amodal 3D Object Detection. [__`det.`__ __`pos.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594356)] Extracting Phenotypic Characteristics of Corn Crops Through the Use of Reconstructed 3D Models. [__`seg.`__ __`rec.`__]
- [[IROS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8594514)] PCAOT: A Manhattan Point Cloud Registration Method Towards Large Rotation and Small Overlap. [__`reg.`__]
- 
- [[SENSORS](https://www.mdpi.com/1424-8220/18/10/3337)] SECOND: Sparsely Embedded Convolutional Detection. [[pytorch](https://github.com/traveller59/second.pytorch)] [__`det.`__ __`aut.`__] :fire:
-
- [[ACCV](https://arxiv.org/abs/1803.07289)] Flex-Convolution (Million-Scale Point-Cloud Learning Beyond Grid-Worlds). [[tensorflow](https://github.com/cgtuebingen/Flex-Convolution)] [__`seg.`__]
-
- [[3DV](https://arxiv.org/abs/1808.00671)] PCN: Point Completion Network. [[tensorflow](https://github.com/TonythePlaneswalker/pcn)] [__`reg.`__ __`oth.`__ __`aut.`__]
-
- [[ICASSP](https://arxiv.org/abs/1812.01711)] A Graph-CNN for 3D Point Cloud Classification. [[tensorflow](https://github.com/maggie0106/Graph-CNN-in-3D-Point-Cloud-Classification)] [__`cls.`__] :fire:
-
- [[arXiv](https://arxiv.org/abs/1807.00652)] PointSIFT: A SIFT-like Network Module for 3D Point Cloud Semantic Segmentation. [[tensorflow](https://github.com/MVIG-SJTU/pointSIFT)] [__`seg.`__] :fire:
- [[arXiv](https://arxiv.org/abs/1805.07872)] Spherical Convolutional Neural Network for 3D Point Clouds. [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1811.07605)] Adversarial Autoencoders for Generating 3D Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1811.11209)] Iterative Transformer Network for 3D Point Cloud. [__`cls.`__ __`seg.`__ __`pos.`__]
- [[arXiv](https://arxiv.org/abs/1811.12543)] Topology-Aware Surface Reconstruction for Point Clouds. [__`rec.`__]
- [[arXiv](https://arxiv.org/abs/1812.01402)] Inferring Point Clouds from Single Monocular Images by Depth Intermediation. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1812.04302)] Deep RBFNet: Point Cloud Feature Learning using Radial Basis Functions. [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1812.05276)] IPOD: Intensive Point-based Object Detector for Point Cloud. [__`det.`__]
- [[arXiv](https://arxiv.org/abs/1812.07050)] 3D Point Cloud Learning for Large-scale Environment Analysis and Place Recognition. [__`rel.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1812.11017)] Deflecting 3D Adversarial Point Clouds Through Outlier-Guided Removal. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1812.11383)] Feature Preserving and Uniformity-controllable Point Cloud Simplification on Graph. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1901.01060)] POINTCLEANNET: Learning to Denoise and Remove Outliers from Dense Point Clouds. [[pytorch](https://github.com/mrakotosaon/pointcleannet)] [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1803.06199)] Complex-YOLO: Real-time 3D Object Detection on Point Clouds. [[pytorch](https://github.com/AI-liu/Complex-YOLO)] [__`det.`__ __`aut.`__] :fire:
- [[arxiv](https://arxiv.org/abs/1811.03818)] RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement. [[tensorflow](https://github.com/Kiwoo/RoarNet)] [__`det.`__ __`aut.`__]

---
## 2019
- [[CVPR](http://export.arxiv.org/abs/1904.07601)] Relation-Shape Convolutional Neural Network for Point Cloud Analysis. [[pytorch](https://github.com/Yochengliu/Relation-Shape-CNN)] [__`cls.`__ __`seg.`__ __`oth.`__]
- [[CVPR](https://raoyongming.github.io/files/SFCNN.pdf)] Spherical Fractal Convolutional Neural Networks for Point Cloud Recognition. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1811.11397)] DeepMapping: Unsupervised Map Estimation From Multiple Point Clouds. [[code](https://ai4ce.github.io/DeepMapping/)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1812.07179)] Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving. [[code](https://github.com/mileyan/pseudo_lidar)] [__`det.`__ __`dep.`__ __`aut.`__]
- [[CVPR](https://arxiv.org/abs/1812.04244)] PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud. [[pytorch](https://github.com/sshaoshuai/PointRCNN)] [__`det.`__ __`aut.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1809.07016)] Generating 3D Adversarial Point Clouds. [[code](https://github.com/xiangchong1/3d-adv-pc)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.03375v1)] Modeling Point Clouds with Self-Attention and Gumbel Subset Sampling. [__`cls.`__ __`seg.`__]
- [[CVPR](http://export.arxiv.org/abs/1904.08017)] A-CNN: Annularly Convolutional Neural Networks on Point Clouds. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1811.07246)] PointConv: Deep Convolutional Networks on 3D Point Clouds. [[tensorflow](https://github.com/DylanWusee/pointconv)] [__`cls.`__ __`seg.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1812.11647)] Path-Invariant Map Networks. [[tensorflow](https://github.com/zaiweizhang/path_invariance_map_network)] [__`seg.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.02713)] PartNet: A Large-scale Benchmark for Fine-grained and Hierarchical Part-level 3D Object Understanding. [[code](https://github.com/daerduoCarey/partnet_dataset)] [__`dat.`__ __`seg.`__]
- [[CVPR](http://export.arxiv.org/abs/1901.00680)] GeoNet: Deep Geodesic Networks for Point Cloud Analysis. [__`cls.`__ __`rec.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1902.09852)] Associatively Segmenting Instances and Semantics in Point Clouds. [[tensorflow](https://github.com/WXinlong/ASIS)] [__`seg.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1811.08988)] Supervised Fitting of Geometric Primitives to 3D Point Clouds. [[tensorflow](https://github.com/csimstu2/SPFN)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1903.00343)] Octree guided CNN with Spherical Kernels for 3D Point Clouds. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1903.05711)] PointNetLK: Point Cloud Registration using PointNet. [[pytorch](https://github.com/hmgoforth/PointNetLK)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1904.00699v1)] JSIS3D: Joint Semantic-Instance Segmentation of 3D Point Clouds with Multi-Task Pointwise Networks and Multi-Value Conditional Random Fields. [[pytorch](https://github.com/pqhieu/JSIS3D)] [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1904.02113)] Point Cloud Oversegmentation with Graph-Structured Deep Metric Learning. [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1812.05784)] PointPillars: Fast Encoders for Object Detection from Point Clouds. [[pytorch](https://github.com/nutonomy/second.pytorch)] [__`det.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1811.11286)] Patch-based Progressive 3D Point Set Upsampling. [[tensorflow](https://github.com/yifita/3PU)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.09793)] PCAN: 3D Attention Map Learning Using Contextual Information for Point Cloud Based Retrieval. [[code](https://github.com/XLechter/PCAN)] [__`rel.`__]
- [[CVPR](https://arxiv.org/abs/1903.00709)] PartNet: A Recursive Part Decomposition Network for Fine-grained and Hierarchical Shape Segmentation. [[pytorch](https://github.com/FoggYu/PartNet)] [__`dat.`__ __`seg.`__] 
- [[CVPR](https://arxiv.org/abs/1806.02170)] PointFlowNet: Learning Representations for Rigid Motion Estimation from Point Clouds. [[code](https://github.com/aseembehl/pointflownet)] [__`det.`__ __`dat.`__ __`oth.`__] 
- [[CVPR](https://arxiv.org/abs/1904.03483)] SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences. [[matlab](https://github.com/intellhave/SDRSAC)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1903.04019)] Deep Reinforcement Learning of Volume-guided Progressive View Inpainting for 3D Point Scene Completion from a Single Depth Image. [__`rec.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.03461)] Embodied Question Answering in Photorealistic Environments with Point Cloud Perception. [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.10775v1)] 3D Point-Capsule Networks. [[pytorch](https://github.com/yongheng1991/3D-point-capsule-networks)] [__`cls.`__ __`rec.`__ __`oth.`__]
- [[CVPR](http://export.arxiv.org/abs/1904.08755)] 4D Spatio-Temporal ConvNets: Minkowski Convolutional Neural Networks. [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1811.06879v2)] The Perfect Match: 3D Point Cloud Matching with Smoothed Densities. [[tensorflow](https://github.com/zgojcic/3DSmoothNet)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1811.10136)] FilterReg: Robust and Efficient Probabilistic Point-Set Registration using Gaussian Filter and Twist Parameterization. [[code](https://bitbucket.org/gaowei19951004/poser/src/master/)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1806.01411)] FlowNet3D: Learning Scene Flow in 3D Point Clouds. [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1811.07782)] Modeling Local Geometric Structure of 3D Point Clouds using Geo-CNN. [__`cls.`__ __`det.`__]
- [[CVPR](http://www.linliang.net/wp-content/uploads/2019/04/CVPR2019_PointClound.pdf)] ClusterNet: Deep Hierarchical Cluster Network with Rigorously Rotation-Invariant Representation for Point Cloud Analysis. [__`cls.`__]
- [[CVPR](http://jiaya.me/papers/pointweb_cvpr19.pdf)] PointWeb: Enhancing Local Neighborhood Features for Point Cloud Processing. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1904.12304)] RL-GAN-Net: A Reinforcement Learning Agent Controlled GAN Network for Real-Time Point Cloud Shape Completion. [[code](https://github.com/iSarmad/RL-GAN-Net)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1903.05711)] PointNetLK: Robust & Efficient Point Cloud Registration using PointNet. [[pytorch](https://github.com/hmgoforth/PointNetLK)] [__`reg.`__]
- [[CVPR](https://www.researchgate.net/publication/332240602_Robust_Point_Cloud_Based_Reconstruction_of_Large-Scale_Outdoor_Scenes)] Robust Point Cloud Based Reconstruction of Large-Scale Outdoor Scenes. [[code](https://github.com/ziquan111/RobustPCLReconstruction)] [__`rec.`__]
- [[CVPR](https://arxiv.org/abs/1812.00709)] Nesti-Net: Normal Estimation for Unstructured 3D Point Clouds using Convolutional Neural Networks. [[tensorflow](https://github.com/sitzikbs/Nesti-Net)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.03320)] GSPN: Generative Shape Proposal Network for 3D Instance Segmentation in Point Cloud. [__`seg.`__]
- [[CVPR](https://engineering.purdue.edu/~jshan/publications/2018/Lei%20Wang%20Graph%20Attention%20Convolution%20for%20Point%20Cloud%20Segmentation%20CVPR2019.pdf)] Graph Attention Convolution for Point Cloud Segmentation. [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1812.02050)] Point-to-Pose Voting based Hand Pose Estimation using Residual Permutation Equivariant Layer. [__`pos.`__]
- [[CVPR](https://arxiv.org/abs/1903.08701v1)] LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving. [__`det.`__ __`aut.`__]
- [[CVPR](https://arxiv.org/pdf/1904.03498.pdf)] LP-3DCNN: Unveiling Local Phase in 3D Convolutional Neural Networks. [[project](https://sites.google.com/view/lp-3dcnn/home)] [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Duan_Structural_Relational_Reasoning_of_Point_Clouds_CVPR_2019_paper.pdf)] Structural Relational Reasoning of Point Clouds. [__`cls.`__ __`seg.`__]
-
- [[ICLR](https://openreview.net/forum?id=SJeXSo09FQ)] Learning Localized Generative Models for 3D Point Clouds via Graph Convolution. [__`oth.`__]
-
- [[AAAI](https://arxiv.org/abs/1811.11731)] CAPNet: Continuous Approximation Projection For 3D Point Cloud Reconstruction Using 2D Supervision. [[code](https://github.com/val-iisc/capnet)] [__`rec.`__] 
- [[AAAI](https://arxiv.org/abs/1811.02565)] Point2Sequence: Learning the Shape Representation of 3D Point Clouds with an Attention-based Sequence to Sequence Network. [[tensorflow](https://github.com/liuxinhai/Point2Sequence)] [__`cls.`__ __`seg.`__]
- [[AAAI](https://par.nsf.gov/biblio/10086163)] Point Cloud Processing via Recurrent Set Encoding. [__`cls.`__]
- [[AAAI](https://arxiv.org/abs/1812.00333)] PVRNet: Point-View Relation Neural Network for 3D Shape Recognition. [[pytorch](https://github.com/Hxyou/PVRNet)] [__`cls.`__ __`rel.`__]
- [[AAAI](http://gaoyue.org/paper/HGNN.pdf)] Hypergraph Neural Networks. [[pytorch](https://github.com/iMoonLab/HGNN)] [__`cls.`__]
-
- [[TOG](https://arxiv.org/abs/1801.07829)] Dynamic Graph CNN for Learning on Point Clouds. [[tensorflow](https://github.com/WangYueFt/dgcnn)][[pytorch](https://github.com/muhanzhang/pytorch_DGCNN)] [__`cls.`__ __`seg.`__] :fire: :star:
-
- [[ICRA](https://arxiv.org/abs/1904.00319)] Discrete Rotation Equivariance for Point Cloud Recognition. [[pytorch](https://github.com/lijx10/rot-equ-net)] [__`cls.`__]
- [[ICRA](https://arxiv.org/abs/1809.08495)] SqueezeSegV2: Improved Model Structure and Unsupervised Domain Adaptation for Road-Object Segmentation from a LiDAR Point Cloud. [[tensorflow](https://github.com/xuanyuzhou98/SqueezeSegV2)] [__`seg.`__ __`aut.`__]
- [[ICRA](https://www.ais.uni-bonn.de/papers/ICRA_2019_Razlaw.pdf)] Detection and Tracking of Small Objects in Sparse 3D Laser Range Data. [__`det.`__ __`tra.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1905.02553)] Oriented Point Sampling for Plane Detection in Unorganized Point Clouds. [__`det.`__ __`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_1.html)] Point Cloud Compression for 3D LiDAR Sensor Using Recurrent Neural Network with Residual Blocks. [[pytorch](https://github.com/ChenxiTU/Point-cloud-compression-by-RNN)] [__`oth.`__]
- [[ICRA](https://arxiv.org/abs/1809.06065)] Focal Loss in 3D Object Detection. [[code](https://github.com/pyun-ram/FL3D)] [__`det.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1809.06267)] PointNetGPD: Detecting Grasp Configurations from Point Sets. [[pytorch](https://github.com/lianghongzhuo/PointNetGPD)] [__`det.`__ __`seg.`__]
- [[ICRA](https://arxiv.org/abs/1904.09742)] 2D3D-MatchNet: Learning to Match Keypoints across 2D Image and 3D Point Cloud. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] Speeding up Iterative Closest Point Using Stochastic Gradient Descent. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] Uncertainty Estimation for Projecting Lidar Points Onto Camera Images for Moving Platforms. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] SEG-VoxelNet for 3D Vehicle Detection from RGB and LiDAR Data. [__`det.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1903.06405v1)] BLVD: Building A Large-scale 5D Semantics Benchmark for Autonomous Driving. [[project](https://github.com/VCCIV/BLVD)] [__`dat.`__ __`det.`__ __`tra.`__ __`aut.`__ __`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] A Fast and Robust 3D Person Detector and Posture Estimator for Mobile Robotic Applications. [__`det.`__]
- [[ICRA](https://arpg.colorado.edu/papers/hmrf_icp.pdf)] Robust low-overlap 3-D point cloud registration for outlier rejection. [[matlab](https://github.com/JStech/ICP)] [__`reg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Robust 3D Object Classification by Combining Point Pair Features and Graph Convolution. [__`cls.`__ __`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Hierarchical Depthwise Graph Convolutional Neural Network for 3D Semantic Segmentation of Point Clouds. [__`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Robust Generalized Point Set Registration Using Inhomogeneous Hybrid Mixture Models Via Expectation. [__`reg.`__]
- [[ICRA](https://arxiv.org/abs/1902.07511)] Dense 3D Visual Mapping via Semantic Simplification. [__`oth.`__]
- [[ICRA](https://arxiv.org/abs/1904.01649)] MVX-Net: Multimodal VoxelNet for 3D Object Detection. [__`det.`__ __`aut.`__]
- [[ICRA](https://export.arxiv.org/abs/1810.01470)] CELLO-3D: Estimating the Covariance of ICP in the Real World. [__`reg.`__]
-
- [[Eurographics Workshop](https://arxiv.org/abs/1904.02375)] Generalizing Discrete Convolutions for Unstructured Point Clouds. [[pytorch](https://github.com/aboulch/ConvPoint)] [__`cls.`__ __`seg.`__]
-
- [[arXiv](https://arxiv.org/abs/1901.02532)] Fast 3D Line Segment Detection From Unorganized Point Cloud. [__`det.`__]
- [[arXiv](https://arxiv.org/abs/1812.01687)] Point-Cloud Saliency Maps. [[tensorflow](https://github.com/tianzheng4/PointCloud-Saliency-Maps)] [__`cls.`__ __`oth.`__]
- [[arXiv](https://export.arxiv.org/abs/1901.03006)] Extending Adversarial Attacks and Defenses to Deep 3D Point Cloud Classifiers. [[code](https://github.com/Daniel-Liu-c0deb0t/3D-Neural-Network-Adversarial-Attacks)] [__`oth.`__]
- [[arxiv](https://arxiv.org/abs/1901.08396)] Context Prediction for Unsupervised Deep Learning on Point Clouds. [__`cls.`__ __`seg.`__]
- [[arXiv](http://export.arxiv.org/abs/1901.09280)] Points2Pix: 3D Point-Cloud to Image Translation using conditional Generative Adversarial Networks. [__`oth.`__]
- [[arXiv](http://export.arxiv.org/abs/1901.09394)] NeuralSampler: Euclidean Point Cloud Auto-Encoder and Sampler. [__`cls.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1902.05247)] 3D Graph Embedding Learning with a Structure-aware Loss Function for Point Cloud Semantic Instance Segmentation. [__`seg.`__]
- [[arXiv](https://arxiv.org/abs/1902.10272)] Zero-shot Learning of 3D Point Cloud Objects. [[code](https://github.com/alichr/Zero-shot-Learning-of-3D-Point-Cloud-Objects)] [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1903.09847)] Monocular 3D Object Detection with Pseudo-LiDAR Point Cloud. [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1903.01695)] Real-time Multiple People Hand Localization in 4D Point Clouds. [__`det.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.02858)] Variational Graph Methods for Efficient Point Cloud Sparsification. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.05807)] Neural Style Transfer for Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.07918)] OREOS: Oriented Recognition of 3D Point Clouds in Outdoor Scenarios. [__`pos.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.10750)] FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds. [[code](https://github.com/LordLiang/FVNet)] [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1904.00069)] Unpaired Point Cloud Completion on Real Scans using Adversarial Training. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.00229)] USIP: Unsupervised Stable Interest Point Detection from 3D Point Clouds. [[code](https://github.com/lijx10/USIP)] [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.00230)] MortonNet: Self-Supervised Learning of Local Features in 3D Point Clouds. [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1904.00817)] DeepPoint3D: Learning Discriminative Local Descriptors using Deep Metric Learning on 3D Point Clouds. [__`cls.`__ __`rel.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.01416)] A Dataset for Semantic Segmentation of Point Cloud Sequences. [__`dat.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1904.04427)] 3D Point Cloud Denoising via Deep Neural Network based Local Surface Estimation. [[code](https://github.com/chaojingduan/Neural-Projection)] [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.07537)] Complexer-YOLO: Real-Time 3D Object Detection and Tracking on Semantic Point Clouds. [[pytorch](https://github.com/AI-liu/Complex-YOLO)] [__`det.`__ __`tra.`__ __`aut.`__] :fire:
- [[arXiv](https://arxiv.org/abs/1904.10795)] Graph-based Inpainting for 3D Dynamic Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.11027)] nuScenes: A multimodal dataset for autonomous driving. [[link](https://www.nuscenes.org/overview)] [__`dat.`__ __`det.`__ __`tra.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1901.08373)] 3D Backbone Network for 3D Object Detection. [[code](https://github.com/Benzlxs/tDBN)] [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1904.08889)] KPConv: Flexible and Deformable Convolution for Point Clouds. [[tensorflow](https://github.com/HuguesTHOMAS/KPConv)] [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1904.09664v1)] Deep Hough Voting for 3D Object Detection in Point Clouds. [__`det.`__]
- [[arXiv](https://arxiv.org/abs/1811.07605v3)] Adversarial Autoencoders for Compact Representations of 3D Point Clouds. [[pytorch](https://github.com/MaciejZamorski/3d-AAE)] [__`rel.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/pdf/1904.10014.pdf)] Linked Dynamic Graph CNN: Learning on Point Cloud via Linking Hierarchical Features. [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1905.08705)] GAPNet: Graph Attention based Point Neural Network for Exploiting Local Feature of Point Cloud. [[tensorflow](https://github.com/FrankCAN/GAPNet)] [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1906.01140)] Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds. [[tensorflow](https://github.com/Yang7879/3D-BoNet)] [__`det.`__ __`seg.`__]
- [[arXiv](https://export.arxiv.org/abs/1906.04173)] Differentiable Surface Splatting for Point-based Geometry Processing. [[pytorch](https://github.com/yifita/DSS)] [__`oth.`__]
- 
- [[IV2019](https://arxiv.org/abs/1906.10964)] End-to-End 3D-PointCloud Semantic Segmentation for Autonomous Driving. [__`seg.`__] [__`aut.`__]

<h1> 

```diff
- Datasets
```

</h1>

- [[KITTI](http://www.cvlibs.net/datasets/kitti/)] The KITTI Vision Benchmark Suite. [__`det.`__]
- [[ModelNet](http://modelnet.cs.princeton.edu/)] The Princeton ModelNet . [__`cls.`__]
- [[ShapeNet](https://www.shapenet.org/)]  A collaborative dataset between researchers at Princeton, Stanford and TTIC. [__`seg.`__]
- [[PartNet](https://shapenet.org/download/parts)] The PartNet dataset provides fine grained part annotation of objects in ShapeNetCore. [__`seg.`__]
- [[PartNet](http://kevinkaixu.net/projects/partnet.html)] PartNet benchmark from Nanjing University and National University of Defense Technology. [__`seg.`__]
- [[S3DIS](http://buildingparser.stanford.edu/dataset.html#Download)] The Stanford Large-Scale 3D Indoor Spaces Dataset. [__`seg.`__]
- [[ScanNet](http://www.scan-net.org/)] Richly-annotated 3D Reconstructions of Indoor Scenes. [__`cls.`__ __`seg.`__]
- [[Stanford 3D](https://graphics.stanford.edu/data/3Dscanrep/)] The Stanford 3D Scanning Repository. [__`reg.`__]
- [[UWA Dataset](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)] . [__`cls.`__ __`seg.`__ __`reg.`__]
- [[Princeton Shape Benchmark](http://shape.cs.princeton.edu/benchmark/)] The Princeton Shape Benchmark.
- [[SYDNEY URBAN OBJECTS DATASET](http://www.acfr.usyd.edu.au/papers/SydneyUrbanObjectsDataset.shtml)] This dataset contains a variety of common urban road objects scanned with a Velodyne HDL-64E LIDAR, collected in the CBD of Sydney, Australia. There are 631 individual scans of objects across classes of vehicles, pedestrians, signs and trees. [__`cls.`__ __`match.`__]
- [[ASL Datasets Repository(ETH)](https://projects.asl.ethz.ch/datasets/doku.php?id=home)] This site is dedicated to provide datasets for the Robotics community with the aim to facilitate result evaluations and comparisons. [__`cls.`__ __`match.`__ __`reg.`__ __`det`__]
- [[Large-Scale Point Cloud Classification Benchmark(ETH)](http://www.semantic3d.net/)] This benchmark closes the gap and provides a large labelled 3D point cloud data set of natural scenes with over 4 billion points in total. [__`cls.`__]
- [[Robotic 3D Scan Repository](http://asrl.utias.utoronto.ca/datasets/3dmap/)] The Canadian Planetary Emulation Terrain 3D Mapping Dataset is a collection of three-dimensional laser scans gathered at two unique planetary analogue rover test facilities in Canada.  
- [[Radish](http://radish.sourceforge.net/)] The Robotics Data Set Repository (Radish for short) provides a collection of standard robotics data sets.
- [[IQmulus & TerraMobilita Contest](http://data.ign.fr/benchmarks/UrbanAnalysis/#)] The database contains 3D MLS data from a dense urban environment in Paris (France), composed of 300 million points. The acquisition was made in January 2013. [__`cls.`__ __`seg.`__ __`det.`__]
- [[Oakland 3-D Point Cloud Dataset](http://www.cs.cmu.edu/~vmr/datasets/oakland_3d/cvpr09/doc/)] This repository contains labeled 3-D point cloud laser data collected from a moving platform in a urban environment.
- [[Robotic 3D Scan Repository](http://kos.informatik.uni-osnabrueck.de/3Dscans/)] This repository provides 3D point clouds from robotic experiments，log files of robot runs and standard 3D data sets for the robotics community.
- [[Ford Campus Vision and Lidar Data Set](http://robots.engin.umich.edu/SoftwareData/Ford)] The dataset is collected by an autonomous ground vehicle testbed, based upon a modified Ford F-250 pickup truck. 
- [[The Stanford Track Collection](https://cs.stanford.edu/people/teichman/stc/)] This dataset contains about 14,000 labeled tracks of objects as observed in natural street scenes by a Velodyne HDL-64E S2 LIDAR.
- [[PASCAL3D+](http://cvgl.stanford.edu/projects/pascal3d.html)] Beyond PASCAL: A Benchmark for 3D Object Detection in the Wild. [__`pos.`__ __`det.`__]
- [[3D MNIST](https://www.kaggle.com/daavoo/3d-mnist)] The aim of this dataset is to provide a simple way to get started with 3D computer vision problems such as 3D shape recognition. [__`cls.`__]
- [[WAD](http://wad.ai/)] This dataset is provided by Baidu Inc.
- [[nuScenes](https://d3u7q4379vrm7e.cloudfront.net/object-detection)] The nuScenes dataset is a large-scale autonomous driving dataset.
- [[PreSIL](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/projects/precise-synthetic-image-and-lidar-presil-dataset-autonomous)] Depth information, semantic segmentation (images), point-wise segmentation (point clouds), ground point labels (point clouds), and detailed annotations for all vehicles and people. [[paper](https://arxiv.org/abs/1905.00160)] [__`det.`__ __`aut.`__]
- [[3D Match](http://3dmatch.cs.princeton.edu/)] Keypoint Matching Benchmark, Geometric Registration Benchmark, RGB-D Reconstruction Datasets. [__`reg.`__ __`rec.`__ __`oth.`__]
- [[BLVD](https://github.com/VCCIV/BLVD)] (a) 3D detection, (b) 4D tracking, (c) 5D interactive event recognition and (d) 5D intention prediction. [[ICRA 2019 paper](https://arxiv.org/abs/1903.06405v1)] [__`det.`__ __`tra.`__ __`aut.`__ __`oth.`__]
- [[PedX](https://arxiv.org/abs/1809.03605)] 3D Pose Estimation of Pedestrians, more than 5,000 pairs of high-resolution (12MP) stereo images and LiDAR data along with providing 2D and 3D labels of pedestrians. [[ICRA 2019 paper](https://arxiv.org/abs/1809.03605)] [__`pos.`__ __`aut.`__]
- [[H3D](https://usa.honda-ri.com/H3D)] Full-surround 3D multi-object detection and tracking dataset. [[ICRA 2019 paper](https://arxiv.org/abs/1903.01568)] [__`det.`__ __`tra.`__ __`aut.`__]