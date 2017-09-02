# Recommended Papers ![Maintenance](https://img.shields.io/maintenance/yes/2017.svg) [![DUB](https://img.shields.io/dub/l/vibe-d.svg)](LICENSE)
- The goal of this document is to provide a reading list for Deep Learning in Computer Vision Field.

## Paper Collections   ![new](https://img.shields.io/badge/docs-New-brightgreen.svg)
- [CVPR 2017 papers related to Attention Model](CVPR2017-Attention-model/README.md)
- [Paper List for Instance Aware Tasks](Instance-Aware-Paper-List/README.md)

## Topics
- [Salient Object Detection](#salient-object-detection)
- [Visual Object Tracking](#visual-object-tracking)
- [Object Detection](#object-detection)
- [Object Localization](#object-localization)
- [Semantic Segmentation and Scene Parsing](#semantic-segmentation-and-scene-parsing)
- [Edge Detection](#edge-detection)
- [Pose Estimation](#pose-estimation)
- [Super Resolution](#super-resolution)
- [Image Classification](#image-classification)
- [Others](#others)

## Papers
Paper list.

### Salient Object Detection
|No.  |Figure   |Title   |Authors  |Pub.  |Links|
|-----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![MDF](data/MDF.png)|__Visual Saliency Based on Multiscale Deep Features__|[Guanbin Li](https://sites.google.com/site/ligb86/), Yizhou Yu|__CVPR 2015__|[`project page`](https://sites.google.com/site/ligb86/mdfsaliency/)|
|2|![MCDL](data/MCDL.png)|__Saliency Detection by Multi-context Deep Learning__|[Rui Zhao](http://www.ee.cuhk.edu.hk/~rzhao/), Wanli Ouyang, Hongsheng Li, Xiaogang Wang|__CVPR 2015__|[`paper`](http://www.ee.cuhk.edu.hk/~rzhao/project/deepsal_cvpr15/zhaoOLWcvpr15.pdf) [`code`](https://github.com/Robert0812/deepsaldet)|
|3|![LEGS](data/LEGS.png)|__Deep Networks for Saliency Detection via Local Estimation and Global Search__|Lijun Wang, Huchuan Lu, Xiang Ruan, Ming-Hsuan Yang|__CVPR 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Deep_Networks_for_2015_CVPR_paper.pdf) [`code`](https://drive.google.com/file/d/0B5rfGpkt3dDaVmhucE1jTVZGeTA/view)|
|4|![DHS](data/DHS.png)|__DHSNet: Deep Hierarchical Saliency Network for Salient Object Detection__|[Nian Liu](https://sites.google.com/site/liunian228/), Junwei Han|__CVPR 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DHSNet_Deep_Hierarchical_CVPR_2016_paper.pdf) [`Google Drive`](https://drive.google.com/file/d/0B1sbejbIJIW3RlJJY1NNNkFydEU/view) [`Baidu Yun`](https://pan.baidu.com/s/1jIm8cfk) :star:|
|5|![DCL](data/DCL.png)|__Deep Contrast Learning for Salient Object Detection__|[Guanbin Li](https://sites.google.com/site/ligb86/), Yizhou Yu|__CVPR 2016__|[`project page`](http://i.cs.hku.hk/~gbli/deep_saliency.html)|
|6|![SU](data/SU.png)|__Saliency Unified: A Deep Architecture for Simultaneous Eye Fixation Prediction and Salient Object Segmentation__|Srinivas S S Kruthiventi, Vennela Gudisa, Jaley H Dholakiya and R. Venkatesh Babu|__CVPR 2016__|[`project page`](http://val.serc.iisc.ernet.in/saliency-unified/)|
|7|![ELD](data/ELD.png)|__Deep Saliency with Encoded Low level Distance Map and High Level Features__|Gayoung Lee, Yu-Wing Tai, Junmo Kim|__CVPR 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lee_Deep_Saliency_With_CVPR_2016_paper.pdf) [`code`](https://github.com/gylee1103/SaliencyELD)|
|8|![RAN](data/RAN.png)|__Recurrent Attentional Networks for Saliency Detection__|Jason Kuen, Zhenhua Wang, Gang Wang|__CVPR 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kuen_Recurrent_Attentional_Networks_CVPR_2016_paper.pdf)|
|9|![DS](data/DS.png)|__DeepSaliency: Multi-Task Deep Neural Network Model for Salient Object Detection__|Xi Li, Liming Zhao, Lina Wei, Ming-Hsuan Yang, Fei Wu, Yueting Zhuang, Haibin Ling, Jingdong Wang|__TIP 2016__|[`project page`](http://www.zhaoliming.net/research/deepsaliency)|
|10|![SSD-HS](data/SSD-HS.png)|__A Shape-Based Approach for Salient Object Detection Using Deep Learning__|[Jongpil Kim](http://www.research.cs.rutgers.edu/~jpkim/), Vladimir Pavlovic|__ECCV 2016__|[`paper`](http://www.research.cs.rutgers.edu/~jpkim/papers/jpkim_eccv2016.pdf) [`Pre-computed Maps`](http://www.research.cs.rutgers.edu/~jpkim/papers/resources/ssd_hs.tar.gz)|
|11|![RFCN](data/RFCN.png)|__Saliency Detection with Recurrent Fully Convolutional Networks__|Linzhao Wang, Lijun Wang, Huchuan Lu, Pingping Zhang, Xiang Ruan|__ECCV 2016__|[`paper`](https://www.researchgate.net/profile/Pingping_Zhang6/publication/308278832_Saliency_Detection_with_Recurrent_Fully_Convolutional_Networks/links/584b5da208aecb6bd8c157e0/Saliency-Detection-with-Recurrent-Fully-Convolutional-Networks.pdf) [`code`](https://drive.google.com/file/d/0B5rfGpkt3dDaODFRZ0ZXZjQyWDg/view)|
|12|![DSS](data/DSS.png)|__Deeply Supervised Salient Object Detection with Short Connections__|Qibin Hou, [Ming-Ming Cheng](http://mmcheng.net/cmm/), Xiaowei Hu, Ali Borji, [Zhuowen Tu](http://pages.ucsd.edu/~ztu/), Philip Torr|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.04849) [`github`](https://github.com/Andrew-Qibin/DSS) :star:|
|13|![NLDF](data/NLDF.png)|__Non-Local Deep Features for Salient Object Detection__|Zhiming Luo, Akshaya Mishra , Andrew Achkar , Justin Eichel , Shaozi Li , Pierre-Marc.Jodoin|__CVPR 2017__|[`project page`](https://sites.google.com/view/zhimingluo/nldf)|
|14|![MSRNet](data/MSRNet.png)|__Instance-Level Salient Object Segmentation__|[Guanbin Li](https://sites.google.com/site/ligb86/), Yuan Xie, Liang Lin, Yizhou Yu|__CVPR 2017__|[`paper`](https://arxiv.org/pdf/1704.03604.pdf)|
|15|![WSS](data/WSS.png)|__Learning to Detect Salient Objects with Image-level Supervision__|Lijun Wang, Huchuan Lu, Yifan Wang, Mengyang Feng, Dong Wang, Baocai Yin , Xiang Ruan|__CVPR 2017__|[`paper`](http://saliencydetection.net/duts/download/camera_ready.pdf) [`github`](https://github.com/scott89/WSS)|
|16|![DLS](data/DLS.png)|__Deep Level Sets for Salient Object Detection__|Ping Hu, Bing Shuai, Jun Liu, Gang Wang|__CVPR 2017__|[`paper`](http://openaccess.thecvf.com/content_cvpr_2017/papers/Hu_Deep_Level_Sets_CVPR_2017_paper.pdf)|
|17|![UCF](data/UCF.png)|__Learning Uncertain Convolutional Features for Accurate Saliency Detection__|Pingping Zhang, Dong Wang, Huchuan Lu, Hongyu Wang, Baocai Yin|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1708.02031) [`github`](https://github.com/Pchank/caffe-sal)|
|17|![Amulet](data/Amulet.png)|__Amulet: Aggregating Multi-level Convolutional Features for Salient Object Detection__|Pingping Zhang, Dong Wang, Huchuan Lu, Hongyu Wang, Xiang Ruan|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1708.02001) [`github`](https://github.com/Pchank/caffe-sal)|

### Visual Object Tracking
[Recommended Homepage---OTB Results. This shares results for more recent trackers.](https://github.com/foolwood/benchmark_results)

### Object Detection
|No. |Figure   |Title   |Authors  |Pub.  |Links|
|-----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![R-CNN](data/R-CNN.png)|__Rich feature hierarchies for accurate object detection and semantic segmentation__|Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik|__CVPR 2014__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf) [`github`](https://github.com/rbgirshick/rcnn) :star:|
|2|![Fast-R-CNN](data/Fast-R-CNN.png)|__Fast R-CNN__|Ross Girshick|__ICCV 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf) [`github`](https://github.com/rbgirshick/fast-rcnn) :star:|
|3|![Faster-R-CNN](data/Faster-R-CNN.png)|__Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks__|Shaoqing Ren, [Kaiming He](http://kaiminghe.com/), Ross Girshick, Jian Sun|__NIPS 2015__|[`paper`](http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf) [`matlab`](https://github.com/ShaoqingRen/faster_rcnn) [`python`](https://github.com/rbgirshick/py-faster-rcnn) [`pytorch`](https://github.com/longcw/faster_rcnn_pytorch) :star:|
|4|![CFM](data/CFM.png)|__Convolutional Feature Masking for Joint Object and Stuff Segmentation__|Jifeng Dai, [Kaiming He](http://kaiminghe.com/), Jian Sun|__CVPR 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Dai_Convolutional_Feature_Masking_2015_CVPR_paper.pdf)|
|5|![MNC](data/MNC.png)|__Instance-aware Semantic Segmentation via Multi-task Network Cascades__|Jifeng Dai, [Kaiming He](http://kaiminghe.com/), Jian Sun|__CVPR 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Dai_Instance-Aware_Semantic_Segmentation_CVPR_2016_paper.pdf) [`github`](https://github.com/daijifeng001/MNC) :star:|
|6|![Region-FCN](data/Region-FCN.png)|__R-FCN: Object Detection via Region-based Fully Convolutional Networks__|Jifeng Dai, Yi Li, [Kaiming He](http://kaiminghe.com/), Jian Sun|__NIPS 2016__|[`paper`](https://arxiv.org/abs/1605.06409) [`github`](https://github.com/daijifeng001/R-FCN)|
|7|![FPN](data/FPN.png)|__Feature Pyramid Networks for Object Detection__|Tsung-Yi Lin, Piotr Dollár, Ross Girshick, [Kaiming He](http://kaiminghe.com/), Bharath Hariharan, and Serge Belongie|__CVPR 2017__|[`paper`](https://arxiv.org/pdf/1612.03144.pdf)|
|8|![Mask-R-CNN](data/Mask-R-CNN.png)|__Mask R-CNN__|Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1703.06870) :star:|
|9|![A-Fast-R-CNN](data/A-Fast-R-CNN.png)|__A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection__|Xiaolong Wang, Abhinav Shrivastava, Abhinav Gupta|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.03414)  [`github`](https://github.com/xiaolonw/adversarial-frcnn) :star:|
|10|![MIDN](data/MIDN.png)|__Multiple Instance Detection Network with Online Instance Classifier Refinement__|Peng Tang, Xinggang Wang, Xiang Bai, Wenyu Liu|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.00138)|

### Object Localization
|No.  |Figure   |Title   |Authors  |Pub.  |Links|
|------|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![SDS](data/SDS.png)|__Simultaneous Detection and Segmentation__|Bharath Hariharan, Pablo Arbeláez, Ross Girshick, Jitendra Malik|__ECCV 2014__|[`paper`](https://arxiv.org/abs/1407.1808) :star:|
|2|![WSOL](data/WSOL.png)|__Deep Self-Taught Learning for Weakly Supervised Object Localization__|Zequn Jie, Yunchao Wei, Xiaojie Jin, Jiashi Feng, Wei Liu|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.05188)|
|3|![LDDP](data/LDDP.png)|__Learning Detection with Diverse Proposals__|Samaneh Azadi, Jiashi Feng, Trevor Darrell|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.03533)|
|4|![TPL](data/TPL.png)|__Two-Phase Learning for Weakly Supervised Object Localization__|Two-Phase Learning for Weakly Supervised Object Localization|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1708.02108)|

### Semantic Segmentation and Scene Parsing
|No.  |Figure   |Title   |Authors  |Pub.  |Links|
|--------|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![FCN](data/FCN.png)|__Fully Convolutional Networks for Semantic Segmentation__|Jonathan Long, Evan Shelhamer, Trevor Darrell|__CVPR 2015__|[`paper`](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) :star:|
|2|![LSOC](data/LSOC.png)|__Learning to Segment Object Candidates__|Pedro O. Pinheiro, Ronan Collobert, Piotr Dollar|__NIPS 2015__|[`paper`](http://papers.nips.cc/paper/5852-learning-to-segment-object-candidates.pdf)|
|3|![LROS](data/LROS.png)|__Learning to Refine Object Segments__|Pedro O. Pinheiro , Tsung-Yi Lin , Ronan Collobert, Piotr Doll ́ar|__arXiv 1603.08695__|[`paper`](https://arxiv.org/pdf/1603.08695.pdf)|
|4|![CRFRNN](data/CRFRNN.png)|__Conditional Random Fields as Recurrent Neural Networks__|Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet, ZhiZhong Su, Dalong Du, Chang Huang, and Philip H. S. Torr|__ICCV 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zheng_Conditional_Random_Fields_ICCV_2015_paper.html)|
|5|![LDN](data/LDN.png)|__Learning Deconvolution Network for Semantic Segmentation__|Heonwoo Noh, Seunghoon Hong, Bohyung Han|__ICCV 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Noh_Learning_Deconvolution_Network_ICCV_2015_paper.html)|
|6|![ISFCN](data/ISFCN.png)|__Instance-sensitive Fully Convolutional Networks__|Jifeng Dai, Kaiming He, Yi Li, Shaoqing Ren, Jian Sun|__ECCV 2016__|[`paper`](https://arxiv.org/abs/1603.08678)|
|7|![LPRR](data/LPRR.png)|__Laplacian Pyramid Reconstruction and Refinement for Semantic Segmentation__|Golnaz Ghiasi, Charless C. Fowlkes|__ECCV 2016__|[`paper`](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_32)  [`github`](https://github.com/golnazghiasi/LRR)|
|8|![SSIS](data/SSIS.png)|__Attention to Scale: Scale-aware Semantic Image Segmentation__|Liang-Chieh Chen, Yi Yang, Jiang Wang, Wei Xu, Alan L. Yuille|__CVPR 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Chen_Attention_to_Scale_CVPR_2016_paper.html)|
|9|![Not-All-Pixels-Are-Equal](data/Not-All-Pixels-Are-Equal.png)|__Not All Pixels Are Equal: Difficulty-Aware Semantic Segmentation via Deep Layer Cascade__|Xiaoxiao Li, Ziwei Liu, Ping Luo, Chen Change Loy, Xiaoou Tang|__CVPR 2016__|[`paper`](https://arxiv.org/abs/1704.01344)|
|10|![RefineNet](data/RefineNet.png)|__RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation__|Guosheng Lin, Anton Milan, Chunhua Shen, Ian Reid|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.06612)  [`github`](https://github.com/guosheng/refinenet)|
|11|![PSPNet](data/PSPNet.png)|__Pyramid Scene Parsing Network__|Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, Jiaya Jia|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1612.01105)  [`github`](https://github.com/hszhao/PSPNet)|
|12|![DRN](data/DRN.png)|__Dilated Residual Networks__|Fisher Yu, Vladlen Koltun, Thomas Funkhouser|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1705.09914)|
|13|![FCIS](data/FCIS.png)|__Fully Convolutional Instance-aware Semantic Segmentation__|Yi Li, Haozhi Qi, Jifeng Dai, Xiangyang Ji, Yichen Wei|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.07709) [`github`](https://github.com/msracver/FCIS)|
|14|![FRRN](data/FRRN.png)|__Full-Resolution Residual Networks for Semantic Segmentation in Street Scenes__|Tobias Pohlen, Alexander Hermans, Markus Mathias, Bastian Leibe|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.08323)|
|15|![A-Erasing](data/A-Erasing.png)|__Object Region Mining with Adversarial Erasing: A Simple Classification toSemantic Segmentation Approach__|Yunchao Wei, Jiashi Feng, Xiaodan Liang, Ming-Ming Cheng, Yao Zhao, Shuicheng Yan|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1703.08448) :star:|

### Edge Detection
|No. |Figure   |Title   |Authors  |Pub.  |Links|
|-----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![HED](data/HED.png)|__Holistically-Nested Edge Detection__|Saining Xie, Zhuowen Tu|__ICCV 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Xie_Holistically-Nested_Edge_Detection_ICCV_2015_paper.pdf) [`github`](https://github.com/s9xie/hed) :star:|
|2|![RCF](data/RCF.png)|__Richer Convolutional Features for Edge Detection__|Yun Liu, Ming-Ming Cheng, Xiaowei Hu, Kai Wang, Xiang Bai|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1612.02103)|
|3|![CASENet](data/CASENet.png)|__CASENet: Deep Category-Aware Semantic Edge Detection__|Zhiding Yu, Chen Feng, Ming-Yu Liu, Srikumar Ramalingam|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1705.09759)|

### Pose Estimation
|No. |Figure   |Title   |Authors  |Pub.  |Links|
|----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![Hourglass](data/Hourglass.png)|__Stacked Hourglass Networks for Human Pose Estimation__|Alejandro Newell, Kaiyu Yang, and Jia Deng|__ECCV 2016__|[`paper`](https://arxiv.org/abs/1603.06937) :star:|
|2|![MCA](data/MCA.png)|__Multi-Context Attention for Human Pose Estimation__|[Xiao Chu](http://www.ee.cuhk.edu.hk/~xchu/), Wei Yang, [Wanli Ouyang](http://www.ee.cuhk.edu.hk/~wlouyang/), Cheng Ma, Alan L. Yuille, [Xiaogang Wang](http://www.ee.cuhk.edu.hk/~xgwang/)|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1702.07432) [`github`](https://github.com/bearpaw/pose-attention)|

### Super Resolution
|No. |Figure   |Title   |Authors  |Pub.  |Links|
|------|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![LapSRN](data/LapSRN.png)|__Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution__|Wei-Sheng Lai, Jia-Bin Huang, Narendra Ahuja, Ming-Hsuan Yang|__CVPR 2017__|[`project page`](http://vllab1.ucmerced.edu/~wlai24/LapSRN/)|
|2|![DRRN](data/DRRN.png)|__Image Super-Resolution via Deep Recursive Residual Network__|Ying Tai, Jian Yang, and Xiaoming Liu|__CVPR 2017__|[`paper`](https://www.researchgate.net/profile/Xiaoming_Liu8/publication/316017318_Image_Super-Resolution_via_Deep_Recursive_Residual_Network/links/58eda40b0f7e9b37ed14f5d7/Image-Super-Resolution-via-Deep-Recursive-Residual-Network.pdf) [`github`](https://github.com/tyshiwo/DRRN_CVPR17)|

### Image Classification
|No. |Figure   |Title   |Authors  |Pub.  |Links|
|-----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![GoogLeNet](data/GoogLeNet.png)|__Going Deeper with Convolutions__|Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed|__CVPR 2015__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Szegedy_Going_Deeper_With_2015_CVPR_paper.html) :star:|
|2|![ResNet](data/ResNet.png)|__Deep Residual Learning for Image Recognition__|Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun|__CVPR 2016__ *`best`*|[`paper`](https://arxiv.org/abs/1512.03385) [`github`](https://github.com/KaimingHe/deep-residual-networks) :star:|
|3|![Res-Attention-Network](data/Res-Attention-Network.png)|__Residual Attention Network for Image Classification__|Fei Wang, Mengqing Jiang, Chen Qian, Shuo Yang, Cheng Li, Honggang Zhang, Xiaogang Wang, Xiaoou Tang|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.06904) [`github`](https://github.com/buptwangfei/residual-attention-network) :star:|
|4|![ResNeXt](data/ResNeXt.png)|__Aggregated Residual Transformations for Deep Neural Networks__|Saining Xie, Ross Girshick, Piotr Dollár, Zhuowen Tu, and Kaiming He|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.05431) [`github`](https://github.com/facebookresearch/ResNeXt)|
|5|![DenseNet](data/DenseNet.png)|__Densely Connected Convolutional Networks__|Gao Huang, Zhuang Liu, Kilian Q. Weinberger|__CVPR 2017__ *`best`*|[`paper`](https://arxiv.org/abs/1608.06993) [`github`](https://github.com/liuzhuang13/DenseNet) :star:|
|6|![PyramidNet](data/PyramidNet.png)|__Deep Pyramidal Residual Networks__|Dongyoon Han, Jiwhan Kim, Junmo Kim|__CVPR 2017__|[`paper`](https://arxiv.org/pdf/1610.02915.pdf) [`github`](https://github.com/jhkim89/PyramidNet) :star:|

### Others
|No.   |Figure   |Title   |Authors  |Pub.  |Links|
|-----|:-----:|:-----:|:-----:|:-----:|:---:|
|1|![FSDSO](data/FSDSO.png)|__Object Skeleton Extraction in Natural Images by Fusing Scale-associated Deep Side Outputs__|Wei Shen, Kai Zhao, Yuan Jiang, Yan Wang, Zhijiang Zhang, Xiang Bai|__ICCV 2016__|[`paper`](http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Shen_Object_Skeleton_Extraction_CVPR_2016_paper.html) [`github`](https://github.com/zeakey/DeepSkeleton)|
|2|![AnchorNet](data/AnchorNet.png)|__AnchorNet: A Weakly Supervised Network to Learn Geometry-sensitive Features For Semantic Matching__|David Novotny, DianeLarlus, Andrea Vedaldi|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.04749)|
|3|![SRN](data/SRN.png)|__SRN：Side-output Residual Network for Object Symmetry Detection in the Wild__|Wei Ke, Jie Chen, Jianbin Jiao, Guoying Zhao and Qixiang Ye|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1703.02243) [`github`](https://github.com/KevinKecc/SRN) :star:|
|4|![QAN](data/QAN.png)|__Quality Aware Network for Set to Set Recognition__|Yu Liu, Junjie Yan, Wanli Ouyang|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.03373)|
|5|![Continuous-CRFs](data/Continuous-CRFs.png)|__Multi-Scale Continuous CRFs as Sequential Deep Networks for Monocular Depth Estimation__|Dan Xu, Elisa Ricci, Wanli Ouyang, Xiaogang Wang, Nicu Sebe|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.02157) [`github`](https://github.com/danxuhk/ContinuousCRF-CNN) :star:|
|6|![CMT](data/CMT.png)|__Learning Cross-Modal Deep Representations for Robust Pedestrian Detection__|Dan Xu, Wanli Ouyang, Elisa Ricci, Xiaogang Wang, Nicu Sebe|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.02431)|
|7|![SS-DMP](data/SS-DMP.png)|__Semi-Supervised Deep Learning for Monocular Depth Map Prediction__|Yevhen Kuznietsov, Jörg Stückler, Bastian Leibe|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1702.02706)|
|8|![DRNet](data/DRNet.png)|__Detecting Visual Relationships with Deep Relational Networks__|Bo Dai, Yuqi Zhang, Dahua Lin|__CVPR 2017__|[`paper`](https://arxiv.org/pdf/1704.03114.pdf) [`github`](https://github.com/doubledaibo/drnet)|
|9|![Polygon-RNN](data/Polygon-RNN.png)|__Annotating Object Instances with a Polygon-RNN__|Lluis Castrejon, Kaustav Kundu, Raquel Urtasun, Sanja Fidler|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1704.05548) :star:|
|10|![WCCN](data/WCCN.png)|__Weakly Supervised Cascaded Convolutional Networks__|Ali Diba, Vivek Sharma, Ali Pazandeh, Hamed Pirsiavash, Luc Van Gool|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1611.08258)|
|11|![GRU](data/GRU.png)|__Full Resolution Image Compression with Recurrent Neural Networks__|George Toderici, Damien Vincent, Nick Johnston, Sung Jin Hwang, David Minnen, Joel Shor, Michele Covell|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1608.05148) [`github`](https://github.com/tensorflow/models/tree/master/compression)|
|12|![FSOR](data/FSOR.png)|__Few-Shot Object Recognition from Machine-Labeled Web Images__|Zhongwen Xu, Linchao Zhu, Yi Yang|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1612.06152)|
|13|![UberNet](data/UberNet.png)|__UberNet: Training a `Universal' Convolutional Neural Network for Low-, Mid-, and High-Level Vision using Diverse Datasets and Limited Memory__|Iasonas Kokkinos|__CVPR 2017__|[`paper`](https://arxiv.org/abs/1609.02132) [`code`](http://cvn.ecp.fr/ubernet/)|
|14|![CP-CNN](data/CP-CNN.png)|__Generating High-Quality Crowd Density Maps using Contextual Pyramid CNNs__|Vishwanath A. Sindagi and Vishal M. Patel|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1708.00953)|
|15|![MemNet](data/MemNet.png)|__MemNet: A Persistent Memory Network for Image Restoration__| Ying Tai, Jian Yang, Xiaoming Liu, Chunyan Xu|__ICCV 2017__|[`paper`](https://arxiv.org/abs/1708.02209)|
