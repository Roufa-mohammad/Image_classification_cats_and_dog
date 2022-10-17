# Image classification using pytorch
It is defined as the task of classifying an image from a fixed set of categories. Many other computer vision challenges such as object detection and segmentation can be reduced to image classification

### Content:
 * imported pytorch libraries
 * used standard models
 * Applied custom classification models
 * Applied Custom classification Modle 
 
 Imported necessary libraries to work on image classification
 ![Screenshot from 2022-10-17 22-13-37](https://user-images.githubusercontent.com/25703407/196237091-133ad4ce-37fe-4e47-9a41-9f86e3b9740c.png)
 
 Torch and Tochvision have all the required packages to work on image classification and 
 i used custom and standard models with the help of torch.nn
 ![Screenshot from 2022-10-17 22-33-21](https://user-images.githubusercontent.com/25703407/196239921-94e8c81a-12c9-454c-a7f8-59b2f9d230e0.png)
 The data augmentation and normalizing are required before we pass our input to the model  doing such operations our model works properly
 
 cropped the image and resized to (224*224) Horizontal and Vertical crop which uses to improve  composition by removing unwanted regions 
 * HorizontalFlip of image 
 * Converted image to tensor
 * Normalizes images Channels [RGB]
 ![Screenshot from 2022-10-17 22-33-55](https://user-images.githubusercontent.com/25703407/196240520-31fa9619-403e-4d5a-b403-be674dfc55a9.png)
 I gave the local image path to the variable and pass this image path to Dataloader this Dataloader have a parameter like batch size, num _works, etc..
 
 pytorch custom data class
 
 
 



 
 
 
