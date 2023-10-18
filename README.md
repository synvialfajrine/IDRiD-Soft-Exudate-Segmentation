# IDRiD Soft Exudates Segmentation

## Dataset
Dataset used in this assigment is taken from IDRiD, that can be retrieved from this [link](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid). The dataset consist of three dataset types:
A. Segmentation, B. Disease Grading, C. Localization. In this repository, we use A. Segmentation dataset which consist of original color fundus images (81 images divided into train and test set - JPG Files) and groundtruth images for the Lesions (Microaneurysms, Haemorrhages, Hard Exudates and Soft Exudates divided into train and test set - TIF Files) and Optic Disc (divided into train and test set - TIF Files)

## Method
In this repository, U-Net is chosen to be the architecture for soft exudate segmentation.

## Performance
Accuracy: 0.97351

F1: 0.41985

Jaccard: 0.33390

Recall: 0.39325

Precision: 0.84668

## Conclusion
The resulted segmentation model achieves high accuracy in identifying objects, but it struggles with capturing all relevant instances, indicating a low recall rate. The precision is high, signifying accurate positive predictions, but the model has difficulty in accurately pinpointing the exact location of objects resulting in more false positives.

## Reference
nikhilroxtomar. 2021. UNET.py. [https://github.com/nikhilroxtomar/Semantic-Segmentation-Architecture/blob/8e1e51f97ca3db7e8e41be6ee9c0a46dd56474c0/TensorFlow/unet.py](https://github.com/nikhilroxtomar/Semantic-Segmentation-Architecture/blob/8e1e51f97ca3db7e8e41be6ee9c0a46dd56474c0/TensorFlow/unet.py)
