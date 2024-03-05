# Relation Extraction (COMP61332 Group Coursework)
  This Project is temporarily used for the group coursework, which contains two function of Relation extraction.
  1. BiLSTM, 2. Bert (pretrained model: bert-base-cased)
# Group Member:
  Junfan Cheng, Tong Shen, Qiujie Xu, Yuxuan Zhang

# Dataset
  The dataset applied in this project is only the "NYT" part of [UniRel Model](https://github.com/wtangdev/UniRel/blob/main/README.md), which data can also be downloaded from [the shared drive link](https://drive.google.com/file/d/1-3uBc_VfaCEWO2_FegzSyBXNeFmqhv7x/view)
  
  The dataset is originally obtained from TPLinker, refer to [TPLinker officail repository](https://github.com/131250208/TPlinker-joint-extraction). 
  
  The path of dataset files: ./model_data

# Trained Model file
  The trained model of this assignment has been upload.
  1: BiLSTM (./trained_model/BiLSTM_xxxx.h5)
  2: As the size of bert model overs the limitation of github, the result can be found by [this link](https://drive.google.com/drive/folders/17gy7A6w-dHqTzw7Bmkcfe4H0ApJ1ePSE?usp=drive_link).

# Result

# Citation
```
@inproceedings{tang-etal-2022-unirel,
    title = "{U}ni{R}el: Unified Representation and Interaction for Joint Relational Triple Extraction",
    author = "Tang, Wei  and
      Xu, Benfeng  and
      Zhao, Yuyue  and
      Mao, Zhendong  and
      Liu, Yifeng  and
      Liao, Yong  and
      Xie, Haiyong",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emnlp-main.477",
    pages = "7087--7099",
}
```
```
@article{nayak2019effective,
  title={Effective attention modeling for neural relation extraction},
  author={Nayak, Tapas and Ng, Hwee Tou},
  journal={arXiv preprint arXiv:1912.03832},
  year={2019}
}
```
