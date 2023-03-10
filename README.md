# Awesome-Local-Feature

A curated list of resources for awesome local feature related works. 

If you find some overlooked papers, please open issues or pull requests (recommended).

<p align="left">
    <a href="https://github.com/subeeshvasu/Awesome-Deblurring/pulls/new">Suggest new item</a>
    <br />
    <a href="https://github.com/subeeshvasu/Awesome-Deblurring/issues/new">Report Bug</a>
</p>

## Table of contents
- [Survey](#survey)
- [Benchmark](#benchmark)
- [Datasets](#datasets)
- [Detector Learning](#detector-learning)
- [Descriptor Learning](#descriptor-learning)
- [Joint Detector & Descriptor Learning](#joint-detector-descriptor-learning)
- [Others](#others)


## Survey
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2021|IJCV|[Image Matching from Handcrafted to Deep Features: A Survey](https://link.springer.com/content/pdf/10.1007/s11263-020-01359-2.pdf)|[Blog](https://blog.csdn.net/qq_42708183/article/details/109133806)|

## Benchmark
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|


## Datasets
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2017|CVPR|[Comparative Evaluation of Hand-Crafted and Learned Local Features](https://demuc.de/papers/schoenberger2017comparative.pdf)|[Code](https://github.com/ahojnnes/local-feature-evaluation)|
|2017|CVPR|[HPatches: A benchmark and evaluation of handcrafted and learned local descriptors](https://openaccess.thecvf.com/content_cvpr_2017/papers/Balntas_HPatches_A_Benchmark_CVPR_2017_paper.pdf)|[Code & Project page](https://hpatches.github.io/)|


## Detector Learning
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2015|CVPR|[TILDE: A Temporally Invariant Learned DEtector](https://openaccess.thecvf.com/content_cvpr_2015/papers/Verdie_TILDE_A_Temporally_2015_CVPR_paper.pdf)|[Code](https://github.com/vcg-uvic/TILDE)|
|2017|CVPR|[Quad-networks: unsupervised learning to rank for interest point detection](https://www.microsoft.com/en-us/research/uploads/prod/2019/09/quad_cvpr17.pdf)||
|2017|CVPR|[Learning Discriminative and Transformation Covariant Local Feature Detectors](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Learning_Discriminative_and_CVPR_2017_paper.pdf)|[Code](https://github.com/ColumbiaDVMM/Transform_Covariant_Detector)|
|2018|CVPR|[Learning to Detect Features in Texture Images](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Learning_to_Detect_CVPR_2018_paper.pdf)|[Code](https://github.com/lg-zhang/pytorch-keypoint-release)|
|2019|ICCV|[Key.Net: Keypoint Detection by Handcrafted and Learned CNN Filters](http://refbase.cvc.uab.es/files/BRP2019.pdf)|[Code](https://github.com/axelBarroso/Key.Net)|
|2019|ICCV|[ELF: Embedded Localisation of Features in Pre-Trained CNN](https://openaccess.thecvf.com/content_ICCV_2019/papers/Benbihi_ELF_Embedded_Localisation_of_Features_in_Pre-Trained_CNN_ICCV_2019_paper.pdf)|[Code](https://github.com/abenbihi/elf)|
|2020|ACCV|[D2D: Keypoint Extraction with Describe to Detect Approach](https://openaccess.thecvf.com/content/ACCV2020/papers/Tian_D2D_Keypoint_Extraction_with_Describe_to_Detect_Approach_ACCV_2020_paper.pdf)||
|2021|WACV|[Learning of low-level feature keypoints for accurate and robust detection](https://openaccess.thecvf.com/content/WACV2021/papers/Suwanwimolkul_Learning_of_Low-Level_Feature_Keypoints_for_Accurate_and_Robust_Detection_WACV_2021_paper.pdf)||


## Descriptor Learning
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2014|ArXiv|[Descriptor Matching with Convolutional Neural Networks: a Comparison to SIFT](https://lmb.informatik.uni-freiburg.de/Publications/2014/FDB14/1405.5769v1.pdf)||
|2015|ICCV|[iscriminative Learning of Deep Convolutional Feature Point Descriptors](https://openaccess.thecvf.com/content_iccv_2015/papers/Simo-Serra_Discriminative_Learning_of_ICCV_2015_paper.pdf)|[Code](https://github.com/etrulls/deepdesc-release)|
|2015|CVPR|[Learning to Compare Image Patches via Convolutional Neural Networks](https://arxiv.org/pdf/1504.03641.pdf)|[Blog](https://blog.csdn.net/m0_61899108/article/details/122609390)|
|2015|CVPR|[MatchNet: Unifying Feature and Metric Learning for Patch-Based Matching](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Han_MatchNet_Unifying_Feature_2015_CVPR_paper.pdf)|[Blog](https://blog.csdn.net/qq_36104364/article/details/115299866)|
|2015|CVPR|[Computing the Stereo Matching Cost with a Convolutional Neural Network](https://openaccess.thecvf.com/content_cvpr_2015/papers/Zbontar_Computing_the_Stereo_2015_CVPR_paper.pdf)||
|2016|CVPR|[Learning Local Image Descriptors with Deep Siamese and Triplet Convolutional Networks by Minimizing Global Loss Functions](https://openaccess.thecvf.com/content_cvpr_2016/papers/G_Learning_Local_Image_CVPR_2016_paper.pdf)||
|2016|CoRR|[PN-Net: Conjoined Triple Deep Networks for Learning Local Image Descriptors](https://arxiv.org/pdf/1601.05030.pdf)|[Code](https://github.com/vbalnt/pnnet), [Blog](https://blog.csdn.net/qq_36104364/article/details/115324732)|
|2016|BMVC|[Learning local feature descriptors with triplets and shallow convolutional neural networks](http://www.bmva.org/bmvc/2016/papers/paper119/paper119.pdf)|[Code](https://github.com/vbalnt/tfeat)|


## Joint Detector & Descriptor Learning
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2022|ACCV|[Rethinking Low-level Features for Interest Point Detection and Description](https://openaccess.thecvf.com/content/ACCV2022/papers/Wang_Rethinking_Low-level_Features_for_Interest_Point_Detection_and_Description_ACCV_2022_paper.pdf)|[Code](https://github.com/wangch-g/lanet)|
|2020|ICLR|[Neural Outlier Rejection for Self-Supervised Keypoint Learning](https://openreview.net/pdf?id=Skx82ySYPH)|[Code](https://github.com/TRI-ML/KP2D)|

## Others
|Year|Pub|Paper|Repo|
|:---:|:---:|:---:|:---:|
|2016|CVPR|[Learning to Assign Orientations to Feature Points](https://openaccess.thecvf.com/content_cvpr_2016/papers/Yi_Learning_to_Assign_CVPR_2016_paper.pdf)||
|2020|CVPR|[On Translation Invariance in CNNs: Convolutional Layers can Exploit Absolute Spatial Location](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kayhan_On_Translation_Invariance_in_CNNs_Convolutional_Layers_Can_Exploit_Absolute_CVPR_2020_paper.pdf)|[Code](https://github.com/oskyhn/CNNs-Without-Borders)|
