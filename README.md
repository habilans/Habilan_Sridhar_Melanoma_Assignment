# Melanoma-Detection-Assignment
## Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion



![image](https://github.com/habilans/Melanoma-Detection-Assignment/assets/27769116/6f57b474-e578-4986-9930-cdc96495bb38)                

As you can clearly see the class imbalance from the above table. 
we have introduced 'Augmentor'  library to reduce the class imbalance problem and overfitting 

![image](https://github.com/habilans/Melanoma-Detection-Assignment/assets/27769116/b0d8223b-fbfc-4599-b138-d0100236786a)

As you can see after building the model on the Augmented dataset we can see that model can classify the cancer based on test image
