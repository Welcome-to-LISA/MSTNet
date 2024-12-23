# MSTNet
---------------------
TGRS paper "MSTNet: A Multilevel Spectral–Spatial Transformer Network for Hyperspectral Image Classification"
# Abstract
---------------------
Abstract—— Convolutional neural networks (CNNs) have been widely used in hyperspectral image classification (HSIC). Although the current CNN-based methods have achieved good performance, they still face a series of challenges. For example, the receptive field is limited, information is lost in down-sampling layer, and a lot of computing resources are consumed for deep networks. To overcome these problems, we proposed a multilevel spectral–spatial transformer network (MSTNet) for HSIC. The structure of MSTNet is an image-based classification framework, which is efficient and straightforward. Based on this framework, we designed a self-attentive encoder. First, HSIs are processed into sequences. Meanwhile, a learned positional embedding (PE) is added to integrate spatial information. Then, a pure transformer encoder (TE) is employed to learn feature representations. Finally, the multilevel features are processed by decoders to generate the classification results in the original image size. The experimental results based on three real hyperspectral datasets demonstrate the efficiency of the proposed method in comparison with the other related CNN-based methods.
# Paper Linking
---------------------
https://ieeexplore.ieee.org/document/9807344
# Citation
---------------------
**Please kingly cite the papers if this is something useful and helpful for your research.**

    @ARTICLE{9807344,
      author={Yu, Haoyang and Xu, Zhen and Zheng, Ke and Hong, Danfeng and Yang, Hao and Song, Meiping},
      journal={IEEE Transactions on Geoscience and Remote Sensing}, 
      title={MSTNet: A Multilevel Spectral–Spatial Transformer Network for Hyperspectral Image Classification}, 
      year={2022},
      volume={60},
      number={},
      pages={1-13},
      keywords={Transformers;Feature extraction;Convolutional neural networks;Hyperspectral imaging;Training;Data mining;Task analysis;Convolutional neural networks (CNNs);hyperspectral image (HSI);image-based classification;transformer},
      doi={10.1109/TGRS.2022.3186400}
    }
