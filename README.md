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
        <tr>
            <th><img src="data/LEGS.png"  alt="LEGS" align=center /></th>
            <th>Deep Networks for Saliency Detection via Local Estimation and Global Search</th>
            <th>Lijun Wang, Huchuan Lu, Xiang Ruan, Ming-Hsuan Yang</th>
            <th>CVPR 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Deep_Networks_for_2015_CVPR_paper.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/DHS.png"  alt="DHS" align=center /></th>
            <th>DHSNet: Deep Hierarchical Saliency Network for Salient Object Detection</th>
            <th><a href="https://sites.google.com/site/liunian228/">Nian Liu, Junwei Han</th>
            <th>CVPR 2016</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DHSNet_Deep_Hierarchical_CVPR_2016_paper.pdf">paper</a>  [code: <a href="https://drive.google.com/file/d/0B1sbejbIJIW3RlJJY1NNNkFydEU/view">google drive</a> <a href="http://pan.baidu.com/s/1jIm8cfk">baidu yun</a></th>
        </tr>
        <tr>
            <th><img src="data/DCL.png"  alt="DCL" align=center /></th>
            <th>Deep Contrast Learning for Salient Object Detection</th>
            <th><a href="https://sites.google.com/site/ligb86/">Guanbin Li</a>, Yizhou Yu</th>
            <th>CVPR 2016</th>
            <th><a href="http://i.cs.hku.hk/~gbli/deep_saliency.html">project page</a></th>
        </tr> 
        <tr>
            <th><img src="data/SU.png"  alt="SU" align=center /></th>
            <th>Saliency Unified: A Deep Architecture for Simultaneous Eye Fixation Prediction and Salient Object Segmentation</th>
            <th>Srinivas S S Kruthiventi, Vennela Gudisa, Jaley H Dholakiya and R. Venkatesh Babu</th>
            <th>CVPR 2016</th>
            <th><a href="http://val.serc.iisc.ernet.in/saliency-unified/">project page</a></th>
        </tr>
        <tr>
            <th><img src="data/ELD.png"  alt="ELD" align=center /></th>
            <th>Deep Saliency with Encoded Low level Distance Map and High Level Features</th>
            <th>Gayoung Lee, Yu-Wing Tai, Junmo Kim</th>
            <th>CVPR 2016</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lee_Deep_Saliency_With_CVPR_2016_paper.pdf">paper</a>  <a href="https://github.com/gylee1103/SaliencyELD">code</a></th>
        </tr>
        <tr>
            <th><img src="data/RAN.png"  alt="RAN" align=center /></th>
            <th>Recurrent Attentional Networks for Saliency Detection</th>
            <th>Jason Kuen, Zhenhua Wang, Gang Wang</th>
            <th>CVPR 2016</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kuen_Recurrent_Attentional_Networks_CVPR_2016_paper.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/DS.png"  alt="DS" align=center /></th>
            <th>DeepSaliency: Multi-Task Deep Neural Network Model for Salient Object Detection</th>
            <th>Xi Li, Liming Zhao, Lina Wei, Ming-Hsuan Yang, Fei Wu, Yueting Zhuang, Haibin Ling, Jingdong Wang</th>
            <th>TIP 2016</th>
            <th><a href="http://www.zhaoliming.net/research/deepsaliency">project page</a></th>
        </tr>
        <tr>
            <th><img src="data/SSD-HS.png"  alt="SSD-HS" align=center /></th>
            <th>A Shape-Based Approach for Salient Object Detection Using Deep Learning</th>
            <th><a href="http://www.research.cs.rutgers.edu/~jpkim/">Jongpil Kim</a>, Vladimir Pavlovic</th>
            <th>ECCV 2016</th>
            <th><a href="http://www.research.cs.rutgers.edu/~jpkim/papers/jpkim_eccv2016.pdf">paper</a>  <a href="http://www.research.cs.rutgers.edu/~jpkim/papers/resources/ssd_hs.tar.gz">Pre-computed Maps</a> </th>
        </tr>
        <tr>
            <th><img src="data/RFCN.png"  alt="RFCN" align=center /></th>
            <th>Saliency Detection with Recurrent Fully Convolutional Networks</th>
            <th>Linzhao Wang, Lijun Wang, Huchuan Lu, Pingping Zhang, Xiang Ruan</th>
            <th>ECCV 2016</th>
            <th><a href="https://www.researchgate.net/profile/Pingping_Zhang6/publication/308278832_Saliency_Detection_with_Recurrent_Fully_Convolutional_Networks/links/584b5da208aecb6bd8c157e0/Saliency-Detection-with-Recurrent-Fully-Convolutional-Networks.pdf">paper</a> <a href="https://drive.google.com/file/d/0B5rfGpkt3dDaODFRZ0ZXZjQyWDg/view">code</a></th>
        </tr>
        <tr>
            <th><img src="data/DSS.png"  alt="DSS" align=center /></th>
            <th>Deeply Supervised Salient Object Detection with Short Connections</th>
            <th>Qibin Hou, <a href="http://mmcheng.net/cmm/">Ming-Ming Cheng</a>, Xiaowei Hu, Ali Borji, <a href="http://pages.ucsd.edu/~ztu/">Zhuowen Tu</a>, Philip Torr</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1611.04849">paper</a> <a href="https://github.com/Andrew-Qibin/DSS">github</a></th>
        </tr>   
        <tr>
            <th><img src="data/NLDF.png"  alt="NLDF" align=center /></th>
            <th>Non-Local Deep Features for Salient Object Detection</th>
            <th>Zhiming Luo, Akshaya Mishra , Andrew Achkar , Justin Eichel , Shaozi Li , Pierre-Marc.Jodoin</th>
            <th>CVPR 2017</th>
            <th><a href="https://sites.google.com/view/zhimingluo/nldf">project page</a></th>
        </tr> 
        <tr>
            <th><img src="data/MSRNet.png"  alt="MSRNet" align=center /></th>
            <th>Instance-Level Salient Object Segmentation</th>
            <th><a href="https://sites.google.com/site/ligb86/">Guanbin Li</a>, Yuan Xie, Liang Lin, Yizhou Yu</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/pdf/1704.03604.pdf">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/WSS.png"  alt="WSS" align=center /></th>
            <th>Learning to Detect Salient Objects with Image-level Supervision</th>
            <th>Lijun Wang, Huchuan Lu, Yifan Wang, Mengyang Feng, Dong Wang, Baocai Yin , Xiang Ruan</th>
            <th>CVPR 2017</th>
            <th><a href="http://saliencydetection.net/duts/download/camera_ready.pdf">paper</a>  <a href="https://github.com/scott89/WSS">github</a></th>
        </tr>        
    </thead>
</table>

	

	


### Visual Object Tracking
[Recommended Homepage---OTB Results. This shares results for more recent trackers.](https://github.com/foolwood/benchmark_results)
	
### Object Detection

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
            <th><img src="data/R-CNN.png"  alt="R-CNN" align=center /></th>
            <th>Rich feature hierarchies for accurate object detection and semantic segmentation</th>
            <th>Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik</th>
            <th>CVPR 2014</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf">paper</a>  <a href="https://github.com/rbgirshick/rcnn">github</a></th>
        </tr> 
        <tr>
            <th><img src="data/Fast-R-CNN.png"  alt="Fast-R-CNN" align=center /></th>
            <th>Fast R-CNN</th>
            <th>Ross Girshick</th>
            <th>ICCV 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Girshick_Fast_R-CNN_ICCV_2015_paper.pdf">paper</a>  <a href="https://github.com/rbgirshick/fast-rcnn">github</a></th>
        </tr>
        <tr>
            <th><img src="data/Faster-R-CNN.png"  alt="Faster-R-CNN" align=center /></th>
            <th>Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks</th>
            <th>Shaoqing Ren, <a href="http://kaiminghe.com/">Kaiming He</a>, Ross Girshick, Jian Sun</th>
            <th>NIPS 2015</th>
            <th><a href="http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks.pdf">paper</a> <a href="https://github.com/ShaoqingRen/faster_rcnn">matlab</a>  <a href="https://github.com/rbgirshick/py-faster-rcnn">python</a></th>
        </tr>
        <tr>
            <th><img src="data/CFM.png"  alt="CFM" align=center /></th>
            <th>Convolutional Feature Masking for Joint Object and Stuff Segmentation</th>
            <th>Jifeng Dai, <a href="http://kaiminghe.com/">Kaiming He</a>, Jian Sun</th>
            <th>CVPR 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Dai_Convolutional_Feature_Masking_2015_CVPR_paper.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/MNC.png"  alt="MNC" align=center /></th>
            <th>Instance-aware Semantic Segmentation via Multi-task Network Cascades</th>
            <th>Jifeng Dai, <a href="http://kaiminghe.com/">Kaiming He</a>, Jian Sun</th>
            <th>CVPR 2016</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Dai_Instance-Aware_Semantic_Segmentation_CVPR_2016_paper.pdf">paper</a>  <a href="https://github.com/daijifeng001/MNC">github</a></th>
        </tr> 
        <tr>
            <th><img src="data/Region-FCN.png"  alt="Region-FCN" align=center /></th>
            <th>R-FCN: Object Detection via Region-based Fully Convolutional Networks</th>
            <th>Jifeng Dai, Yi Li,  <a href="http://kaiminghe.com/">Kaiming He</a>, Jian Sun</th>
            <th>NIPS 2016</th>
            <th><a href="https://arxiv.org/abs/1605.06409">paper</a>  <a href="https://github.com/daijifeng001/R-FCN">github</a></th>
        </tr>
        <tr>
            <th><img src="data/FPN.png"  alt="FPN" align=center /></th>
            <th>Feature Pyramid Networks for Object Detection</th>
            <th>Tsung-Yi Lin, Piotr Dollár, Ross Girshick, <a href="http://kaiminghe.com/">Kaiming He</a>, Bharath Hariharan, and Serge Belongie</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/pdf/1612.03144.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/Mask-R-CNN.png"  alt="Mask-R-CNN" align=center /></th>
            <th>Mask R-CNN</th>
            <th>Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick</th>
            <th>Tech Report</th>
            <th><a href="https://arxiv.org/abs/1703.06870">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/A-Fast-R-CNN.png"  alt="A-Fast-R-CNN" align=center /></th>
            <th>A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection</th>
            <th>Xiaolong Wang, Abhinav Shrivastava, Abhinav Gupta</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.03414">paper</a>  <a href="https://github.com/xiaolonw/adversarial-frcnn">github</a></th>
        </tr>
        <tr>
            <th><img src="data/MIDN.png"  alt="MIDN" align=center /></th>
            <th>Multiple Instance Detection Network with Online Instance Classifier Refinement</th>
            <th>Peng Tang, Xinggang Wang, Xiang Bai, Wenyu Liu</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.00138">paper</a></th>
        </tr>    
    </thead>
</table>
	
	
### Object Localization

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
            <th><img src="data/SDS.png"  alt="SDS" align=center /></th>
            <th>Simultaneous Detection and Segmentation</th>
            <th>Bharath Hariharan, Pablo Arbeláez, Ross Girshick, Jitendra Malik</th>
            <th>ECCV 2014</th>
            <th><a href="https://arxiv.org/abs/1407.1808">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/WSOL.png"  alt="WSOL" align=center /></th>
            <th>Deep Self-Taught Learning for Weakly Supervised Object Localization</th>
            <th>Zequn Jie, Yunchao Wei, Xiaojie Jin, Jiashi Feng, Wei Liu</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.05188">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/LDDP.png"  alt="LDDP" align=center /></th>
            <th>Learning Detection with Diverse Proposals</th>
            <th>Samaneh Azadi, Jiashi Feng, Trevor Darrell</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.03533">paper</a></th>
        </tr>
    </thead>
</table>	

### Semantic Segmentation & Scene Parsing

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
            <th><img src="data/FCN.png"  alt="FCN" align=center /></th>
            <th>Fully Convolutional Networks for Semantic Segmentation</th>
            <th>Jonathan Long, Evan Shelhamer, Trevor Darrell</th>
            <th>CVPR 2015</th>
            <th><a href="https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/LSOC.png"  alt="LSOC" align=center /></th>
            <th>Learning to Segment Object Candidates</th>
            <th>Pedro O. Pinheiro, Ronan Collobert, Piotr Dollar</th>
            <th>NIPS 2015</th>
            <th><a href="http://papers.nips.cc/paper/5852-learning-to-segment-object-candidates.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/LROS.png"  alt="LROS" align=center /></th>
            <th>Learning to Refine Object Segments</th>
            <th>Pedro O. Pinheiro , Tsung-Yi Lin , Ronan Collobert, Piotr Doll ́ar</th>
            <th>arXiv 1603.08695</th>
            <th><a href="https://arxiv.org/pdf/1603.08695.pdf">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/CRFRNN.png"  alt="CRFRNN" align=center /></th>
            <th>Conditional Random Fields as Recurrent Neural Networks</th>
            <th>Shuai Zheng, Sadeep Jayasumana, Bernardino Romera-Paredes, Vibhav Vineet, ZhiZhong Su, Dalong Du, Chang Huang, and Philip H. S. Torr</th>
            <th>ICCV 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zheng_Conditional_Random_Fields_ICCV_2015_paper.html">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/LDN.png"  alt="LDN" align=center /></th>
            <th>Learning Deconvolution Network for Semantic Segmentation</th>
            <th>Heonwoo Noh, Seunghoon Hong, Bohyung Han</th>
            <th>ICCV 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Noh_Learning_Deconvolution_Network_ICCV_2015_paper.html">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/ISFCN.png"  alt="ISFCN" align=center /></th>
            <th>Instance-sensitive Fully Convolutional Networks</th>
            <th>Jifeng Dai, Kaiming He, Yi Li, Shaoqing Ren, Jian Sun</th>
            <th>arXiv 1603.08678</th>
            <th><a href="https://arxiv.org/abs/1603.08678">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/SSIS.png"  alt="SSIS" align=center /></th>
            <th>Attention to Scale: Scale-aware Semantic Image Segmentation</th>
            <th>Liang-Chieh Chen, Yi Yang, Jiang Wang, Wei Xu, Alan L. Yuille</th>
            <th>CVPR 2016</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Chen_Attention_to_Scale_CVPR_2016_paper.html">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/Not-All-Pixels-Are-Equal.png"  alt="Not-All-Pixels-Are-Equal" align=center /></th>
            <th>Not All Pixels Are Equal: Difficulty-Aware Semantic Segmentation via Deep Layer Cascade</th>
            <th>Xiaoxiao Li, Ziwei Liu, Ping Luo, Chen Change Loy, Xiaoou Tang</th>
            <th>CVPR 2016</th>
            <th><a href="https://arxiv.org/abs/1704.01344">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/RefineNet.png"  alt="RefineNet" align=center /></th>
            <th>RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation</th>
            <th>Guosheng Lin, Anton Milan, Chunhua Shen, Ian Reid</th>
            <th>arXiv 1611.06612</th>
            <th><a href="https://arxiv.org/abs/1611.06612">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/PSPNet.png"  alt="PSPNet" align=center /></th>
            <th>Pyramid Scene Parsing Network</th>
            <th>Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, Jiaya Jia</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1612.01105>paper</a>  <a href="https://github.com/hszhao/PSPNet">github</a></th>
        </tr> 
        <tr>
            <th><img src="data/DRN.png"  alt="DRN" align=center /></th>
            <th>Dilated Residual Networks</th>
            <th>Fisher Yu, Vladlen Koltun, Thomas Funkhouser</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1705.09914">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/FCIS.png"  alt="FCIS" align=center /></th>
            <th>Fully Convolutional Instance-aware Semantic Segmentation</th>
            <th>Yi Li, Haozhi Qi, Jifeng Dai, Xiangyang Ji, Yichen Wei</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1611.07709">paper</a>  <a href="https://github.com/msracver/FCIS">github</a></th>
        </tr>  
    </thead>
</table>

### Edge Detection

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
            <th><img src="data/HED.png"  alt="HED" align=center /></th>
            <th>Holistically-Nested Edge Detection</th>
            <th>Saining Xie, Zhuowen Tu</th>
            <th>ICCV 2015</th>
            <th><a href="http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Xie_Holistically-Nested_Edge_Detection_ICCV_2015_paper.pdf">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/RCF.png"  alt="RCF" align=center /></th>
            <th>Richer Convolutional Features for Edge Detection</th>
            <th>Yun Liu, Ming-Ming Cheng, Xiaowei Hu, Kai Wang, Xiang Bai</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1612.02103">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/CASENet.png"  alt="CASENet" align=center /></th>
            <th>CASENet: Deep Category-Aware Semantic Edge Detection</th>
            <th>Zhiding Yu, Chen Feng, Ming-Yu Liu, Srikumar Ramalingam</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1705.09759">paper</a></th>
        </tr>
    </thead>
</table>	
	
### Pose Estimation

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
            <th><img src="data/Hourglass.png"  alt="Hourglass" align=center /></th>
            <th>Stacked Hourglass Networks for Human Pose Estimation</th>
            <th>Alejandro Newell, Kaiyu Yang, and Jia Deng</th>
            <th>ECCV 2016</th>
            <th><a href="https://arxiv.org/abs/1603.06937">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/MCA.png"  alt="MCA" align=center /></th>
            <th>Multi-Context Attention for Human Pose Estimation</th>
            <th><a href="http://www.ee.cuhk.edu.hk/~xchu/">Xiao Chu</a>, Wei Yang, <a href="http://www.ee.cuhk.edu.hk/~wlouyang/">Wanli Ouyang</a>, Cheng Ma, Alan L. Yuille, <a href="http://www.ee.cuhk.edu.hk/~xgwang/">Xiaogang Wang</a></th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1702.07432">paper</a>  <a href="https://github.com/bearpaw/pose-attention">github</a></th>
        </tr>
    </thead>
</table>	

### Semantic Matching

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
            <th><img src="data/AnchorNet.png"  alt="AnchorNet" align=center /></th>
            <th>AnchorNet: A Weakly Supervised Network to Learn Geometry-sensitive Features For Semantic Matching</th>
            <th>David Novotny, DianeLarlus, Andrea Vedaldi</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.04749">paper</a></th>
        </tr> 
    </thead>
</table>	
	
### Super Resolution

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
            <th><img src="data/LapSRN.png"  alt="LapSRN" align=center /></th>
            <th>Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution</th>
            <th>Wei-Sheng Lai, Jia-Bin Huang, Narendra Ahuja, Ming-Hsuan Yang</th>
            <th>CVPR 2017</th>
            <th><a href="http://vllab1.ucmerced.edu/~wlai24/LapSRN/">project page</a></th>
        </tr> 
    </thead>
</table>	

### Image Classification

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
            <th><img src="data/ResNet.png"  alt="ResNet" align=center /></th>
            <th>Deep Residual Learning for Image Recognition</th>
            <th>Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun</th>
            <th>CVPR 2015</th>
            <th><a href="https://arxiv.org/abs/1512.03385">paper</a>  <a href="https://github.com/KaimingHe/deep-residual-networks">github</a></th>
        </tr> 
        <tr>
            <th><img src="data/Res-Attention-Network.png"  alt="Res-Attention-Network" align=center /></th>
            <th>Residual Attention Network for Image Classification</th>
            <th>Fei Wang, Mengqing Jiang, Chen Qian, Shuo Yang, Cheng Li, Honggang Zhang, Xiaogang Wang, Xiaoou Tang</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.06904">paper</a></th>
        </tr> 
       <tr>
            <th><img src="data/ResNeXt.png"  alt="ResNeXt" align=center /></th>
            <th>Aggregated Residual Transformations for Deep Neural Networks</th>
            <th>Saining Xie, Ross Girshick, Piotr Dollár, Zhuowen Tu, and Kaiming He</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1611.05431">paper</a> <a href="https://github.com/facebookresearch/ResNeXt">github</a></th>
        </tr>
    </thead>
</table>	
	
### Others

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
            <th><img src="data/SRN.png"  alt="SRN" align=center /></th>
            <th>SRN：Side-output Residual Network for Object Symmetry Detection in the Wild</th>
            <th>Wei Ke, Jie Chen, Jianbin Jiao, Guoying Zhao and Qixiang Ye</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1703.02243">paper</a></th>
        </tr> 
        <tr>
            <th><img src="data/QAN.png"  alt="QAN" align=center /></th>
            <th>Quality Aware Network for Set to Set Recognition</th>
            <th>Yu Liu, Junjie Yan, Wanli Ouyang</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.03373">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/Continuous-CRFs.png"  alt="Continuous-CRFs" align=center /></th>
            <th>Multi-Scale Continuous CRFs as Sequential Deep Networks for Monocular Depth Estimation</th>
            <th>Dan Xu, Elisa Ricci, Wanli Ouyang, Xiaogang Wang, Nicu Sebe</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.02157">paper</a></th>
        </tr>
        <tr>
            <th><img src="data/CMT.png"  alt="CMT" align=center /></th>
            <th>Learning Cross-Modal Deep Representations for Robust Pedestrian Detection</th>
            <th>Dan Xu, Wanli Ouyang, Elisa Ricci, Xiaogang Wang, Nicu Sebe</th>
            <th>CVPR 2017</th>
            <th><a href="https://arxiv.org/abs/1704.02431">paper</a></th>
        </tr>    
    </thead>
</table>