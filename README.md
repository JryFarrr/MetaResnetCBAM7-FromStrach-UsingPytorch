**Real-Waste Image Classification using MetaResnetCBAM7 From Stracth Using Pytorch**
-----------------------------------------------------------------

**Overview**
-----------------------------------------------------------------

An image classification dataset of waste items across 9 major material types, collected within an authentic landfill environment.

**Dataset Information**
----------------------------------------------------------------

For what purpose was the dataset created?
RealWaste was created as apart of an honors thesis researching how convolution neural networks could perform on authentic waste material when trained on objects in pure and unadulterated forms, when compared to training via real waste items.

What do the instances in this dataset represent?
Color images of waste items captured at the point of reception in a landfill environment. Images are released in 524x524 resolution in line with accompanying research paper. For full size resolution images, please contact the corresponding author.

**Additional Information**
---------------------------------------------------------------

The labels applied to the images represent the material type present, however further refinement of labelling may be performed given the moderate dataset size (i.e., splitting the plastic class in transparent and opaque components). Under the proposed labels, image counts are as follows:

Cardboard: 461
Food Organics: 411
Glass: 420
Metal: 790
Miscellaneous Trash: 495
Paper: 500
Plastic: 921
Textile Trash: 318
Vegetation: 436
Has Missing Values?

No

**Introductory Paper**
---------------------------------------------------------------

RealWaste: A Novel Real-Life Data Set for Landfill Waste Classification Using Deep Learning
https://www.mdpi.com/2078-2489/14/12/633
By Sam Single, Saeid Iranmanesh, Raad Raad. 2023
Published in Information

**Class Labels**
--------------------------------------------------------------

Cardboard, Food Organics, Glass, Metal, Miscellaneous Trash, Paper, Plastic, Textile Trash, and Vegetation

Model Architecture

![model_architecture](https://github.com/user-attachments/assets/c29a6ab5-628f-4118-aa6e-4364d1a22839)

Prediction Result

![image](https://github.com/user-attachments/assets/c3185c5d-3073-446a-9914-9cece6c28a6c)
