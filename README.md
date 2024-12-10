# NasalSeg: A Dataset for Automatic Segmentation of Nasal Cavity and Paranasal Sinuses from 3D CT Images

## Basic Information

*  This repo provides the codebase and dataset of NasalSeg，the first large-scale open-access annotated dataset for developing segmentation algorithms for nasal cavities and paranasal sinuses from 3D CT images.

*  The NasalSeg dataset consists of 130 CT scans with pixel-wise manual annotation of 5 nasal structures in great detail, including the left nasal cavity, right nasal cavity, nasal pharynx, left maxillary sinus, and right maxillary sinus. Please download the whole dataset from [here](https://zenodo.org/records/13893419).

*  Some information about the NasalSeg dataset is presented in the following.

![image](https://github.com/YichiZhang98/NasalSeg/blob/main/fig/example.png)

![image](https://github.com/YichiZhang98/NasalSeg/blob/main/fig/workflow.png)

Built upon [nnUNet](https://github.com/MIC-DKFZ/nnUNet), five-fold cross-validation experiments are conducted during the establishment of the NasalSeg dataset. Please refer to [the paper](https://www.nature.com/articles/s41597-024-04176-1) for more details.


## :books: Citation

If you use our dataset, please consider citing:
```
@article{zhang2024nasalseg,
  title={NasalSeg: A Dataset for Automatic Segmentation of Nasal Cavity and Paranasal Sinuses from 3D CT Images},
  author={Zhang, Yichi and Wang, Jing and Pan, Tan and Jiang, Quanling and Ge, Jingjie and Guo, Xin and Jiang, Chen and Lu, Jie and Zhang, Jianning and Liu, Xueling and others},
  journal={Scientific Data},
  volume={11},
  number={1},
  pages={1--5},
  year={2024},
  publisher={Nature Publishing Group}
}
```
