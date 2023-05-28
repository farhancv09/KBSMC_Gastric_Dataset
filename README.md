# KBSMC_Gastric_Dataset

This dataset has been introduced in the paper "Multi-Cell Type and Multi-Level Graph Aggregation Network for Cancer Grading in Pathology Images" by Syed Farhan Abbas,
Trinh Thi Le Vuong, Jin Tae Kwak, Kyungeun Kim, Boram Song ([Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4232906)). 
## Description
**Gastric cancer** is the leading type of cancer in Korea. This dataset has been collected from the Kangbuk Samsung Medical Hospital (KSMH), Seoul, South Korea. The 96 WSI has been collected form the **96** patients from 2018-2020. The digitized images were taken at **40x** magnification using an **Aperio digital slide scanner (Leica Biosystems)**. The size of a WSI is ∼100,000 x ∼80,000 with **0.2635 μm x 0.2635** μm pixel spacing. Each WSI was examined by experienced pathologists Kyungeun Kim
,Sungkyunkwan University School of Medicine and Boram Song, Sungkyunkwan University School of Medicine to identify distinct tissue regions, including Benign **(BN)**, tubular well-differentiated adenocarcinoma **(TW)**, tubular Moderatly-differentiated adenocarcinoma **(TM)**, and tubular poorly-differentiated adenocarcinoma **(TP)**. There are some types of cancer  Using these tissue regions, we generated image patches of size **1024 x 1024** pixels that are split into training, validation, and test data. Sample Images are shown below. 

![](gastric_data.png)

# Download
Whole dataset of 96 WSI are divided into three folders named as Train, Valid and Test. 
Dataset is publicaly available at [here](https://drive.google.com/drive/folders/1lNhdk392O5tE1Bd6omkqrSBlO6BpyIKF)



# Details about Dataset and Naming Convention
| ** Type**  | **Train**    | **Valid**    | **Test**    | **Naming Convention/ Label** |               
|------------|--------------|--------------|-------------|------------------------------- 
|    Benign  |     150063   |    29790     |     26221   |              1,2             |
|     WD     |     14162    |    8809      |     7197    |              3               |
|     MD     |     20808    |    9510      |     9892    |              4               |
|     PD     |     27597    |    9464      |     4386    |              5               |

**Naming Convention:**
**patch_number_class_Label.jpg**. Example: patch_1995_class_2.jpg, here **2** Represent the label of image.
There are other adenocarcinoma images are available which are labeled as  **6,7,8,9,10,11**. But we didn't those images in this paper.

# Citation
If you use this dataset either entirely or partially in your research, please cite the following paper::
<br />
```
@article{abbas4232906multi,
  title={Multi-Cell Type and Multi-Level Graph Aggregation Network for Cancer Grading in Pathology Images},
  author={Abbas, Syed Farhan and Vuong, Trinh Thi Le and Kim, Kyungeun and Song, Boram and Kwak, Jin Tae},
  journal={Available at SSRN 4232906}
}
```
