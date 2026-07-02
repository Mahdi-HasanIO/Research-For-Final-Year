# Marine-YOLO: A high-precision object detection algorithm for complex maritime environments


## Abstract

Sea Surface Object Detection is of great significance for intelligent shipping, marine monitoring, and search and rescue. However, in complex sea-surface scenarios, challenges remain, such as severe weather, illumination changes, large variations in object scale, and missed detections of small targets. To address these issues, this paper proposes Marine-YOLO based on YOLOv11 to improve detection accuracy and robustness in complex sea-surface environments. First, Marine-YOLO introduces a C3k2-SP module into the backbone network to enhance feature representation and environmental robustness. Second, a SAGA attention module is added to the neck to strengthen multi-scale modeling capability. Finally, an AFAE-Head module is designed in the detection head, and a P2 layer is incorporated to optimize small-object detection performance. Experimental results on the WSODD dataset show that Marine-YOLO achieves 76.7% and 44.1% on mAP50 and mAP50–95, respectively, representing improvements of 3.5% and 1.3% over YOLOv11n. While achieving higher accuracy, Marine-YOLO (4.2 M parameters and 13.3 GFLOPs) has more parameters and computational cost than YOLOv11n (2.6 M parameters and 6.5 GFLOPs), but still far less than other high-performance models. Compared with RT-DETR-X (67.3 M parameters and 232.4 GFLOPs), Marine-YOLO maintains higher accuracy while reducing parameters and computation by about 94%, and improving mAP50 and mAP50–95 by 12.2% and 13.9%, respectively. The results indicate that Marine-YOLO achieves a good balance between accuracy and efficiency, making it an ideal choice for real-time marine object detection.

# YOLO-SEA: An Enhanced Detection Framework for Multi-Scale Maritime Targets in Complex Sea States and Adverse Weather


## Abstract

Maritime object detection is essential for resource monitoring, maritime defense, and public safety, yet detecting diverse targets beyond ships remains challenging. This paper presents YOLO-SEA, an efficient detection framework based on the enhanced YOLOv8 architecture. The model incorporates the SESA (SimAM-Enhanced SENetV2 Attention) module, which integrates the channel-adaptive weight adjustment of SENetV2 with the parameter-free spatial-channel modeling of SimAM to enhance feature representation. An improved BiFPN (Bidirectional Feature Pyramid Network) structure enhances multi-scale fusion, particularly for small object detection. In the post-processing stage, Soft-NMS (Soft Non-Maximum Suppression) replaces traditional NMS to reduce false suppression in dense scenes. YOLO-SEA detects eight maritime object types. Experiments show it achieves a 5.8% improvement in mAP@0.5 and 7.2% improvement in mAP@0.5:0.95 over the baseline, demonstrating enhanced accuracy and robustness in complex marine environments.

Keywords:

[maritime target detection](https://www.mdpi.com/search?q=maritime+target+detection);  [YOLOv8](https://www.mdpi.com/search?q=YOLOv8);  [deep learning](https://www.mdpi.com/search?q=deep+learning);  [multi-target recognition](https://www.mdpi.com/search?q=multi-target+recognition)


# YOLO-Ssboat: Super-Small Ship Detection Network for Large-Scale Aerial and Remote Sensing Scenes


## Abstract

Enhancing the detection capabilities of marine vessels is crucial for maritime security and intelligence acquisition. However, accurately identifying small ships in complex oceanic environments remains a significant challenge, as these targets are frequently obscured by ocean waves and other disturbances, compromising recognition accuracy and stability. To address this issue, we propose YOLO-ssboat, a novel small-target ship recognition algorithm based on the YOLOv8 framework. YOLO-ssboat integrates the C2f_DCNv3 module to extract fine-grained features of small vessels while mitigating background interference and preserving critical target details. Additionally, it employs a high-resolution feature layer and incorporates a Multi-Scale Weighted Pyramid Network (MSWPN) to enhance feature diversity. The algorithm further leverages an improved multi-attention detection head, Dyhead_v3, to refine the representation of small-target features. To tackle the challenge of wake waves from moving ships obscuring small targets, we introduce a gradient flow mechanism that improves detection efficiency under dynamic conditions. The Tail Wave Detection Method synergistically integrates gradient computation with target detection techniques. Furthermore, adversarial training enhances the network’s robustness and ensures greater stability. Experimental evaluations on the Ship_detection and Vessel datasets demonstrate that YOLO-ssboat outperforms state-of-the-art detection algorithms in both accuracy and stability. Notably, the gradient flow mechanism enriches target feature extraction for moving vessels, thereby improving detection accuracy in wake-disturbed scenarios, while adversarial training further fortifies model resilience. These advancements offer significant implications for the long-range monitoring and detection of maritime vessels, contributing to enhanced situational awareness in expansive oceanic environments.

Keywords:

[small target detection](https://www.mdpi.com/search?q=small+target+detection);  [deformable convolution](https://www.mdpi.com/search?q=deformable+convolution);  [feature fusion](https://www.mdpi.com/search?q=feature+fusion);  [adversarial training](https://www.mdpi.com/search?q=adversarial+training)



# Object Detection and Classification Based on YOLO-V5 with Improved Maritime Dataset


## Abstract

SMD (Singapore Maritime Dataset) is a public dataset with annotated videos, and it is almost unique in the training of deep neural networks (DNN) for the recognition of maritime objects. However, there are noisy labels and imprecisely located bounding boxes in the ground truth of the SMD. In this paper, for the benchmark of DNN algorithms, we correct the annotations of the SMD dataset and present an improved version, which we coined SMD-Plus. We also propose augmentation techniques designed especially for the SMD-Plus. More specifically, an online transformation of training images via Copy & Paste is applied to solve the class-imbalance problem in the training dataset. Furthermore, the mix-up technique is adopted in addition to the basic augmentation techniques for YOLO-V5. Experimental results show that the detection and classification performance of the modified YOLO-V5 with the SMD-Plus has improved in comparison to the original YOLO-V5. The ground truth of the SMD-Plus and our experimental results are available for download.

Keywords:

[object detection](https://www.mdpi.com/search?q=object+detection);  [maritime dataset](https://www.mdpi.com/search?q=maritime+dataset);  [deep learning](https://www.mdpi.com/search?q=deep+learning);  [data relabel](https://www.mdpi.com/search?q=data+relabel)


# YOLO-MRS: An efficient deep learning-based maritime object detection method for unmanned surface vehicles



## Abstract

Deep learning-based object detection for an unmanned  [surface vehicle](https://www.sciencedirect.com/topics/earth-and-planetary-sciences/surface-vehicle) (USV) is an important way of visual perception. However, current methods perform poorly when performing complex maritime object detection tasks. It also lacks available datasets of complex maritime objects for visual perception system of USVs. In order to solve these problems, we propose an improved maritime object detection method, called YOLO-MRS, based on lightweight YOLOv8 model in this paper. Specifically, we introduce a multi-scale cross-axis attention (MCA) mechanism into the backbone network of the model to establish long-distance dependencies between pixels to capture global feature information. In addition, we introduce Simplified Spatial Pyramid Pooling-Fast (SimSPPF) to the backbone to enhance prediction accuracy. Also, considering computational efficiency, we replace the ordinary  [convolutional layers](https://www.sciencedirect.com/topics/engineering/convolutional-layer)  in the backbone network and neck network with refocused convolutional (RefConv) layers to reduce model parameters. Especially, we construct a maritime object detection dataset, termed MODD-13, which contains over 9000 precisely annotated images. The proposed MODD-13 sufficiently considers the characteristics of object categories (13 types), image diversity, sample independence, and background confusion, and can be used as a benchmark dataset for maritime object detection. The final experimental results show that compared with the representative YOLO series models, YOLO-MRS improves the average mAP50 accuracy by 1.8%–7% and mAP50-95 by 1.1%–11.5%, and effectively balances detection accuracy and computational efficiency, thereby effectively achieving fast and accurate detection of maritime objects.


# CRAS-YOLO: A Novel Multi-Category Vessel Detection and Classification Model Based on YOLOv5s Algorithm


## Abstract:

Multi-category vessel detection and classification based on satellite imagery attract a lot of attention due to their significant applications in the military and civilian domains. In this study, we generated a new Artificial-SAR-Vessel dataset based on the combination of the FUSAR-Ship dataset and the SimpleCopyPaste method. We further proposed a novel multi-category vessel detection called CRAS-YOLO which consisted of a convolutional block attention module (CBAM), receptive fields block (RFB), and adaptively spatial feature fusion (ASFF) based on YOLOv5s. The proposed CRAS-YOLO improved the feature pyramid network based on the path aggregation network (PANet), which integrates the RFB feature enhancement module and ASFF feature fusion strategy to obtain richer feature information and realize the adaptive fusion of multi-scale features (RA-PANet). At the same time, a CBAM is added to the backbone to accurately locate the vessel location and improve detection capability. The results confirmed that the proposed CRAS-YOLO model reached a precision, recall rate, and mean average precision (mAP) (0.5) of up to 90.4%, 88.6%, and 92.1% respectively. The proposed model also outperformed previous studies’ results in another Sar Ship Detection (SSDD) dataset with precision, recall, and mAP scores of up to 97.3%, 95.5%, and 98.7% respectively.


# GGT-YOLO: A Novel Object Detection Algorithm for Drone-Based Maritime Cruising


## Abstract

Drones play an important role in the development of remote sensing and intelligent surveillance. Due to limited onboard computational resources, drone-based object detection still faces challenges in actual applications. By studying the balance between detection accuracy and computational cost, we propose a novel object detection algorithm for drone cruising in large-scale maritime scenarios. Transformer is introduced to enhance the feature extraction part and is beneficial to small or occluded object detection. Meanwhile, the computational cost of the algorithm is reduced by replacing the convolution operations with simpler linear transformations. To illustrate the performance of the algorithm, a specialized dataset composed of thousands of images collected by drones in maritime scenarios is given, and quantitative and comparative experiments are conducted. By comparison with other derivatives, the detection precision of the algorithm is increased by 1.4%, the recall is increased by 2.6% and the average precision is increased by 1.9%, while the parameters and floating-point operations are reduced by 11.6% and 7.3%, respectively. These improvements are thought to contribute to the application of drones in maritime and other remote sensing fields.

Keywords:

[drone](https://www.mdpi.com/search?q=drone);  [maritime surveillance](https://www.mdpi.com/search?q=maritime+surveillance);  [object detection](https://www.mdpi.com/search?q=object+detection);  [Transformer](https://www.mdpi.com/search?q=Transformer);  [GhostNet](https://www.mdpi.com/search?q=GhostNet)



# AM YOLO: adaptive multi-scale YOLO for ship instance segmentation


## Abstract

Instance segmentation has seen widespread development and significant progress across various fields. However, ship instance segmentation in marine environments faces challenges, including complex sea surface backgrounds, indistinct target features, and large-scale variations, making it incapable of achieving the desirable results. To overcome these challenges, this paper presents an adaptive multi-scale YOLO (AM YOLO) algorithm to improve instance segmentation performance for multi-scale ship targets in marine environments. Initially, the algorithm proposes a multi-grained adaptive feature enhancement module (MAEM) that utilizes grouped weighting and multiple adaptive mechanisms to enhance the extraction of details and improve the accuracy of multi-scale and global information. Subsequently, this study proposes a refine bidirectional feature pyramid network (RBiFPN) structure, which employs a cross-channel attention adaptive mechanism to integrate feature information and contextual details across different scales fully. Experiments on the challenging MS COCO dataset, COCO-boat dataset, and OVSD dataset show that compared to the baseline YOLOv5s, the AM YOLO model increases instance segmentation precision by 4.0%, 1.4%, and 2.3%, respectively. This improvement enhances the model’s generalization capabilities and achieves an optimal balance between accuracy and speed while maintaining real-time performance, thus broadening the model’s applicability in dynamic marine environments


Spotlight on Small-scale Ship Detection: Empowering YOLO with Advanced Techniques and a Novel Dataset


**Abstract**  
  

In recent years, significant advancements have been made in deep learning-based ship detection methods on the ocean surface. However, publicly available maritime datasets that include categories for small-scale ships and network frameworks optimized explicitly for small-scale ship detection on the ocean surface are still limited in availability. To address the data scarcity in small-scale ship detection, bridge the gap between small-scale ship detection and general object detection, and mitigate the impact of small objects on maritime safety, we collect a multi-scale dataset with a particular emphasis on detecting small objects on the ocean surface, named the iShip-1. Leveraging this dataset, we train the S^3Det for small-scale ship detection, which remarkably detects small-scale ships on the ocean surface. Specifically, the iShip-1 comprises 17,236 images encompassing six categories captured from multiple perspectives and under various weather conditions. Notably, the Other Ship category focuses explicitly on small-scale ships. The S^3Det is optimized for detecting small-scale ships through improved backbone and neck architecture. It employs the NWD Loss instead of the traditional IoU Loss and utilizes the Feedback Cut&Paste technique for effective data augmentation. We evaluate the performance of the S^3Det on both the Seaships and iShip-1. For small-scale ship detection, S^3Det achieved a recall rate of 68.9%, a mAP50 of 73.9%, and a mAP50:90 of 39.4%. These results indicate improvements of 5.9%, 2%, and 1.2% compared to the original YOLOv8 model, respectively. Our code and dataset are available here https://github.com/li01233/S3Det.



# ROI-YOLO Model: Real-Time Deep Learning Detector for Floating Objects on River


## Abstract:

Floating objects on river and lake surfaces can cause significant water pollution, necessitating timely detection and treatment. However, the features of floating objects are complex and variable, with a small proportion in monitoring scenes and image quality constrained by surveillance equipment. To address these challenges, this study proposes the ROI-YOLO model for rapid and intelligent detection of floating objects in monitoring video images. The proposed model comprises three key components. First, the pre-detection module enables fast scene focusing and background suppression for large-scale video images, overcoming the issue of excessive information loss caused by downsampling in real-world scenarios. Second, the model employs multi-resolution feature extraction and precise localization of floating objects, with the design of adaptive anchor boxes based on object density and maximum-minimum distances. Third, the sub-pixel feature fusion module learns upsampling operators on feature maps and integrates multi-resolution features based on sub-pixel information, enhancing the restoration and fusion of effective information to improve detection accuracy. Furthermore, the model utilizes Bernoulli distribution-based random parameter updates during training, reducing the required training sample size. The resulting model achieves a mean average precision of 84.5%, a recall of 90.9%, and a detection speed of 27 FPS (Frames Per Second), outperforming other deep learning based object detection models.


# EFD-YOLO: An Improved YOLOv8 Network for River Floating Debris Object Detection


## Abstract:

With the rapid development of uncrewed aerial vehicle (UAV) technology, UAVs have provided an innovative solution for floating debris monitoring. However, object detection in UAV images remains challenging due to high miss rates for small objects, insufficient low-level feature extraction, and computational redundancy. This letter proposes an efficient floating debris detection model based on YOLOv8n, named EFD-you only look once (YOLO), to address these issues. First, the edge fusion stem (EFStem) module is proposed to enhance low-level feature extraction through an integrated gate-attention mechanism. Second, the multibranch efficient reparameterization block (MBERB) is designed to achieve efficient cross-layer feature fusion. Experimental results demonstrate that compared to YOLOv8n, our model achieves a 6.3% improvement in mean average precision (mAP) on the UAV floating debris dataset, while simultaneously reducing parameters by 26.7% and improving small object recall by 21.9%. The inference time of EFD-YOLO on the RK3588 edge device is as low as 30.5 ms, demonstrating real-time capability.


# A High-Precision Detection Model of Small Objects in Maritime UAV Perspective Based on Improved YOLOv5

_first_page_

[Download PDF](https://www.mdpi.com/2077-1312/11/9/1680/pdf?version=1693200709)

_settings_

[Order Article Reprints](https://www.mdpi.com/2077-1312/11/9/1680/reprints)

Open AccessArticle

# A High-Precision Detection Model of Small Objects in Maritime UAV Perspective Based on Improved YOLOv5

by

Zhilin Yang

[](mailto:dmu_zly@dlmu.edu.cn),

Yong Yin

[](mailto:bushyin@dlmu.edu.cn),

Qianfeng Jing

*[](mailto:jqf_dlmu@dlmu.edu.cn)[![](https://pub.mdpi-res.com/img/design/orcid.png?0465bc3812adeb52?1782465688 "ORCID")](https://orcid.org/0000-0001-8452-9961)  and

Zeyuan Shao

[](mailto:szy@dlmu.edu.cn)[![](https://pub.mdpi-res.com/img/design/orcid.png?0465bc3812adeb52?1782465688 "ORCID")](https://orcid.org/0000-0003-2637-8004)

Navigation College, Dalian Maritime University, Dalian 116026, China

*

Author to whom correspondence should be addressed.

_J. Mar. Sci. Eng._  **2023**,  _11_(9), 1680;  [https://doi.org/10.3390/jmse11091680](https://doi.org/10.3390/jmse11091680)

Submission received: 11 July 2023  /  Revised: 11 August 2023  /  Accepted: 24 August 2023  /  Published: 25 August 2023

(This article belongs to the Special Issue  [Application of Advanced Technologies in Maritime Safety](https://www.mdpi.com/journal/jmse/special_issues/Technologies_Maritime_Safety))  

Download_keyboard_arrow_down_

[Browse Figures](https://www.mdpi.com/2077-1312/11/9/1680#)

[Versions Notes](https://www.mdpi.com/2077-1312/11/9/1680/notes)

## Abstract

Object detection by shipborne unmanned aerial vehicles (UAVs) equipped with electro-optical (EO) sensors plays an important role in maritime rescue and ocean monitoring. However, high-precision and low-latency maritime environment small-object-detection algorithms remain a major challenge. To address this problem, this paper proposes the YOLO-BEV (“you only look once”–“bird’s-eye view”) model. First, we constructed a bidirectional feature fusion module—that is, PAN+ (Path Aggregation Network+)—adding an extremely-small-object-prediction head to deal with the large-scale variance of targets at different heights. Second, we propose a C2fSESA (Squeeze-and-Excitation Spatial Attention Based on C2f) module based on the attention mechanism to obtain richer feature information by aggregating features of different depth layers. Finally, we describe a lightweight spatial pyramid pooling structure called RGSPP (Random and Group Convolution Spatial Pyramid Pooling), which uses group convolution and random channel rearrangement to reduce the model’s computational overhead and improve its generalization ability. The article compares the YOLO-BEV model with other object-detection algorithms on the publicly available MOBDrone dataset. The research results show that the mAP0.5  value of YOLO-BEV reached 97.1%, which is 4.3% higher than that of YOLOv5, and the average precision for small objects increased by 22.2%. Additionally, the YOLO-BEV model maintained a detection speed of 48 frames per second (FPS). Consequently, the proposed method effectively balances the accuracy and efficiency of object-detection in shipborne UAV scenarios, outperforming other related techniques in shipboard UAV maritime object detection.

Keywords:

[shipborne UAV scenarios](https://www.mdpi.com/search?q=shipborne+UAV+scenarios);  [object detection](https://www.mdpi.com/search?q=object+detection);  [attention mechanism](https://www.mdpi.com/search?q=attention+mechanism);  [space pyramid pool](https://www.mdpi.com/search?q=space+pyramid+pool);  [YOLOv5](https://www.mdpi.com/search?q=YOLOv5)




# Maritime Small Object Detection Algorithm in Drone Aerial Images Based on Improved YOLOv8


## Abstract:

Combining unmanned aerial vehicles (UAVs) with deep learning algorithms offers an efficient, safe and inexpensive alternative to maritime search and rescue (mSAR) missions. Maritime UAV images present unique challenges for object detection due to their complex nature, including dense distribution, multi-scale objects and occlusion. Aiming to address this problem, we propose a novel lightweight model specifically designed for maritime small object detection, named AB2D-YOLO. Firstly, the attention based intra-scale feature interaction (AIFI) module is used to replace the spatial pyramid pooling fast (SPPF) module on the backbone, enhancing the detection precision of occluded and densely small targets by integrating global and contextual feature information. Secondly, the dilation-wise residual (DWR) module is integrated into the network. The module employs three sets of dilated convolution with different sampling rates to obtain multi-scale receptive fields, which effectively improves the capacity for detecting multi-scale objects. Then, we propose an improved network fusion model based on weighted bi-directional feature pyramid network (BiFPN) to reconstruct the neck, which can enhance the features of small targets through weighted fusion of feature information of different scales and bidirectional cross-scale connection. Finally, we add a new detection layer in the neck to capture more object location information in images. When compared to the benchmark model YOLOv8s, AB2D-YOLO achieves an 8.96% increase in mean average precision (mAP) on the SeaDroneSee dataset, while maintaining a low model complexity with only 6.95 MB of parameters. When compared to state-of-the-art models, AB2D-YOLO model is conducive to the deployment of maritime UAV.


# YOLO-LFVM: A Lightweight UAV-Based Model for Real-Time Fishing Vessel Tracking and Dimension Measurement


_first_page_

_settings_

[Order Article Reprints](https://www.mdpi.com/2077-1312/13/9/1739/reprints)

Open AccessArticle

# YOLO-LFVM: A Lightweight UAV-Based Model for Real-Time Fishing Vessel Tracking and Dimension Measurement

by

Zhuofan Hui

1[](mailto:huizf0909@126.com),

Penglong Li

1,2[](mailto:15142892813@163.com)[![](https://pub.mdpi-res.com/img/design/orcid.png?0465bc3812adeb52?1782465688 "ORCID")](https://orcid.org/0009-0009-2199-4909),

Shujiang Miao

1,

Yinfu Li

3[](mailto:liyinfu28@163.com),

Lie Shen

1,*[](mailto:shenlie@dlou.edu.cn)  and

Hui Shen

4

1

College of Navigation and Naval Engineering, Dalian Ocean University, Dalian 116023, China

2

Key Laboratory of Fishery Remote Sensing, East China Sea Fisheries Research Institute, Chinese Academy of Fishery Sciences, Ministry of Agriculture and Rural Affairss, Shanghai 200090, China

3

Merchant Marine College, Shanghai Maritime University, Shanghai 201306, China

4

Liaoning Provincial Marine and Fishery Administrative Law Enforcement Corps, Dalian 116023, China

*

Author to whom correspondence should be addressed.

_J. Mar. Sci. Eng._  **2025**,  _13_(9), 1739;  [https://doi.org/10.3390/jmse13091739](https://doi.org/10.3390/jmse13091739)

Submission received: 15 August 2025  /  Revised: 1 September 2025  /  Accepted: 5 September 2025  /  Published: 10 September 2025

(This article belongs to the Section  [Ocean Engineering](https://www.mdpi.com/journal/jmse/sections/ocean_engineering))  

Download_keyboard_arrow_down_

[Browse Figures](https://www.mdpi.com/2077-1312/13/9/1739#)

[Versions Notes](https://www.mdpi.com/2077-1312/13/9/1739/notes)

## Abstract

This study proposes a lightweight real-time fishing vessel tracking and size measurement model based on a UAV. In view of the problems faced by the current fishing port management department, such as low efficiency of fishing vessel size measurement methods and difficulty in updating the size information of large quantities of fishing vessels in time, this paper proposes a lightweight real-time fishing vessel tracking and size measurement model based on a UAV. (YOLO-LFVM). The model incorporates lightweight modules, such as MobileNetV3, AKConv, and C2f, and utilizes Python scripts in conjunction with OpenCV to measure vessel size in pixels. The findings indicate that, compared to the original model, the YOLO-LFVM model’s accuracy rate, recall rate, and mAP@0.5 decrease by only 0.7%, 0.2%, and 0.3%, respectively, while mAP@0.95 increases by 1.7%. Additionally, the model’s parameters decrease by 65%, and GFLOPs decrease by 69%. When comparing the model’s output with actual vessel data, the average relative error for total length is 2.67%, and for width, it is 3.28%. The research shows that the YOLO-LFVM model is effective in ship identification, ship tracking statistics, and measurement. Through the integration with UAV remote sensing technology, it is conducive to the timely updating of large-scale fishing vessel size information. Finally, the model can assist the daily management and law enforcement of the fishing port management department and can be applied to other equipment with limited computing power to perform target detection and object size measurement tasks.

Keywords:

[object detection](https://www.mdpi.com/search?q=object+detection);  [YOLOv8](https://www.mdpi.com/search?q=YOLOv8);  [ship category statistics](https://www.mdpi.com/search?q=ship+category+statistics);  [hull size measurements](https://www.mdpi.com/search?q=hull+size+measurements);  [lightweight improvement](https://www.mdpi.com/search?q=lightweight+improvement)



### D. YOLO-based detection methodology

**1. Marine-YOLO: A high-precision object detection algorithm for complex maritime environments**

**Abstract:** Sea Surface Object Detection is of great significance for intelligent shipping, marine monitoring, and search and rescue. However, in complex sea-surface scenarios, challenges remain, such as severe weather, illumination changes, large variations in object scale, and missed detections of small targets. To address these issues, this paper proposes Marine-YOLO based on YOLOv11 to improve detection accuracy and robustness in complex sea-surface environments. First, Marine-YOLO introduces a C3k2-SP module into the backbone network to enhance feature representation and environmental robustness. Second, a SAGA attention module is added to the neck to strengthen multi-scale modeling capability. Finally, an AFAE-Head module is designed in the detection head, and a P2 layer is incorporated to optimize small-object detection performance. Experimental results on the WSODD dataset show that Marine-YOLO achieves 76.7% and 44.1% on mAP50 and mAP50–95, respectively, representing improvements of 3.5% and 1.3% over YOLOv11n. While achieving higher accuracy, Marine-YOLO (4.2 M parameters and 13.3 GFLOPs) has more parameters and computational cost than YOLOv11n (2.6 M parameters and 6.5 GFLOPs), but still far less than other high-performance models. Compared with RT-DETR-X (67.3 M parameters and 232.4 GFLOPs), Marine-YOLO maintains higher accuracy while reducing parameters and computation by about 94%, and improving mAP50 and mAP50–95 by 12.2% and 13.9%, respectively. The results indicate that Marine-YOLO achieves a good balance between accuracy and efficiency, making it an ideal choice for real-time marine object detection.

**2. YOLO-SEA: An Enhanced Detection Framework for Multi-Scale Maritime Targets in Complex Sea States and Adverse Weather**

**Abstract:** Maritime object detection is essential for resource monitoring, maritime defense, and public safety, yet detecting diverse targets beyond ships remains challenging. This paper presents YOLO-SEA, an efficient detection framework based on the enhanced YOLOv8 architecture. The model incorporates the SESA (SimAM-Enhanced SENetV2 Attention) module, which integrates the channel-adaptive weight adjustment of SENetV2 with the parameter-free spatial-channel modeling of SimAM to enhance feature representation. An improved BiFPN (Bidirectional Feature Pyramid Network) structure enhances multi-scale fusion, particularly for small object detection. In the post-processing stage, Soft-NMS (Soft Non-Maximum Suppression) replaces traditional NMS to reduce false suppression in dense scenes. YOLO-SEA detects eight maritime object types. Experiments show it achieves a 5.8% improvement in mAP@0.5 and 7.2% improvement in mAP@0.5:0.95 over the baseline, demonstrating enhanced accuracy and robustness in complex marine environments.

**3. YOLO-Ssboat: Super-Small Ship Detection Network for Large-Scale Aerial and Remote Sensing Scenes**

**Abstract:** Enhancing the detection capabilities of marine vessels is crucial for maritime security and intelligence acquisition. However, accurately identifying small ships in complex oceanic environments remains a significant challenge, as these targets are frequently obscured by ocean waves and other disturbances, compromising recognition accuracy and stability. To address this issue, we propose YOLO-ssboat, a novel small-target ship recognition algorithm based on the YOLOv8 framework. YOLO-ssboat integrates the C2f_DCNv3 module to extract fine-grained features of small vessels while mitigating background interference and preserving critical target details. Additionally, it employs a high-resolution feature layer and incorporates a Multi-Scale Weighted Pyramid Network (MSWPN) to enhance feature diversity. The algorithm further leverages an improved multi-attention detection head, Dyhead_v3, to refine the representation of small-target features. To tackle the challenge of wake waves from moving ships obscuring small targets, we introduce a gradient flow mechanism that improves detection efficiency under dynamic conditions. The Tail Wave Detection Method synergistically integrates gradient computation with target detection techniques. Furthermore, adversarial training enhances the network’s robustness and ensures greater stability. Experimental evaluations on the Ship_detection and Vessel datasets demonstrate that YOLO-ssboat outperforms state-of-the-art detection algorithms in both accuracy and stability. Notably, the gradient flow mechanism enriches target feature extraction for moving vessels, thereby improving detection accuracy in wake-disturbed scenarios, while adversarial training further fortifies model resilience. These advancements offer significant implications for the long-range monitoring and detection of maritime vessels, contributing to enhanced situational awareness in expansive oceanic environments.

**4. Object Detection and Classification Based on YOLO-V5 with Improved Maritime Dataset**

**Abstract:** SMD (Singapore Maritime Dataset) is a public dataset with annotated videos, and it is almost unique in the training of deep neural networks (DNN) for the recognition of maritime objects. However, there are noisy labels and imprecisely located bounding boxes in the ground truth of the SMD. In this paper, for the benchmark of DNN algorithms, we correct the annotations of the SMD dataset and present an improved version, which we coined SMD-Plus. We also propose augmentation techniques designed especially for the SMD-Plus. More specifically, an online transformation of training images via Copy & Paste is applied to solve the class-imbalance problem in the training dataset. Furthermore, the mix-up technique is adopted in addition to the basic augmentation techniques for YOLO-V5. Experimental results show that the detection and classification performance of the modified YOLO-V5 with the SMD-Plus has improved in comparison to the original YOLO-V5. The ground truth of the SMD-Plus and our experimental results are available for download.

**5. YOLO-MRS: An efficient deep learning-based maritime object detection method for unmanned surface vehicles**

**Abstract:** Deep learning-based object detection for an unmanned surface vehicle (USV) is an important way of visual perception. However, current methods perform poorly when performing complex maritime object detection tasks. It also lacks available datasets of complex maritime objects for visual perception system of USVs. In order to solve these problems, we propose an improved maritime object detection method, called YOLO-MRS, based on lightweight YOLOv8 model in this paper. Specifically, we introduce a multi-scale cross-axis attention (MCA) mechanism into the backbone network of the model to establish long-distance dependencies between pixels to capture global feature information. In addition, we introduce Simplified Spatial Pyramid Pooling-Fast (SimSPPF) to the backbone to enhance prediction accuracy. Also, considering computational efficiency, we replace the ordinary convolutional layers in the backbone network and neck network with refocused convolutional (RefConv) layers to reduce model parameters. Especially, we construct a maritime object detection dataset, termed MODD-13, which contains over 9000 precisely annotated images. The proposed MODD-13 sufficiently considers the characteristics of object categories (13 types), image diversity, sample independence, and background confusion, and can be used as a benchmark dataset for maritime object detection. The final experimental results show that compared with the representative YOLO series models, YOLO-MRS improves the average mAP50 accuracy by 1.8%–7% and mAP50-95 by 1.1%–11.5%, and effectively balances detection accuracy and computational efficiency, thereby effectively achieving fast and accurate detection of maritime objects.

**6. CRAS-YOLO: A Novel Multi-Category Vessel Detection and Classification Model Based on YOLOv5s Algorithm**

**Abstract:** Multi-category vessel detection and classification based on satellite imagery attract a lot of attention due to their significant applications in the military and civilian domains. In this study, we generated a new Artificial-SAR-Vessel dataset based on the combination of the FUSAR-Ship dataset and the SimpleCopyPaste method. We further proposed a novel multi-category vessel detection called CRAS-YOLO which consisted of a convolutional block attention module (CBAM), receptive fields block (RFB), and adaptively spatial feature fusion (ASFF) based on YOLOv5s. The proposed CRAS-YOLO improved the feature pyramid network based on the path aggregation network (PANet), which integrates the RFB feature enhancement module and ASFF feature fusion strategy to obtain richer feature information and realize the adaptive fusion of multi-scale features (RA-PANet). At the same time, a CBAM is added to the backbone to accurately locate the vessel location and improve detection capability. The results confirmed that the proposed CRAS-YOLO model reached a precision, recall rate, and mean average precision (mAP) (0.5) of up to 90.4%, 88.6%, and 92.1% respectively. The proposed model also outperformed previous studies’ results in another Sar Ship Detection (SSDD) dataset with precision, recall, and mAP scores of up to 97.3%, 95.5%, and 98.7% respectively.

**7. GGT-YOLO: A Novel Object Detection Algorithm for Drone-Based Maritime Cruising**

**Abstract:** Drones play an important role in the development of remote sensing and intelligent surveillance. Due to limited onboard computational resources, drone-based object detection still faces challenges in actual applications. By studying the balance between detection accuracy and computational cost, we propose a novel object detection algorithm for drone cruising in large-scale maritime scenarios. Transformer is introduced to enhance the feature extraction part and is beneficial to small or occluded object detection. Meanwhile, the computational cost of the algorithm is reduced by replacing the convolution operations with simpler linear transformations. To illustrate the performance of the algorithm, a specialized dataset composed of thousands of images collected by drones in maritime scenarios is given, and quantitative and comparative experiments are conducted. By comparison with other derivatives, the detection precision of the algorithm is increased by 1.4%, the recall is increased by 2.6% and the average precision is increased by 1.9%, while the parameters and floating-point operations are reduced by 11.6% and 7.3%, respectively. These improvements are thought to contribute to the application of drones in maritime and other remote sensing fields.

**8. AM YOLO: adaptive multi-scale YOLO for ship instance segmentation**

**Abstract:** Instance segmentation has seen widespread development and significant progress across various fields. However, ship instance segmentation in marine environments faces challenges, including complex sea surface backgrounds, indistinct target features, and large-scale variations, making it incapable of achieving the desirable results. To overcome these challenges, this paper presents an adaptive multi-scale YOLO (AM YOLO) algorithm to improve instance segmentation performance for multi-scale ship targets in marine environments. Initially, the algorithm proposes a multi-grained adaptive feature enhancement module (MAEM) that utilizes grouped weighting and multiple adaptive mechanisms to enhance the extraction of details and improve the accuracy of multi-scale and global information. Subsequently, this study proposes a refine bidirectional feature pyramid network (RBiFPN) structure, which employs a cross-channel attention adaptive mechanism to integrate feature information and contextual details across different scales fully. Experiments on the challenging MS COCO dataset, COCO-boat dataset, and OVSD dataset show that compared to the baseline YOLOv5s, the AM YOLO model increases instance segmentation precision by 4.0%, 1.4%, and 2.3%, respectively. This improvement enhances the model’s generalization capabilities and achieves an optimal balance between accuracy and speed while maintaining real-time performance, thus broadening the model’s applicability in dynamic marine environments.

**9. Spotlight on Small-scale Ship Detection: Empowering YOLO with Advanced Techniques and a Novel Dataset**

**Abstract:** In recent years, significant advancements have been made in deep learning-based ship detection methods on the ocean surface. However, publicly available maritime datasets that include categories for small-scale ships and network frameworks optimized explicitly for small-scale ship detection on the ocean surface are still limited in availability. To address the data scarcity in small-scale ship detection, bridge the gap between small-scale ship detection and general object detection, and mitigate the impact of small objects on maritime safety, we collect a multi-scale dataset with a particular emphasis on detecting small objects on the ocean surface, named the iShip-1. Leveraging this dataset, we train the S^3Det for small-scale ship detection, which remarkably detects small-scale ships on the ocean surface. Specifically, the iShip-1 comprises 17,236 images encompassing six categories captured from multiple perspectives and under various weather conditions. Notably, the Other Ship category focuses explicitly on small-scale ships. The S^3Det is optimized for detecting small-scale ships through improved backbone and neck architecture. It employs the NWD Loss instead of the traditional IoU Loss and utilizes the Feedback Cut&Paste technique for effective data augmentation. We evaluate the performance of the S^3Det on both the Seaships and iShip-1. For small-scale ship detection, S^3Det achieved a recall rate of 68.9%, a mAP50 of 73.9%, and a mAP50:90 of 39.4%. These results indicate improvements of 5.9%, 2%, and 1.2% compared to the original YOLOv8 model, respectively.

**10. ROI-YOLO Model: Real-Time Deep Learning Detector for Floating Objects on River**

**Abstract:** Floating objects on river and lake surfaces can cause significant water pollution, necessitating timely detection and treatment. However, the features of floating objects are complex and variable, with a small proportion in monitoring scenes and image quality constrained by surveillance equipment. To address these challenges, this study proposes the ROI-YOLO model for rapid and intelligent detection of floating objects in monitoring video images. The proposed model comprises three key components. First, the pre-detection module enables fast scene focusing and background suppression for large-scale video images, overcoming the issue of excessive information loss caused by downsampling in real-world scenarios. Second, the model employs multi-resolution feature extraction and precise localization of floating objects, with the design of adaptive anchor boxes based on object density and maximum-minimum distances. Third, the sub-pixel feature fusion module learns upsampling operators on feature maps and integrates multi-resolution features based on sub-pixel information, enhancing the restoration and fusion of effective information to improve detection accuracy. Furthermore, the model utilizes Bernoulli distribution-based random parameter updates during training, reducing the required training sample size. The resulting model achieves a mean average precision of 84.5%, a recall of 90.9%, and a detection speed of 27 FPS (Frames Per Second), outperforming other deep learning based object detection models.

**11. EFD-YOLO: An Improved YOLOv8 Network for River Floating Debris Object Detection**

**Abstract:** With the rapid development of uncrewed aerial vehicle (UAV) technology, UAVs have provided an innovative solution for floating debris monitoring. However, object detection in UAV images remains challenging due to high miss rates for small objects, insufficient low-level feature extraction, and computational redundancy. This letter proposes an efficient floating debris detection model based on YOLOv8n, named EFD-you only look once (YOLO), to address these issues. First, the edge fusion stem (EFStem) module is proposed to enhance low-level feature extraction through an integrated gate-attention mechanism. Second, the multibranch efficient reparameterization block (MBERB) is designed to achieve efficient cross-layer feature fusion. Experimental results demonstrate that compared to YOLOv8n, our model achieves a 6.3% improvement in mean average precision (mAP) on the UAV floating debris dataset, while simultaneously reducing parameters by 26.7% and improving small object recall by 21.9%. The inference time of EFD-YOLO on the RK3588 edge device is as low as 30.5 ms, demonstrating real-time capability.

**12. A High-Precision Detection Model of Small Objects in Maritime UAV Perspective Based on Improved YOLOv5**

**Abstract:** Object detection by shipborne unmanned aerial vehicles (UAVs) equipped with electro-optical (EO) sensors plays an important role in maritime rescue and ocean monitoring. However, high-precision and low-latency maritime environment small-object-detection algorithms remain a major challenge. To address this problem, this paper proposes the YOLO-BEV (“you only look once”–“bird’s-eye view”) model. First, we constructed a bidirectional feature fusion module—that is, PAN+ (Path Aggregation Network+)—adding an extremely-small-object-prediction head to deal with the large-scale variance of targets at different heights. Second, we propose a C2fSESA (Squeeze-and-Excitation Spatial Attention Based on C2f) module based on the attention mechanism to obtain richer feature information by aggregating features of different depth layers. Finally, we describe a lightweight spatial pyramid pooling structure called RGSPP (Random and Group Convolution Spatial Pyramid Pooling), which uses group convolution and random channel rearrangement to reduce the model’s computational overhead and improve its generalization ability. The article compares the YOLO-BEV model with other object-detection algorithms on the publicly available MOBDrone dataset. The research results show that the mAP0.5 value of YOLO-BEV reached 97.1%, which is 4.3% higher than that of YOLOv5, and the average precision for small objects increased by 22.2%. Additionally, the YOLO-BEV model maintained a detection speed of 48 frames per second (FPS). Consequently, the proposed method effectively balances the accuracy and efficiency of object-detection in shipborne UAV scenarios, outperforming other related techniques in shipboard UAV maritime object detection.

**13. Maritime Small Object Detection Algorithm in Drone Aerial Images Based on Improved YOLOv8**

**Abstract:** Combining unmanned aerial vehicles (UAVs) with deep learning algorithms offers an efficient, safe and inexpensive alternative to maritime search and rescue (mSAR) missions. Maritime UAV images present unique challenges for object detection due to their complex nature, including dense distribution, multi-scale objects and occlusion. Aiming to address this problem, we propose a novel lightweight model specifically designed for maritime small object detection, named AB2D-YOLO. Firstly, the attention based intra-scale feature interaction (AIFI) module is used to replace the spatial pyramid pooling fast (SPPF) module on the backbone, enhancing the detection precision of occluded and densely small targets by integrating global and contextual feature information. Secondly, the dilation-wise residual (DWR) module is integrated into the network. The module employs three sets of dilated convolution with different sampling rates to obtain multi-scale receptive fields, which effectively improves the capacity for detecting multi-scale objects. Then, we propose an improved network fusion model based on weighted bi-directional feature pyramid network (BiFPN) to reconstruct the neck, which can enhance the features of small targets through weighted fusion of feature information of different scales and bidirectional cross-scale connection. Finally, we add a new detection layer in the neck to capture more object location information in images. When compared to the benchmark model YOLOv8s, AB2D-YOLO achieves an 8.96% increase in mean average precision (mAP) on the SeaDroneSee dataset, while maintaining a low model complexity with only 6.95 MB of parameters.

**14. YOLO-LFVM: A Lightweight UAV-Based Model for Real-Time Fishing Vessel Tracking and Dimension Measurement**

**Abstract:** This study proposes a lightweight real-time fishing vessel tracking and size measurement model based on a UAV. In view of the problems faced by the current fishing port management department, such as low efficiency of fishing vessel size measurement methods and difficulty in updating the size information of large quantities of fishing vessels in time, this paper proposes a lightweight real-time fishing vessel tracking and size measurement model based on a UAV (YOLO-LFVM). The model incorporates lightweight modules, such as MobileNetV3, AKConv, and C2f, and utilizes Python scripts in conjunction with OpenCV to measure vessel size in pixels. The findings indicate that, compared to the original model, the YOLO-LFVM model’s accuracy rate, recall rate, and mAP@0.5 decrease by only 0.7%, 0.2%, and 0.3%, respectively, while mAP@0.95 increases by 1.7%. Additionally, the model’s parameters decrease by 65%, and GFLOPs decrease by 69%. When comparing the model’s output with actual vessel data, the average relative error for total length is 2.67%, and for width, it is 3.28%. The research shows that the YOLO-LFVM model is effective in ship identification, ship tracking statistics, and measurement. Through the integration with UAV remote sensing technology, it is conducive to the timely updating of large-scale fishing vessel size information.

**15. FLCSDet: Federated Learning-Driven Cross-Spatial Vessel Detection for Maritime Surveillance With Privacy Preservation**

**Abstract:** Maritime surveillance plays a vital role in reducing maritime accidents and improving maritime safety. To enhance situational awareness for maritime movements, deep learning-based visual object detection has become an important part of maritime surveillance. However, the detection results are highly dependent on the training datasets collected from different departments (i.e., clients). If the sub-datasets from departments are sensitive and private in cross-department maritime surveillance, it will be intractable to directly combine these sub-datasets to train the learning-based object detection method. To solve this issue, we propose a federated learning-driven cross-spatial vessel detection model, called FLCSDet, for maritime surveillance with privacy preservation. In particular, an efficient multi-scale attention module is integrated into our FLCSDet to achieve local cross-spatial feature learning. To improve the federated-learning aggregation method, we propose an optimized algorithm based on the proportion of valid data on departments to adaptively select the allocating weights and preserve the specific characteristics of client data. In addition, we employ transfer learning to further improve the robustness and convergence of our FLCSDet under different experimental scenarios. Compared with several representative federated learning-based detection methods, our FLCSDet could achieve superior detection performance in terms of both quantitative and qualitative results. Moreover, comprehensive experiments conducted on real datasets from both inland waterways and open seas demonstrate the robustness and generalization of our method in intelligent transportation systems.

**16. Enhanced YOLOv8 for accurate and efficient floating object detection on water surfaces**

**Abstract:** Detecting floating objects on water surfaces is critical for environmental monitoring and pollution control. We present SEDS-YOLOv8, an enhanced YOLOv8n variant that integrates Squeeze-and-Excitation (SE) attention, Distribution Shift Convolution (DSConv), and Enhanced Intersection over Union (EIoU) loss to address challenges in complex aquatic environments. These environments are characterized by surface reflections, ripple-induced noise, and dense small debris that complicate accurate detection. We trained and evaluated our model on a hybrid dataset of 28,000 images with data augmentation for robustness. The SEDSConv module replaces selected convolutional layers with DSConv for efficient multi-scale feature extraction, while SE attention suppresses reflection-induced channel noise by recalibrating feature responses. The EIoU loss accelerates convergence and improves localization accuracy through decoupled width-height regression. SEDS-YOLOv8 achieves 86.02% precision, 85.01% recall, and 88.82% mAP@0.5 with 2.90M parameters and 7.60 GFLOPs (7.3% fewer than the baseline YOLOv8n at 8.20 GFLOPs), while maintaining real-time inference at 103.7 FPS on NVIDIA RTX 4090 hardware. Our contribution is the systematic integration and adaptation of existing techniques to water-surface detection, demonstrating that task-specific architectural choices can substantially improve accuracy without sacrificing computational efficiency.

**17. YOLOv7-Sea: Object Detection of Maritime UAV Images Based on Improved YOLOv7**

**Abstract:** Object detection algorithms play an important role in maritime search and rescue missions, where they are designed to detect people, boats and other objects in open water. However, the SeaDronesee dataset has the characteristics of small targets and large sea surface interference, which brings great challenges to general object detectors. To address these issues, we propose an improved detector YOLOv7-sea. Based on YOLOv7, we add a prediction head to detect tiny-scale people or objects. Besides, we integrate Simple, Parameter-Free Attention Module (SimAM) to find attention regions in the scene. To achieve further improvements to our proposed YOLOv7-sea, we provide some useful strategies such as data augmentation, test time augmentation (TTA), and bundled box fusion (WBF). On the ODv2 challenge dataset, the AP result of YOLOv7-sea is 59.00%, which is about 7% higher than the baseline model (YOLOv7).



