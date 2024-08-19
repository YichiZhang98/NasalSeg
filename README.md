# NasalSeg

**NasalSeg: A Dataset for Automatic Segmentation of Nasal Cavity and Paranasal Sinuses from 3D CT Images**
Yichi Zhang, Jing Wang, Tan Pan, Quanling Jiang, Jingjie Ge, Xin Guo, Chen Jiang, Jie Lu, Jianning Zhang, Xueling Liu, Mei Tian, Yuan Qi, Yuan Cheng, Chuantao Zuo


*  This repo provides the codebase and dataset of work NasalSeg，the first large-scale open-access annotated dataset for developing segmentation algorithms for nasal cavities and paranasal sinuses from 3D CT images.

*  The NasalSeg dataset consists of 130 CT scans with pixel-wise manual annotation of 5 nasal structures in great detail, including the left nasal cavity, right nasal cavity, nasal pharynx, left maxillary sinus, and right maxillary sinus.

*  Some information about the NasalSeg dataset is presented in the following.

![image](https://github.com/YichiZhang98/NasalSeg/blob/main/fig/example.png)

![image](https://github.com/YichiZhang98/NasalSeg/blob/main/fig/workflow.png)

Built upon [nnUNet](https://github.com/MIC-DKFZ/nnUNet), five-fold cross-validation experiments are conducted during the establishment of the NasalSeg dataset. The details are described in our paper.
