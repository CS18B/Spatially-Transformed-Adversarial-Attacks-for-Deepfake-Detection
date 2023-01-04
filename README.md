# Stadv-Deepfake-Detection
This Repository contains the PyTorch Implementation for the ICLR'18 paper 《Spatially Transformed Adversarial Examples》
## Dataset


The [DFFD dataset](http://cvlab.cse.msu.edu/dffd-dataset.html) is comprised of multiple publically available datasets and images that are synthesized/manipulated using publically available methods. By incorporating multiple sources for real images, we are able to include varying resolution and image quality for both real and synthetic/manipulated images.

![image](https://user-images.githubusercontent.com/44827203/210598433-26484176-c189-4fb3-83c2-95e56998d238.png)
## Model
XnceptionNet(99.7 acc), MesoNet(95.3 acc), MesoInceptionNet(93.2 acc)
## Attack method
FGSM, PGD, stAdv

An example of stAdv generated adversarial example

![image](https://user-images.githubusercontent.com/44827203/210599137-984bba46-4ab2-442b-be64-44789b9baec7.png)
