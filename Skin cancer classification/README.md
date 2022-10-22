# Skin cancer classification

The original task "Lesion Classfication" and the full data (2000 images for training)  is obtained from the [ISIC 2017 Challenge](https://challenge.isic-archive.com/landing/2017/44). For this project, only 125 images were used for training, 45 images for validation and 45 images for testing.

Goal: distinguish between melanoma (0), nevus (1) and seborrheic keratosis (2).
Keypoints:
- The model uses MobileNetV2 as transfer learning model.
- The accuracy of this model is 90%.
- Melanoma is a maglinant type of skin cancer. In the test set, they are all predicted as melanoma. 
![accuracy](https://user-images.githubusercontent.com/39226353/197338514-158e731e-08cd-4749-bec0-03cd169976ba.png)

![confusionmatrix](https://user-images.githubusercontent.com/39226353/197338661-baca0d89-c8a7-4419-a45f-021f6cd02e6a.png)
