# Bachelor thesis
This work was done during my internship at [Imaging and Vision Laboratory](http://www.ivl.disco.unimib.it/).   
My bachelor thesis is about the recognition of vegetables and fruits in digital images using deep learning techniques.  
Our algorithm exploits different Convolutional Neural Networks specially trained on a collection of images from the [VegFru dataset](http://vim.ustc.edu.cn/?product=vegfru).  
VegFru categorizes vegetables and fruits according to their eating characteristics, and each image contains at least one edible part of vegetables or fruits with the same cooking usage.  
Particularly, all the images are labelled hierarchically. The current version covers vegetables and fruits of 25 upper-level categories and 292 subordinate classes and it contains more than 160K images in total and at least 200 images for each subordinate class.  
We use [pytorch](https://pytorch.org/) as a deep learning framework and [this](https://github.com/Cadene/pretrained-models.pytorch) for the implementation of NasNet-A architecture.  
[Recognition of Edible Vegetables and Fruits for Smart Home Appliances](https://www.researchgate.net/publication/329743507_Recognition_of_Edible_Vegetables_and_Fruits_for_Smart_Home_Appliances)  
[Online demo](http://ivldocker.disco.unimib.it/vegfru/)
