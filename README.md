# UAGD: Uniform Age and Gender Dataset
**Paper**: *A comparison study: the impact of age and gender distribution on age estimation*

# Introduction
Dataset plays a very important role in age estimation task. Several available facial aging datasets have been established in recent decades. While, in some respects there are some drawbacks on these datasets. First of all, age distribution unbalance problem: most of datasets have a large number of adult faces and have ignored other age range data collection. Secondly, age labels also vary widely in terms of facial attributes like gender and race. Moreover, age label is really hard to label precisely compared to other vision tasks, and there are non-negligible differences between facial apparent and real age.

In this paper, we collect and clear up a new age dataset called Uniform Age and Gender Dataset(UAGD) which comes with several advantages: (1) it contains 11,852 facial images and age label range from 1 to 80 years old which could cover normal application environment; (2) the number of facial images per age class are almost the same which means our dataset has uniform age label distribution; (3) in addition, the number of female and male images are nearly equal in each age class.
![图片](https://user-images.githubusercontent.com/8656702/166145949-803d0cd7-195c-4793-8cfb-57f6b42b33c7.png)


# UAGD: Uniform Age and Gender Dataset
The source images of UAGD is manually selected from APPA-REAL, UTKFace and AgeDB datasets very carefully, which means only face images that are having large poses, containing noise pixels, bearing various expressions, and under different illuminations could be chosen. We also double clean and remove the images that have wrong or not pretty sure label by crowdsourcing platform. UAGD has almost the same number of female and male images in each age, about 75 female and 75 male, total 150 face.
![图片](https://user-images.githubusercontent.com/8656702/166145965-ca607f7b-163a-42e0-812e-3ab3b7970841.png)

## Download Link: 
**NOTE: Academic use ONLY**    
Google Drive: https://drive.google.com/file/d/1-69fWaalamYy_tk9SjxwVetGPr26B58U/view?usp=sharing   
Baidu Yun: 链接：https://pan.baidu.com/s/1foaJU5ruA4q3WuBRVf7utg 提取码：uagd   

# Citation
Please cite this paper in your publications if it helps your research:
```
@inproceedings{10.1145/3469877.3490576,
  author = {Kong, Chang and Luo, Qiuming and Chen, Guoliang},
  title = {A Comparison Study: The Impact of Age and Gender Distribution on Age Estimation},
  year = {2021},
  isbn = {9781450386074},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3469877.3490576},
  doi = {10.1145/3469877.3490576},
  booktitle = {ACM Multimedia Asia},
  articleno = {46},
  numpages = {5},
  keywords = {deep learning, age dataset, age estimation, CNN, DEX},
  location = {Gold Coast, Australia},
  series = {MMAsia '21}
}
```
