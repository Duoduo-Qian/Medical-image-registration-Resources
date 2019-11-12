# Medical-image-registration-Resouces
Medical image registration related books, tutorials, papers, datasets, toolboxes and deep learning open source codes

# 1. Books

Zhenhuan Zhou, et.al: [ **A software guide for medical image segmentation and registration algorithm.**](https://vdisk.weibo.com/s/FQyto0RT-heb) 

PartⅡ introduces the most basic network and architecture of medical registration algorithms**(Chinese Version)**.

# 2. Tutorials & Workshops

## 2.1 Tutorials

[ **Learn2Reg**](https://github.com/learn2reg/tutorials2019)     MICCAI2019

[ **Autograd Image Registration Laboratory**](https://github.com/airlab-unibas)    MICCAI2019

[**Medical Image Registration**](https://github.com/natandrade/Tutorial-Medical-Image-Registration  )



## 2.2 Workshops

WBIR - International Workshop on Biomedical Image Registration
[WBIR2018,](https://wbir2018.nl/index.html) Leiden, Netherlands
WBIR2016, Las Vegas NV 
WBIR2014, London, UK 

# 3. Datasets

|                    Dataset                     | Number | Modality |  Region  |     Format      |
| :--------------------------------------------: | :----: | :------: | :------: | :-------------: |
|      [DIRLAB](https://www.dir-lab.com/ )       |   10   |  4D  CT  |   Lung   |      .img       |
|                   [LPBA40]()                   |   40   | 3D  MRI  | T1 Brain | .img+.hdr  .nii |
| [IBSR18](https://www.nitrc.org/projects/ibsr/) |   18   | 3D  MRI  | T1 Brain |    .img+.hdr    |
|      [EMPIRE](http://empire10.isi.uu.nl/)      |   30   |  4D CT   |   Lung   |    .mhd+.raw    |
|                   [LiTS]( )                    |  131   |  3D CT   |  Liver   |      .nii       |

# 4. Toolbox

**Image registration tools survey**：A. Klein *et al.*, [“Evaluation of 14 nonlinear deformation algorithms applied to human brain MRI registration,”]( https://www.ncbi.nlm.nih.gov/pubmed/19195496 ) *Neuroimage*, vol. 46, no. 3, pp. 786–802, 2009.



**Tools:**

[c++] [**ITK**]( https://itk.org/ ): Segmentation & Registration Toolkit

[c++ Python and Java] [**SimpleITK**]( http://www.simpleitk.org/ ): A simplified layer built on top of ITK

[c++] [**ANTS**]( https://github.com/ANTsX/ANTs ): Advanced normalization tools 

[c++] [**Elastix**]( http://elastix.isi.uu.nl/index.php ): A toolbox for rigid and nonrigid registration of images



**Github repository for deep learning medical image registration**:

[Keras] [**VoxelMorph**](https://github.com/voxelmorph/voxelmorph)

 [Keras] [**FAIM**]( https://github.com/dykuang/Medical-image-registration )

 [Tensorflow] [**Weakly-supervised CNN**](https://github.com/YipengHu/label-reg)

 [Tensorflow] [**RegNet3D** ](https://github.com/hsokooti/RegNet)

[Tensorflow] [**Recursive-Cascaded-Networks**](https://github.com/microsoft/Recursive-Cascaded-Networks) 

 [Pytorch] [**Probabilistic Dense Displacement Network**](https://github.com/multimodallearning/pdd_net)

 [Pytorch] [**Linear and Deformable Image Registration**](https://github.com/shreshth211/image-registration-cnn)

 [Pytorch] [**Inverse-Consistent Deep Networks**](https://github.com/zhangjun001/ICNet) 

 [Pytorch] [**Non-parametric image registration**](https://github.com/uncbiag/registration) 

 [Pytorch] [**One Shot Deformable Medical Image Registration**](https://github.com/ToFec/OneShotImageRegistration)

 [Pytorch] [**Image-and-Spatial Transformer Networks**](https://github.com/biomedia-mira/istn)

# 5. Papers

**<u>Links and papers will be continuously updated.</u>** 

## 5.1 Survey papers  

[1]    A. Sotiras, C. Davatzikos, and N. Paragios, [“Deformable medical image registration: A survey,”]( https://ieeexplore.ieee.org/document/6522524 ) *IEEE Trans. Med. Imaging*, vol. 32, no. 7, pp. 1153–1190, 2013.

[2]    N. J. Tustison, B. B. Avants, and J. C. Gee, [“Learning image-based spatial transformations via convolutional neural networks : A review,” ]( https://www.sciencedirect.com/science/article/abs/pii/S0730725X19300037 )*Magn. Reson. Imaging*, no. January, pp. 0–1, 2019.

[3]    G. Haskins, U. Kruger, and P. Yan, “Deep Learning in Medical Image Registration: A Survey,” 2019.

[4]    M. Blendowski and M. P. Heinrich, “Combining MRF-based deformable registration and deep binary 3D-CNN descriptors for large lung motion estimation in COPD patients,” *Int. J. Comput. Assist. Radiol. Surg.*, vol. 14, no. 1, pp. 43–52, 2019.

## 5.2 Traditional medical image registration methods

*To be updated*

## 5.3 Learning-based methods

### 5.3.1 Iterative learning methods

[1]    M. Blendowski and M. P. Heinrich, [“Combining MRF-based deformable registration and deep binary 3D-CNN descriptors for large lung motion estimation in COPD patients,”]( https://www.ncbi.nlm.nih.gov/pubmed/30430361 ) *Int. J. Comput. Assist. Radiol. Surg.*, vol. 14, no. 1, pp. 43–52, 2019.

[2]    G. Wu, M. Kim, Q. Wang, Y. Gao, S. Liao, and D. Shen, “Unsupervised deep feature learning for deformable registration of MR brain images,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 8150 LNCS, no. PART 2, pp. 649–656, 2013.

[3]    K. A. J. Eppenhof and J. P. W. Pluim, “Error estimation of deformable image registration of pulmonary CT scans using convolutional neural networks,” *J. Med. Imaging*, vol. 5, no. 02, p. 1, 2018.

[4]    M. Simonovsky, B. Gutiérrez-Becker, D. Mateus, N. Navab, and N. Komodakis, “A deep metric for multimodal registration,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 9902 LNCS, pp. 10–18, 2016.

[5]    S. Miao *et al.*, “Dilated FCN for multi-agent 2D/3D medical image registration,” *32nd AAAI Conf. Artif. Intell. AAAI 2018*, pp. 4694–4701, 2018.

[6]    A. Sedghi *et al.*, “Semi-Supervised Deep Metrics for Image Registration,” 2018.

[7]    X. Cheng, L. Zhang, and Y. Zheng, “Deep similarity learning for multimodal medical images,” *Comput. Methods Biomech. Biomed. Eng. Imaging Vis.*, vol. 6, no. 3, pp. 248–252, 2018.

[8]    V. A. Z. B *et al.*, *Data Driven Treatment Response Assessment and Preterm, Perinatal, and Paediatric Image Analysis*, vol. 11076. Springer International Publishing, 2018.

[9]    K. Ma *et al.*, “Multimodal Image Registration with Deep Context Reinforcement Learning,” 2017, vol. 10433, no. 1, pp. 728–736.

[10]   J. Krebs *et al.*, “Robust non-rigid registration through agent-based action learning,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 10433 LNCS, pp. 344–352, 2017.

[11]   G. Haskins *et al.*, “Learning deep similarity metric for 3D MR–TRUS image registration,” *Int. J. Comput. Assist. Radiol. Surg.*, vol. 14, no. 3, pp. 417–425, 2019.

[12] R. Liao *et al.*, “An artificial agent for robust image registration,” *31st AAAI Conf. Artif. Intell. AAAI 2017*, pp. 4168–4175, 2017.

### 5.3.2 Supervised learning methods

[1]    X. Cao, J. Yang, L. Wang, Z. Xue, Q. Wang, and D. Shen, [“Deep learning based inter-modality image registration supervised by intra-modality similarity,” ]( https://arxiv.org/abs/1804.10735 )*Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11046 LNCS, pp. 55–63, 2018.

[2]    X. Cao *et al.*, [“Deformable Image Registration Based on Similarity-Steered CNN Regression,” ]( https://link.springer.com/chapter/10.1007/978-3-319-66182-7_35 )vol. 10433, pp. 728–736, 2017.

[3]    Y. Hu, M. Modat, E. Gibson, N. Ghavami, E. Bonmati, and C. M. Moore, “[LABEL-DRIVEN WEAKLY-SUPERVISED LEARNING FOR MULTIMODAL DEFORMABLE IMAGE REGISTRATION]( https://arxiv.org/abs/1711.01666 ) Centre for Medical Image Computing , University College London , UK Institute of Biomedical Engineering , University of Oxford , UK Division of Surgery and Interventional,” *2018 IEEE 15th Int. Symp. Biomed. Imaging (ISBI 2018)*, no. Isbi, pp. 1070–1074, 2018.

[4]    M. Ito and F. Ino, “An automated method for generating training sets for deep learning based image registration,” *BIOIMAGING 2018 - 5th Int. Conf. Bioimaging, Proceedings; Part 11th Int. Jt. Conf. Biomed. Eng. Syst. Technol. BIOSTEC 2018*, vol. 2, no. January, pp. 140–147, 2018.

[5]    X. Yang, R. Kwitt, and M. Niethammer, “Fast predictive image registration,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 10008 LNCS, pp. 48–57, 2016.

[6]    S. Miao, Z. J. Wang, Y. Zheng, and R. Liao, “Real-time 2D/3D registration via CNN regression,” *Proc. - Int. Symp. Biomed. Imaging*, vol. 2016-June, pp. 1430–1434, 2016.

[7]    H. Uzunova, M. Wilms, H. Handels, and J. Ehrhardt, “Training CNNs for image registration from few samples with model-based data augmentation,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 10433 LNCS, pp. 223–231, 2017.

[8]    H. Sokooti, B. de Vos, F. Berendsen, B. P. F. Lelieveldt, I. Iˇsgum, and M. Staring, “Nonrigid image registration using multi-scale 3d convolutional neural networks,” vol. 10433, pp. 728–736, Oct. 2017.

[9]    X. Yang, “UNCERTAINTY QUANTIFICATION, IMAGE SYNTHESIS AND DEFORMATION PREDICTION FOR IMAGE REGISTRATION,” UNC, 2017.

[10]   K. A. J. Eppenhof and J. P. W. Pluim, “Pulmonary CT Registration Through Supervised Learning With Convolutional Neural Networks,” *IEEE Trans. Med. Imaging*, vol. 38, no. 5, pp. 1097–1105, 2019.

[11]   P. Yan, S. Xu, A. R. Rastinehad, and B. J. Wood, “Adversarial image registration with application for MR and TRUS image fusion,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11046 LNCS, pp. 197–204, 2018.

[12]   S. S. Mohseni Salehi, S. Khan, D. Erdogmus, and A. Gholipour, “Real-Time Deep Pose Estimation With Geodesic Loss for Image-to-Template Rigid Registration,” *IEEE Trans. Med. Imaging*, vol. 38, no. 2, pp. 470–481, 2019.

[13]   J. M. Sloan, K. A. Goatman, and J. P. Siebert, “Learning rigid image registration utilizing convolutional neural networks for medical image registration,” *BIOIMAGING 2018 - 5th Int. Conf. Bioimaging, Proceedings; Part 11th Int. Jt. Conf. Biomed. Eng. Syst. Technol. BIOSTEC 2018*, vol. 2, no. Biostec, pp. 89–99, 2018.

[14]   M. Graziani, V. Andrearczyk, and M. Henning, *Understanding and Interpreting Machine Learning in Medical Image Computing Applications*, vol. 11038. Springer International Publishing, 2018.

[15]   L. V. Jun, M. Yang, J. Zhang, and X. Wang, “Respiratory motion correction for free-breathing 3D abdominal MRI using CNN-based image registration: a feasibility study,” *Br. J. Radiol.*, vol. 91, no. 1083, pp. 1–9, 2018.

[16]   Y. Hu *et al.*, “Adversarial deformation regularization for training image registration neural networks,” *arXiv*, vol. 11070 LNCS, pp. 774–782, 2018.

[17]   Rohe and Xavier, “SVF-Net: Learning Deformable Image Registration Using Shape Matching Marc-Michel,” vol. 10433, pp. 728–736, Oct. 2017.

[18]   Y. Hu *et al.*, “Weakly-supervised convolutional neural networks for multimodal image registration,” *Med. Image Anal.*, vol. 49, pp. 1–13, 2018.

[19]   A. Hering, S. Kuckertz, S. Heldmann, and M. P. Heinrich, “Enhancing Label-Driven Deep Deformable Image Registration with Local Distance Metrics for State-of-the-Art Cardiac Motion Tracking,” *Inform. aktuell*, pp. 309–314, 2019.

[20]   J. Zheng, S. Miao, Z. Jane Wang, and R. Liao, “Pairwise domain adaptation module for CNN-based 2-D/3-D registration,” *J. Med. Imaging*, vol. 5, no. 02, p. 1, 2018.

[21]   J. Fan, X. Cao, P. T. Yap, and D. Shen, “BIRNet: Brain image registration using dual-supervised fully convolutional networks,” *Med. Image Anal.*, vol. 54, pp. 193–206, 2019.

[22] E. Chee and Z. Wu, “AIRNet: Self-Supervised Affine Registration for 3D Medical Images using Neural Networks,” pp. 1–13, 2018.

### 5.3.3 Unsupervised learning methods

[1]    S. Ghosal and N. Ray, [“Deep deformable registration: Enhancing accuracy by fully convolutional neural net,” ](Deep Deformable Registration: Enhancing Accuracy by Fully Convolutional Neural Net)*Pattern Recognit. Lett.*, vol. 94, pp. 81–86, 2017.

[2]    Q. Liu and H. Leung, “Tensor-based descriptor for image registration via unsupervised network,” *20th Int. Conf. Inf. Fusion, Fusion 2017 - Proc.*, 2017.

[3]    C. Shu, X. Chen, Q. Xie, and H. Han, “An unsupervised network for fast microscopic image registration,” no. March, p. 48, 2018.

[4]    L. Sun and S. Zhang, “Deformable MRI-Ultrasound Registration Using 3D Convolutional Neural Network,” *shuib*, vol. 11042, pp. 21–28, 2018.

[5]    J. Neylon, Y. Min, D. A. Low, and A. Santhanam, “A neural network approach for fast, automated quantification of DIR performance:,” *Med. Phys.*, vol. 44, no. 8, pp. 4126–4138, 2017.

[6]    D. Kuang and T. Schmah, “FAIM -- A ConvNet Method for Unsupervised 3D Medical Image Registration,” pp. 1–9, 2018.

[7]    Pingge Jiang, J. A. Shackleford, and D. of E. and C. Engineering, “Cnn driven sparse multi-level b-spline image registration,” no. December, pp. 9281–9289, 2012.

[8]    E. Ferrante, O. Oktay, B. Glocker, and D. H. Milone, “On the adaptability of unsupervised CNN-based deformable image registration to unseen image domains,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11046 LNCS, pp. 294–302, 2018.

[9]    G. Balakrishnan, A. Zhao, M. R. Sabuncu, J. Guttag, and A. V. Dalca, “VoxelMorph: A Learning Framework for Deformable Medical Image Registration,” *IEEE Trans. Med. Imaging*, pp. 1–1, 2019.

[10]   B. D. de Vos, F. F. Berendsen, M. A. Viergever, H. Sokooti, M. Staring, and I. Išgum, “A deep learning framework for unsupervised affine and deformable image registration,” *Med. Image Anal.*, vol. 52, pp. 128–143, 2019.

[11]   X. Cao, J. Yang, L. Wang, Z. Xue, Q. Wang, and D. Shen, “Deep learning based inter-modality image registration supervised by intra-modality similarity,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11046 LNCS, pp. 55–63, 2018.

[12]   C. Stergios *et al.*, “Linear and deformable image registration with 3D convolutional neural networks,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11040 LNCS, pp. 13–22, 2018.

[13]   J. Zhang, “Inverse-Consistent Deep Networks for Unsupervised Deformable Image Registration,” vol. 1, pp. 1–13, 2018.

[14]   H. Li and Y. Fan, “Non-rigid image registration using self-supervised fully convolutional networks without training data,” *Proc. - Int. Symp. Biomed. Imaging*, vol. 2018-April, pp. 1075–1078, 2018.

[15]   G. Balakrishnan, A. Zhao, M. R. Sabuncu, A. V. Dalca, and J. Guttag, “An Unsupervised Learning Model for Deformable Medical Image Registration,” in *2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2018, pp. 9252–9260.

[16]   B. D. de Vos, F. F. Berendsen, M. A. Viergever, M. Staring, and I. Išgum, “End-to-end unsupervised deformable image registration with a convolutional neural network,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 10553 LNCS, pp. 204–212, 2017.

[17]   J. Fan, X. Cao, Z. Xue, and P. Yap, *Adversarial Similarity Network for Evaluating Image Alignment in Deep Learning Based Registration*, vol. 8149. Springer International Publishing, 2018.

[18]   A. V. Dalca, G. Balakrishnan, J. Guttag, and M. R. Sabuncu, “Unsupervised learning for fast probabilistic diffeomorphic registration,” *Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics)*, vol. 11070 LNCS, pp. 729–738, 2018.

[19] A. Sheikhjafari, K. Punithakumar, and N. Ray, “Unsupervised Deformable Image Registration with Fully Connected Generative Neural Network,” *Midl*, no. Midl 2018, pp. 1–9, 2018.

### 5.3.4 Most recently papers

[1]    X. Hu, M. Kang, W. Huang, M. R. Scott, R. Wiest, and M. Reyes, [*Dual-Stream Pyramid Registration Network*]( https://arxiv.org/abs/1909.11966 ), vol. 2. Springer International Publishing, 2019.

[2]    D. Wei *et al.*, “Synthesis and Inpainting-Based MR-CT Registration for Image-Guided Thermal Ablation of Liver Tumors,” vol. 2, pp. 1–10, 2019.

[3]    T. Estienne *et al.*, “U-ReSNet: Ultimate Coupling; of Registration and Segmentation with Deep Nets,” vol. 2, pp. 329–337, 2019.

[4]    L. Liu, X. Hu, L. Z. B, and P. Heng, *Probabilistic Multilayer Regularization Network for Unsupervised 3D Brain Image Registration*. Springer International Publishing, 2019.

[5]    M. P. Heinrich, “Closing the Gap between Deep and Conventional Image Registration using Probabilistic Dense Displacement Networks,” pp. 1–9, 2019.

[6]    A. Sheikhjafari, K. Punithakumar, and N. Ray, “Unsupervised Deformable Image Registration with Fully Connected Generative Neural Network,” *Midl*, no. Midl 2018, pp. 1–9, 2018.

[7]    Y. Hu, E. Gibson, D. C. Barratt, M. Emberton, J. A. Noble, and T. Vercauteren, *Conditional Segmentation in Lieu of Image Registration*, vol. 2. Springer International Publishing, 2019.

[8]    S. Zhou, Z. X. B, C. Chen, X. Chen, and D. Liu, *Fast and Accurate Electron Microscopy Image Registration with 3D Convolution*. Springer International Publishing, 2019.

[9]    R. K. Nielsen, S. Darkner, and A. Feragen, *TopAwaRe : Topology-Aware Registration*, vol. 2. Springer International Publishing, 2019.

[10]   J. Luo *et al.*, *On the Ambiguity of Registration Uncertainty*, vol. 2. Springer International Publishing, 2018.

[11]   Z. Xu and M. Niethammer, *DeepAtlas: Joint Semi-Supervised Learning of Image Registration and Segmentation*. Springer International Publishing, 2019.

[12]   M. C. H. Lee, O. Oktay, A. Schuh, M. Schaap, and B. Glocker, *Image-and-Spatial Transformer Networks for Structure-Guided Image Registration*, vol. 2. Springer International Publishing, 2019.

[13]   B. Li *et al.*, “A hybrid deep learning framework for integrated segmentation and registration: evaluation on longitudinal white matter tract changes,” pp. 1–9, 2019.

[14]   M. S. Elmahdy, J. M. Wolterink, H. Sokooti, I. Išgum, and M. Staring, “Adversarial optimization for joint registration and segmentation in prostate CT radiotherapy,” pp. 1–9, 2019.

[15]   W. Zhu *et al.*, “NeurReg: Neural Registration and Its Application to Image Segmentation,” WACV,2020.

[16]   S. Zhao, Y. Dong, E. I.-C. Chang, and Y. Xu, “Recursive Cascaded Networks for Unsupervised Medical Image Registration,” *ICCV2019*, 2019.

[17]   W. Zhu *et al.*, “Neural Multi-Scale Self-Supervised Registration for Echocardiogram Dense Tracking,” pp. 1–9, 2019.

[18]   R. Sandkühler, S. Andermatt, G. Bauman, S. Nyilas, C. Jud, and P. C. Cattin, “Recurrent Registration Neural Networks for Deformable Image Registration,” pp. 1–11, 2019.

[19]   Z. Shen, X. Han, Z. Xu, and M. Niethammer, “Networks for Joint Affine and Non-parametric Image Registration,” *CVPR2019*, pp. 4224–4233, 2019.

[20]   B. D. de Vos, F. F. Berendsen, M. A. Viergever, H. Sokooti, M. Staring, and I. Išgum, “A deep learning framework for unsupervised affine and deformable image registration,” *Med. Image Anal.*, vol. 52, pp. 128–143, 2019.

[21]   T. Lau, J. Luo, S. Zhao, E. I.-C. Chang, and Y. Xu, “Unsupervised 3D End-to-End Medical Image Registration with Volume Tweening Network,” pp. 1–14, 2019.

[22]   J. Fan, X. Cao, Q. Wang, P. Yap, and D. Shen, “Adversarial Learning for Mono- or Multi-Modal Registration,” Medical image analysis, 2019.

# 6. Conferences and Journals

## 6.1 Conferences

**① Biomedical image:**

**MICCAI**, International Conference on Medical Image Computing and Computer Assisted Intervention

**IPMI**, Information Processing in Medical Imaging

**ISBI**，International Symposium on Biomedical Imaging 

Medical Imaging **SPIE**

 **② C.v. c.s Conferences:**

CVPR

ECCV

ICCV

NeurIPS

AAAI

ICML

ICPR

IJCNN

ICIP

IJCAI

## 6.2 Journals

[**TMI**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=42) : IEEE Transactions on Medical Imaging

 [**MIA**](https://www.journals.elsevier.com/medical-image-analysis/): Medical Image Analysis

 [**TIP**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=83): IEEE Transactions on Image Processing

[**TBME**](https://tbme.embs.org/) : IEEE Transactions on Biomedical Engineering 
