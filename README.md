# Stadv-Deepfake-Detection
This Repository contains the PyTorch Implementation for the ICLR'18 paper 《Spatially Transformed Adversarial Examples》
## Dataset
DFFD:http://cvlab.cse.msu.edu/dffd-dataset.html
The DFFD dataset is comprised of multiple publically available datasets and images that are synthesized/manipulated using publically available methods. By incorporating multiple sources for real images, we are able to include varying resolution and image quality for both real and synthetic/manipulated images. 
![image](https://user-images.githubusercontent.com/44827203/210598433-26484176-c189-4fb3-83c2-95e56998d238.png)
## Model
XnceptionNet, MesoNet, MesoInceptionNet
## Attack method
FGSM, PGD, stAdv
An example of stAdv generated adversarial example
![image](https://user-images.githubusercontent.com/44827203/210599137-984bba46-4ab2-442b-be64-44789b9baec7.png)
