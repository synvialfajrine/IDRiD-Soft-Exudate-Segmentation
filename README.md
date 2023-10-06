# IDRiD Soft Exudates Segmentation

## Dataset
Dataset used in this assigment is taken from IDRiD, that can be retrieved from this [link](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid). The dataset consist of three dataset types:
A. Segmentation, B. Disease Grading, C. Localization. In this repository, we use A. Segmentation dataset which consist of original color fundus images (81 images divided into train and test set - JPG Files) and groundtruth images for the Lesions (Microaneurysms, Haemorrhages, Hard Exudates and Soft Exudates divided into train and test set - TIF Files) and Optic Disc (divided into train and test set - TIF Files)

## Method
In this repository, U-Net is chosen to be the architecture for soft exudate segmentation.

## Performance Average


## Conclusion
The approach applied to segment retinal vessel has high accuracy and specificity but still needs
improvement to get better result. The segmented images have noises and the vessel pixels can
not be detected thoroughly. There are some vessel pixels that loses in the segmentation
process.

## References
1. Q. Li, B. Feng, L. Xie, P. Liang, H. Zhang and T. Wang, "A Cross-Modality Learning Approach
for Vessel Segmentation in Retinal Images," in IEEE Transactions on Medical Imaging, vol. 35,
no. 1, pp. 109-118, Jan. 2016, doi: 10.1109/TMI.2015.2457891.
2. Özkaya, Umut & Öztürk, Şaban & Akdemir, Bayram & Seyfi, Levent, "An Efficient Retinal
Blood Vessel Segmentation using Morphological Operations", 2018, pp. 1-7,
10.1109/ISMSIT.2018.8567239.
3. Digital Retinal Images for Vessel Extraction (DRIVE). Available at (https://drive.grand-challenge.org/DRIVE/)[[https://drive.grandchallenge.org/DRIVE/](https://drive.grand-challenge.org/DRIVE/)https://drive.grand-challenge.org/DRIVE/]
