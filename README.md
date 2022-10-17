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
 ![Screenshot from 2022-10-17 22-46-30](https://user-images.githubusercontent.com/25703407/196241526-7e5a7aee-7341-4033-8c6c-9282dae5c4a0.png)
 I have used custom data set class if we want to make a pytorch custom class we have to pass Pytorch Dataset to the class then it would become a pytorch
 class
 
 Custom dataset classes have three important methods
 * def_init_ ()
 In this, we pass root path and inside in this method augmentation part works
 * def__getitem__()
 Returns all images input and  all images labels
 * def_len_()
 Length method calculates images count
 ![Screenshot from 2022-10-17 23-34-26](https://user-images.githubusercontent.com/25703407/196250344-76708825-df09-4bb4-9a57-df50e672c18f.png)
 
 Custom Classification model has  two important models
 * def __init__()
 * def __forward ()
I worked on custom classification model used Conv 3 input channel to 16 channel output  by applying (5,5,) filters and used max-pooling of (2,2)
I worked on standard models likes 
 * Resnet18
 * Resnet34
 * Resnet50
 * Resnet101
 * Resnet 152
 
 First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
 





 
 



 
 
 
