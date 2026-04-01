

## A Multi-Dimensional Adaptive Detector for Low-Altitude Fine-Grained Vehicles
This repository(MADet) is the official PyTorch implementation of the paper "A Multi-Dimensional Adaptive Detector for Low-Altitude Fine-Grained Vehicles".  

---
### The Illustration of MTFENet

<img src="pictures/MTFENet.png" alt="MTFENet" width="600" height="400"/>

---



<table>
  <tr>
    <td rowspan="2">
      <img src="PaperFigs/Fig1.png" width="400px" alt="MSCL-SwinUNet"/>
    </td>
    <td>
      <img src="PaperFigs/Fig5.png" width="300px" alt="ACDC Dataset"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src="PaperFigs/Fig6.png" width="300px" alt="MM-WHS Dataset"/>
    </td>
  </tr>
</table>




## Dataset

To evaluate the performance and generalization ability of the proposed MSCL-SwinUNet, we conducted experiments on three benchmark datasets across different imaging modalities.The **ACDC (Automatic Cardiac Diagnosis Challenge)** dataset is an MRI-based cardiac imaging dataset comprising **150 examinations** from different patients. It provides **pixel-level annotations** for **three anatomical structures**, namely the **left ventricle (LV)**, **right ventricle (RV)**, and **myocardium (MYO)**.The **MM-WHS (Multi-Modality Whole Heart Segmentation)** dataset includes **two imaging modalities**, consisting of **52 CT scans** and **46 MR scans**.To further assess cross-modality generalization, we employed the **Synapse multi-organ segmentation dataset**, which contains **3,779 CT images** spanning **30 anatomical categories**.


## MADet



#### Task1: Segmentation  on ACDC dataset

<table>
    <tr>
    <td><img src="PaperFigs\Fig7.png" width = "100%" alt="Single-Modality semantic segmentation"/></td>
    </tr>
</table>
  

#### Task2: Segmentation  on the MRI and CT subset of MM-WHS dataset

<table>
    <tr>
    <td><img src="PaperFigs\Fig8.png" width = "100%" alt="Single-Modality semantic segmentation"/></td>
    </tr>
</table>
  



#### Task3: Segmentation  on Synapse dataset

<table>
    <tr>
    <td><img src="PaperFigs\Fig9.png" width = "100%" alt="Single-Modality semantic segmentation"/></td>
    </tr>
</table>
  

## Description of MSCL-SwinUNet

If you have any question, please discuss with me by sending email to wq@cap.edu.cn.


# References
Many thanks to their excellent works


* **YOLOv11** – [Code](https://github.com/ultralytics/ultralytics)



