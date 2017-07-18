# Recommended Papers
- The goal of this document is to provide a reading list for Deep Learning in Computer Vision Field.
## Topics
- [Salient Object Detection](#salient-object-detection)
- [Visual Object Tracking](#visual-object-tracking)
- [Object Detection](#object-detection)
- [Object Localization](#object-localization)
- [Semantic Segmentation & Scene Parsing](#semantic-segmentation-scene-parsing)
- [Edge Detection](#edge-detection)
- [Pose Estimation](#pose-estimation)
- [Semantic Matching](#semantic-matching)
- [Super Resolution](#super-resolution)
- [Image Classification](#image-classification)
- [Others](#others)
## Papers
Paper list.
### Salient Object Detection

<table>
    <thead>
        <tr>
            <th>Figure</th>
            <th>Title</th>
            <th>Author</th>
            <th>Pub.</th>
            <th>Links</th>
        </tr>
        
        <tr>
            <th><img src="data/MDF.png"  alt="MDF" align=center /></th>
            <th>Visual Saliency Based on Multiscale Deep Features</th>
            <th><a href="https://sites.google.com/site/ligb86/">Guanbin Li</a>, Yizhou Yu</th>
            <th>CVPR 2015</th>
            <th><a href="https://sites.google.com/site/ligb86/mdfsaliency/">project page</a></th>
        </tr>
        
        <tr>
            <th><img src="data/MCDL.png"  alt="MCDL" align=center /></th>
            <th>Saliency Detection by Multi-context Deep Learning</th>
            <th><a href="http://www.ee.cuhk.edu.hk/~rzhao/">Rui Zhao</a>, Wanli Ouyang, Hongsheng Li, Xiaogang Wang</th>
            <th>CVPR 2015</th>
            <th><a href="http://www.ee.cuhk.edu.hk/~rzhao/project/deepsal_cvpr15/zhaoOLWcvpr15.pdf">paper</a>  <a href="https://github.com/Robert0812/deepsaldet">code</a></th>
        </tr>
        
    </thead>
</table>

	

	
- __Deep Networks for Saliency Detection via Local Estimation and Global Search__

	![legs](data/LEGS.png)
	
	- Lijun Wang, Huchuan Lu, Xiang Ruan, Ming-Hsuan Yang, *__CVPR 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Deep_Networks_for_2015_CVPR_paper.pdf)
	
- __DHSNet: Deep Hierarchical Saliency Network for Salient Object Detection__

	![dhs](data/DHS.png)
	
	- [Nian Liu](https://sites.google.com/site/liunian228/), Junwei Han, CVPR 2016. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DHSNet_Deep_Hierarchical_CVPR_2016_paper.pdf) [code: [googel drive](https://drive.google.com/file/d/0B1sbejbIJIW3RlJJY1NNNkFydEU/view) [baidu yun](http://pan.baidu.com/s/1jIm8cfk)]
	
	
- __Deep Contrast Learning for Salient Object Detection__

	![dcl](data/DCL.png)
	
	- [Guanbin Li](https://sites.google.com/site/ligb86/), Yizhou Yu, *__CVPR 2016__*. [[project page]](http://i.cs.hku.hk/~gbli/deep_saliency.html)
	
	
- __Saliency Unified: A Deep Architecture for Simultaneous Eye Fixation Prediction and Salient Object Segmentation__

	![su](data/SU.png)
	
	- Srinivas S S Kruthiventi, Vennela Gudisa, Jaley H Dholakiya and R. Venkatesh Babu, *__CVPR 2016__*. [[project page]](http://val.serc.iisc.ernet.in/saliency-unified/)
	
	
- __Deep Saliency with Encoded Low level Distance Map and High Level Features__

	![eld](data/ELD.png)
	
	- Gayoung Lee, Yu-Wing Tai, Junmo Kim, *__CVPR 2016__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lee_Deep_Saliency_With_CVPR_2016_paper.pdf) [[code]](https://github.com/gylee1103/SaliencyELD)
	
	
- __Recurrent Attentional Networks for Saliency Detection__

	![ran](data/RAN.png)
	
	- Jason Kuen, Zhenhua Wang, Gang Wang, *__CVPR 2016__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kuen_Recurrent_Attentional_Networks_CVPR_2016_paper.pdf)
	
	
- __DeepSaliency: Multi-Task Deep Neural Network Model for Salient Object Detection__

	![ds](data/DS.png)
	
	- Xi Li, Liming Zhao, Lina Wei, Ming-Hsuan Yang, Fei Wu, Yueting Zhuang, Haibin Ling, Jingdong Wang, *__TIP 2016__*. [[project page]](http://www.zhaoliming.net/research/deepsaliency)
	
	
- __A Shape-Based Approach for Salient Object Detection Using Deep Learning__

	![ssd-hs](data/SSD-HS.png)
	
	- [Jongpil Kim](http://www.research.cs.rutgers.edu/~jpkim/) and Vladimir Pavlovic, *__ECCV 2016__*. [[paper]](http://www.research.cs.rutgers.edu/~jpkim/papers/jpkim_eccv2016.pdf) [[Pre-computed Maps]](http://www.research.cs.rutgers.edu/~jpkim/papers/resources/ssd_hs.tar.gz)
	
	
- __Saliency Detection with Recurrent Fully Convolutional Networks__

	![rfcn](data/RFCN.png)
	
	- Linzhao Wang, Lijun Wang, Huchuan Lu, Pingping Zhang, Xiang Ruan, *__ECCV 2016__*. [[paper]](https://www.researchgate.net/profile/Pingping_Zhang6/publication/308278832_Saliency_Detection_with_Recurrent_Fully_Convolutional_Networks/links/584b5da208aecb6bd8c157e0/Saliency-Detection-with-Recurrent-Fully-Convolutional-Networks.pdf)
	
	
- __Deeply Supervised Salient Object Detection with Short Connections__

	![dss](data/DSS.png)
	
	- Qibin Hou, [Ming-Ming Cheng](http://mmcheng.net/cmm/), Xiaowei Hu, Ali Borji, [Zhuowen Tu](http://pages.ucsd.edu/~ztu/), Philip Torr, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1611.04849) [[git-hub]](https://github.com/Andrew-Qibin/DSS)
	
	
- __Non-Local Deep Features for Salient Object Detection__

	![nldf](data/NLDF.png)
	
	- Zhiming Luo, Akshaya Mishra , Andrew Achkar , Justin Eichel , Shaozi Li , Pierre-Marc.Jodoin, *__CVPR 2017__*. [[project page]](https://sites.google.com/view/zhimingluo/nldf)
	
	
- __Instance-Level Salient Object Segmentation__

	![msrnet](data/MSRNet.png)
	
	- [Guanbin Li](https://sites.google.com/site/ligb86/), Yuan Xie, Liang Lin, Yizhou Yu, *__CVPR 2017__*. [[paper]](https://arxiv.org/pdf/1704.03604.pdf)
	
	
- __Learning to Detect Salient Objects with Image-level Supervision__

	![wss](data/WSS.png)
	
	- Lijun Wang, Huchuan Lu, Yifan Wang, Mengyang Feng, Dong Wang, Baocai Yin , and Xiang Ruan, *__CVPR 2017__*. [[paper]](http://saliencydetection.net/duts/download/camera_ready.pdf)

### Visual Object Tracking
[Recommended Homepage---OTB Results. This shares results for more recent trackers.](https://github.com/foolwood/benchmark_results)
	
### Object Detection
- __Rich feature hierarchies for accurate object detection and semantic segmentation__

	![r-cnn](data/R-CNN.png)

	- Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik, *__CVPR 2014__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf) [[git-hub]](https://github.com/rbgirshick/rcnn)
	
	
- __Fast R-CNN__

	![fast r-cnn](data/Fast-R-CNN.png)

	- Ross Girshick, *__ICCV 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf) [[git-hub]](https://github.com/rbgirshick/fast-rcnn)
	
	
- __Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks__

	![faster r-cnn](data/Faster-R-CNN.png)

	- Shaoqing Ren, [Kaiming He](http://kaiminghe.com/), Ross Girshick, Jian Sun, *__NIPS 2015__*. [[paper]](http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf) [[matlab]](https://github.com/ShaoqingRen/faster_rcnn) [[python]](https://github.com/rbgirshick/py-faster-rcnn)
	
	
- __Convolutional Feature Masking for Joint Object and Stuff Segmentation__

	![cfm](data/CFM.png)

	- Jifeng Dai, [Kaiming He](http://kaiminghe.com/), Jian Sun, *__CVPR 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Dai_Convolutional_Feature_Masking_2015_CVPR_paper.pdf)
	
	
- __Instance-aware Semantic Segmentation via Multi-task Network Cascades__

	![mnc](data/MNC.png)	
	
	- Jifeng Dai, [Kaiming He](http://kaiminghe.com/), Jian Sun, *__CVPR 2016__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Dai_Instance-Aware_Semantic_Segmentation_CVPR_2016_paper.pdf) [[git-hub]](https://github.com/daijifeng001/MNC)
	
	
- __R-FCN: Object Detection via Region-based Fully Convolutional Networks__

	![region-fcn](data/Region-FCN.png)

	- Jifeng Dai, Yi Li,  [Kaiming He](http://kaiminghe.com/), Jian Sun, *__NIPS 2016__*. [[paper]](https://arxiv.org/abs/1605.06409) [[git-hub]](https://github.com/daijifeng001/R-FCN)
	
	
- __Feature Pyramid Networks for Object Detection__

	![fpn](data/FPN.png)

	- Tsung-Yi Lin, Piotr Dollár, Ross Girshick, [Kaiming He](http://kaiminghe.com/), Bharath Hariharan, and Serge Belongie, *__CVPR 2017__*. [[paper]](https://arxiv.org/pdf/1612.03144.pdf)
	
	
- __Mask R-CNN__

	![mask r-cnn](data/Mask-R-CNN.png)

	- Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick, *__Tech Report__*. [[paper]](https://arxiv.org/abs/1703.06870)
	
	
- __A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection__

	![a-fast-r-cnn](data/A-Fast-R-CNN.png)

	- Xiaolong Wang, Abhinav Shrivastava, Abhinav Gupta, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.03414) [[git-hub]](https://github.com/xiaolonw/adversarial-frcnn)
	
	
- __Multiple Instance Detection Network with Online Instance Classifier Refinement__

	![midn](data/MIDN.png)

	- Peng Tang, Xinggang Wang, Xiang Bai, Wenyu Liu, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.00138)
	
	
### Object Localization

- __Simultaneous Detection and Segmentation__

	![sds](data/SDS.png)

	- Bharath Hariharan, Pablo Arbeláez, Ross Girshick, Jitendra Malik, *__ECCV 2014__*. [[paper]](https://arxiv.org/abs/1407.1808)
	
	
- __Deep Self-Taught Learning for Weakly Supervised Object Localization__

	![wsol](data/WSOL.png)

	- Zequn Jie, Yunchao Wei, Xiaojie Jin, Jiashi Feng, Wei Liu, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.05188)
	
	
- __Learning Detection with Diverse Proposals__

	![lddp](data/LDDP.png)

	- Samaneh Azadi, Jiashi Feng, Trevor Darrell, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.03533)
	

### Semantic Segmentation & Scene Parsing

- __Fully Convolutional Networks for Semantic Segmentation__

	![fcn](data/FCN.png)

	- Jonathan Long, Evan Shelhamer, Trevor Darrell, *__CVPR 2015__*. [[paper]](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)
	
	
- __Learning to Segment Object Candidates__

	![lsoc](data/LSOC.png)

	- Pedro O. Pinheiro, Ronan Collobert, Piotr Dollar, *__NIPS 2015__*. [[paper]](http://papers.nips.cc/paper/5852-learning-to-segment-object-candidates.pdf)
	
	
- __Learning to Refine Object Segments__

	![lros](data/LROS.png)

	- Pedro O. Pinheiro , Tsung-Yi Lin , Ronan Collobert, Piotr Doll ́ar, *__arXiv 1603.08695__*. [[paper]](https://arxiv.org/pdf/1603.08695.pdf)
	

- __Conditional Random Fields as Recurrent Neural Networks__

	![crfrnn](data/CRFRNN.png)
	
	- Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet, ZhiZhong Su, Dalong Du, Chang Huang, and Philip H. S. Torr, *__ICCV 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zheng_Conditional_Random_Fields_ICCV_2015_paper.html)


- __Learning Deconvolution Network for Semantic Segmentation__

	![ldn](data/LDN.png)
	
	- Heonwoo Noh, Seunghoon Hong, Bohyung Han, *__ICCV 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Noh_Learning_Deconvolution_Network_ICCV_2015_paper.html)
	
	
- __Instance-sensitive Fully Convolutional Networks__

	![isfcn](data/ISFCN.png)

	- Jifeng Dai, Kaiming He, Yi Li, Shaoqing Ren, Jian Sun, *__arXiv 1603.08678__*. [[paper]](https://arxiv.org/abs/1603.08678) 
	

- __Attention to Scale: Scale-aware Semantic Image Segmentation__

	![ssis](data/SSIS.png)
	
	- Liang-Chieh Chen, Yi Yang, Jiang Wang, Wei Xu, Alan L. Yuille, *__CVPR 2016__*. [[paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Chen_Attention_to_Scale_CVPR_2016_paper.html)
	
- __Not All Pixels Are Equal: Difficulty-Aware Semantic Segmentation via Deep Layer Cascade__

	![not all pixels are equal](data/Not-All-Pixels-Are-Equal.png)

	- Xiaoxiao Li, Ziwei Liu, Ping Luo, Chen Change Loy, Xiaoou Tang, *__CVPR 2016__*. [[paper]](https://arxiv.org/abs/1704.01344)
	
	
- __RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation__

	![refinenet](data/RefineNet.png)

	- Guosheng Lin, Anton Milan, Chunhua Shen, Ian Reid, *__arXiv 1611.06612__*. [[paper]](https://arxiv.org/abs/1611.06612)
	
	
- __Pyramid Scene Parsing Network__

	![pspnet](data/PSPNet.png)

	- Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, Jiaya Jia, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1612.01105) [[git-hub]](https://github.com/hszhao/PSPNet)
	

- __Dilated Residual Networks__

	![drn](data/DRN.png)
	
	- Fisher Yu, Vladlen Koltun, Thomas Funkhouser, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1705.09914)
	
- __Fully Convolutional Instance-aware Semantic Segmentation__

	![fcis](data/FCIS.png)

	- Yi Li, Haozhi Qi, Jifeng Dai, Xiangyang Ji, Yichen Wei, *___CVPR 2017__*. [[paper]](https://arxiv.org/abs/1611.07709) [[git-hub]](https://github.com/msracver/FCIS)
	
	
### Edge Detection

- __Holistically-Nested Edge Detection__

	![hed](data/HED.png)

	- Saining Xie, Zhuowen Tu, *__ICCV 2015__*. [[paper]](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Xie_Holistically-Nested_Edge_Detection_ICCV_2015_paper.pdf)
	
	
- __Richer Convolutional Features for Edge Detection__

	![rcf](data/RCF.png)

	- Yun Liu, Ming-Ming Cheng, Xiaowei Hu, Kai Wang, Xiang Bai, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1612.02103)
	

- __CASENet: Deep Category-Aware Semantic Edge Detection__

	![casenet](data/CASENet.png)
	
	- Zhiding Yu, Chen Feng, Ming-Yu Liu, Srikumar Ramalingam, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1705.09759)
	
### Pose Estimation

- __Stacked Hourglass Networks for Human Pose Estimation__

	![hourglass](data/Hourglass.png)

	- Alejandro Newell, Kaiyu Yang, and Jia Deng, *__ECCV 2016__*. [[paper]](https://arxiv.org/abs/1603.06937)
	
	
- __Multi-Context Attention for Human Pose Estimation__

	![mca](data/MCA.png)

	- [Xiao Chu](http://www.ee.cuhk.edu.hk/~xchu/), Wei Yang, [Wanli Ouyang](http://www.ee.cuhk.edu.hk/~wlouyang/), Cheng Ma, Alan L. Yuille, [Xiaogang Wang](http://www.ee.cuhk.edu.hk/~xgwang/), *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1702.07432) [[git-hub]](https://github.com/bearpaw/pose-attention)
	

### Semantic Matching

- __AnchorNet: A Weakly Supervised Network to Learn Geometry-sensitive Features For Semantic Matching__

	![anchornet](data/AnchorNet.png)
	
	- David Novotny, DianeLarlus, Andrea Vedaldi, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.04749)
	
### Super Resolution

- __Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution__

	![lapsrn](data/LapSRN.png)

	- Wei-Sheng Lai, Jia-Bin Huang, Narendra Ahuja, Ming-Hsuan Yang, *__CVPR 2017__*. [[project page]](http://vllab1.ucmerced.edu/~wlai24/LapSRN/)

### Image Classification

- __Deep Residual Learning for Image Recognition__

	![resnet](data/ResNet.png)

	- Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun, *__CVPR 2015__*. [[paper]](https://arxiv.org/abs/1512.03385) [[git-hub]](https://github.com/KaimingHe/deep-residual-networks)
	
	
- __Residual Attention Network for Image Classification__

	![res-attention-network](data/Res-Attention-Network.png)

	- Fei Wang, Mengqing Jiang, Chen Qian, Shuo Yang, Cheng Li, Honggang Zhang, Xiaogang Wang, Xiaoou Tang, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.06904)
	
	
- __Aggregated Residual Transformations for Deep Neural Networks__

	![resnext](data/ResNeXt.png)

	- Saining Xie, Ross Girshick, Piotr Dollár, Zhuowen Tu, and Kaiming He, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1611.05431) [[git-hub]](https://github.com/facebookresearch/ResNeXt)

	
### Others
- __SRN：Side-output Residual Network for Object Symmetry Detection in the Wild__

	![srn](data/SRN.png)
	
	- Wei Ke, Jie Chen, Jianbin Jiao, Guoying Zhao and Qixiang Ye, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1703.02243)
	
- __Quality Aware Network for Set to Set Recognition__

	![qan](data/QAN.png)

	- Yu Liu, Junjie Yan, Wanli Ouyang, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.03373)
	
- __Multi-Scale Continuous CRFs as Sequential Deep Networks for Monocular Depth Estimation__

	![continuous crfs](data/Continuous-CRFs.png)
	
	- Dan Xu, Elisa Ricci, Wanli Ouyang, Xiaogang Wang, Nicu Sebe, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.02157)
	
- __Learning Cross-Modal Deep Representations for Robust Pedestrian Detection__

	![cmt](data/CMT.png)
	
	- Dan Xu, Wanli Ouyang, Elisa Ricci, Xiaogang Wang, Nicu Sebe, *__CVPR 2017__*. [[paper]](https://arxiv.org/abs/1704.02431)
