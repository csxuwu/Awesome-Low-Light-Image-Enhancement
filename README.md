# Awesome-Low-Light-Image-Enhancement

![Paper Reading](https://img.shields.io/badge/PhD-Paper_Reading-green)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Paper Reading](https://img.shields.io/badge/Fields-CV_ML_PR_DM-blue)

This is a collection of awesome papers I have read (carefully or roughly) in the fields of low-light image enhancement (where the notes only represent my personal views). The collection will be continuously updated, so stay tuned. Any suggestions and comments are welcome (csxunwu@gmail.com). 


## Contents
- [Datsets](#Datsets)
  - [Paired](#Paired)
  - [Unpaired](#Unpaired) 
- [Traditional Methods](#Traditional)
  - [HE-based](#HE)
  - [Dehaze-based](#Dehaze)
  - [Retinex-based](#Retinex)
- [Deep Learning Methods](#Deep)
  - [Reference](#Reference)
  - [Unreference](#Unreference)
- [Survey](#Survey)
- [Learning Sources](#Learning)


<a name="Datsets" />

## Datsets [[Back to Top]](#Datsets)

<a name="Paired" />

### Paired

1. **DICM** Lee C, Lee C, Kim C S. Contrast enhancement based on layered difference representation of 2D histograms[J]. IEEE transactions on image processing, 2013, 22(12): 5372-5384.
1. **NPE** Wang S, Zheng J, Hu H M, et al. Naturalness preserved enhancement algorithm for non-uniform illumination images[J]. IEEE transactions on image processing, 2013, 22(9): 3538-3548.
1. **MEF** Ma K, Zeng K, Wang Z. Perceptual quality assessment for multi-exposure image fusion[J]. IEEE Transactions on Image Processing, 2015, 24(11): 3345-3356.
1. **LIME** Guo X, Li Y, Ling H. LIME: Low-light image enhancement via illumination map estimation[J]. IEEE Transactions on image processing, 2016, 26(2): 982-993.
1. **ExDark** Loh Y P, Chan C S. Getting to know low-light images with the exclusively dark dataset[J]. Computer Vision and Image Understanding, 2019, 178: 30-42.
1. **Dark Face** Yang W, Yuan Y, Ren W, et al. Advancing image understanding in poor visibility environments: A collective benchmark study[J]. IEEE Transactions on Image Processing, 2020, 29: 5737-5752.

1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()

<a name="Unpaired" />

### Unpaired

1. **LOL** Wei C, Wang W, Yang W, et al. Deep retinex decomposition for low-light enhancement[J]. arXiv preprint arXiv:1808.04560, 2018.
1. **SID** Chen C, Chen Q, Xu J, et al. Learning to see in the dark[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2018: 3291-3300.
1. **CID** Fu Q, Di X, Zhang Y. Learning an adaptive model for extreme low‐light raw image processing[J]. IET Image Processing, 2020, 14(14): 3433-3443.
1. **VE-LOL** Liu J, Xu D, Yang W, et al. Benchmarking low-light image enhancement and beyond[J]. International Journal of Computer Vision, 2021, 129: 1153-1184.

1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()


<a name="Traditional" />

## Traditional Methods [[Back to Top]](#Traditional)

<a name="HE" />


### HE-based


1. Pizer S M, Amburn E P, Austin J D, et al. Adaptive histogram equalization and its variations[J]. Computer vision, graphics, and image processing, 1987, 39(3): 355-368.
1. Zuiderveld, K.J. Contrast limited adaptive histogram equalization, Graphics gems, 1994.
1. Stark J A. Adaptive image contrast enhancement using generalizations of histogram equalization[J]. IEEE Transactions on Image Processing (TIP), 2000, 9(5): 889-896.
1. Arici T, Dikbas S, Altunbasak Y. A histogram modification framework and its application for image contrast enhancement[J]. IEEE Transactions on Image Processing (TIP), 2009, 18(9): 1921-1935.
1. Celik T, Tjahjadi T. Contextual and variational contrast enhancement[J]. IEEE Transactions on Image Processing (TIP), 2011, 20(12): 3431-3441.
1. Lee C, Lee C, Kim C S. Contrast enhancement based on layered difference representation of 2D histograms[J]. IEEE Transactions on Image Processing (TIP), 2013, 22(12): 5372-5384.
1. Zhuang L, Guan Y. Adaptive Image Enhancement Using Entropy-Based Subhistogram Equalization[J]. Computational Intelligence and Neuroscience, 2018, 2018:1-13.
1. Mun J, Jang Y, Nam Y, et al. Edge-enhancing bi-histogram equalisation using guided image filter[J]. Journal of visual communication & image representation, 2019, 58(JAN.):688-700.
1. Liu C, Sui X, Liu Y, et al. Adaptive contrast enhancement based on histogram modification framework[J]. Journal of Modern Optics, 2019, 66(15): 1590-1601.
1. Veluchamy M, Subramani B. Image contrast and color enhancement using adaptive gamma correction and histogram equalization[J]. Optik, 2019, 183: 329-337.


1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()


<a name="Dehaze" />

### Dehaze-based


1. Dong X, Wang G, Pang Y, et al. Fast efficient algorithm for enhancement of low lighting video[C]//2011 IEEE International Conference on Multimedia and Expo (ICME). IEEE, 2011: 1-6.
1. Zhang X, Shen P, Luo L, et al. Enhancement and noise reduction of very low light level images[C]//Proceedings of the 21st International Conference on Pattern Recognition (ICPR). IEEE, 2012: 2034-2037.
1. Li L, Wang R, Wang W, et al. A low-light image enhancement method for both denoising and contrast enlarging[C]//2015 IEEE International Conference on Image Processing (ICIP). IEEE, 2015: 3730-3734.
1. Song J, Zhang L, Shen P, et al. Single low-light image enhancement using luminance map[C]//Chinese Conference on Pattern Recognition (CCPR). Springer, Singapore, 2016: 101-110.
1. Feng B, Tang Y, Zhou L, et al. Image enhancement under low luminance with strong light weakening[C]//2016 8th International Conference on Wireless Communications & Signal Processing (WCSP). IEEE, 2016: 1-5.


1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()


<a name="Retinex" />

### Retinex-based 

1. Land E H. The retinex[J]. American Scientist, 1964, 52(2): 247-264.
1. Land E H, McCann J J. Lightness and retinex theory[J]. Josa, 1971, 61(1): 1-11.
1. Jobson D J, Rahman Z, Woodell G A. Properties and performance of a center/surround retinex[J]. IEEE Transactions on Image Processing (TIP), 1997, 6(3): 451-462.
1. Rahman Z, Jobson D J, Woodell G A. Multi-scale retinex for color image enhancement[C]//Proceedings of 3rd IEEE International Conference on Image Processing (ICIP). IEEE, 1996, 3: 1003-1006.
1. Jobson D J, Rahman Z, Woodell G A. A multiscale retinex for bridging the gap between color images and the human observation of scenes[J]. Transactions on Image Processing (TIP), 1997, 6(7): 965-976.
1. Palma-Amestoy R, Provenzi E, Bertalmío M, et al. A perceptually inspired variational framework for color enhancement[J]. IEEE transactions on pattern analysis and machine intelligence, 2008, 31(3): 458-474.
1. Wang S, Zheng J, Hu H M, et al. Naturalness preserved enhancement algorithm for non-uniform illumination images[J]. IEEE Transactions on Image Processing (TIP), 2013, 22(9): 3538-3548.
1. Fu X, Sun Y, LiWang M, et al. A novel retinex based approach for image enhancement with illumination adjustment[C]//2014 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2014: 1190-1194.
1. Fu X, Zeng D, Huang Y, et al. A weighted variational model for simultaneous reflectance and illumination estimation[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2016: 2782-2790.
1. Guo X, Li Y, Ling H. LIME: Low-light image enhancement via illumination map estimation[J]. IEEE Transactions on Image Processing (TIP), 2016, 26(2): 982-993.
1. Li M, Liu J, Yang W, et al. Structure-Revealing Low-Light Image Enhancement Via Robust Retinex Model[J]. IEEE Transactions on Image Processing (TIP), 2018, PP(99):1-1.
1. Hao S, Feng Z, Guo Y. Low-light image enhancement with a refined illumination map[J]. Multimedia Tools and Applications, 2018, 77(22): 29639-29650.
1. Fu G, Duan L, Xiao C. A Hybrid L 2− L P Variational Model For Single Low-Light Image Enhancement With Bright Channel Prior[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 1925-1929.

1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()

<a name="Deep" />

## Deep Leanring Methods [[Back to Top]](#Deep)

<a name="Reference"/>

### Reference
1. Lore K G, Akintayo A, Sarkar S. LLNet: A deep autoencoder approach to natural low-light image enhancement[J]. Pattern Recognition, 2017, 61: 650-662.
1. Shen L, Yue Z, Feng F, et al. Msr-net: Low-light image enhancement using deep convolutional network[J]. arXiv preprint arXiv:1711.02488, 2017.
1. Wei C, Wang W, Yang W, et al. Deep retinex decomposition for low-light enhancement[J]. arXiv preprint arXiv:1808.04560, 2018.
1. Gharbi M, Chen J, Barron J T, et al. Deep bilateral learning for real-time image enhancement[J]. ACM Transactions on Graphics (TOG), 2017, 36(4): 1-12.
1. Wang R, Zhang Q, Fu C W, et al. Underexposed photo enhancement using deep illumination estimation[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2019: 6849-6857.
1. Karadeniz A S, Erdem E, Erdem A. Burst Denoising of Dark Images[J]. arXiv preprint arXiv:2003.07823, 2020.
1. Fu Q, Di X, Zhang Y. Learning an adaptive model for extreme low-light raw image processing[J]. IET Image Processing, 2020, 14(14): 3433-3443.
1. 江泽涛, 覃露露.一种基于U-Net 生成对抗网络的低照度图像增强方法[J]. 电子学报. 2020 Vol. 48 (2): 258-264.
1. 江泽涛,覃露露,秦嘉奇等.一种基于MDARNet的低照度图像增强方法[J].软件学报,2021,32(12):3977-3991.DOI:10.13328/j.cnki.jos.006112.
1. 江泽涛,伍旭,张少钦.一种基于MR-VAE的低照度图像增强方法[J].计算机学报,2020,43(07):1328-1339.
1. 江泽涛,钱艺,伍旭等.一种基于ARD-GAN的低照度图像增强方法[J].电子学报,2021,49(11):2160-2165.
1. Meng Z, Xu R, Ho C M. GIA-Net: Global Information Aware Network for Low-light Imaging[C]//European Conference on Computer Vision (ECCV). Springer, Cham, 2020: 327-342.
1. Zamir S W, Arora A, Khan S, et al. Learning enriched features for real image restoration and enhancement[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 45, no. 2, pp. 1934–1948, 2023
1. Kim H U, Koh Y J, Kim C S. Global and Local Enhancement Networks for Paired and Unpaired Image Enhancement[C]//European Conference on Computer Vision (ECCV). Springer, Cham, 2020: 339-354.
1. Wang Y, Jiang Z, Liu C, et al. Shed Various Lights on a Low-Light Image: Multi-Level Enhancement Guided by Arbitrary References[J]. arXiv preprint arXiv:2101.00813, 2021.
1. Y. Yang, Y. Zhang, and X. Guo. Low-light image enhancement via feature restoration. in IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2022, pp. 2440–2444.
1. X. Xu, R. Wang, C.-W. Fu, and J. Ji. Snr-aware low-light image enhancement. in IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022, pp. 17 693–17 703.


1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()

<a name="Unreference"/>

### Unreference

1. Chen Y S, Wang Y C, Kao M H, et al. Deep photo enhancer: Unpaired learning for image enhancement from photographs with gans[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018: 6306-6314.
1. Jiang Y, Gong X, Liu D, et al. Enlightengan: Deep light enhancement without paired supervision[J]. IEEE Transactions on Image Processing (TIP), 2021, 30: 2340-2349.
1. Guo C, Li C, Guo J, et al. Zero-reference deep curve estimation for low-light image enhancement[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR). 2020: 1780-1789.
1. Guo C, Li C, Guo J, et al. Learning to enhance low-light image via zero-reference deep curve estimation[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021, 44(8): 4225-4238.


1. **Updating....** * et al, .*  [[PDF]]() [[Author]]()

<a name="Survey"/>

## Survey [[Back to Top]](#Survey)

1. **A Survey on Learning to Hash.** *Jingdong Wang et al, IEEE TPAMI 2018.*  [[PDF]](https://ieeexplore.ieee.org/abstract/document/7915742) [[Author]](https://jingdongwang2017.github.io/) 


<a name="Learning" />

## Learning Sources [Back to Top](#Learning)

1. **UvA Deep Learning Tutorials.** [[Website]](https://uvadlc-notebooks.readthedocs.io/en/latest/index.html)   

1. **PyTorch Image Models (timm) Documentation** [[Website]](https://github.com/rwightman/pytorch-image-models)

1. **PyTorch Geometric (PyG) Documentation** [[Website]](https://pytorch-geometric.readthedocs.io/en/latest/)

1. **Deep Graph Library (DGL) Tutorials and Documentation** [[Website]](https://docs.dgl.ai/en/latest/)

1. **PyTorch Lightning Documentation** [[Website]](https://pytorch-lightning.readthedocs.io/en/stable/)

1. **Qiskit Machine Learning Documentation** [[Website]](https://qiskit.org/documentation/machine-learning/index.html)

1. **Interpretable Machine Learning** [[Website]](https://christophm.github.io/interpretable-ml-book/)
