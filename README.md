
# Semantic Segmentation using U-NET with VGG-11 backbone pretrained on ImageNet 


A [Pytorch](https://pytorch.org/) implementation of 
[TernausNet](https://arxiv.org/pdf/1801.05746).

• Carried out semantic image segmentation on the [Kaggle Carvana Dataset](https://www.kaggle.com/c/carvana-image-masking-challenge).  
• Carried out data augmentation using python's [Albumentations library](https://albumentations.ai/).


![alt text](https://camo.githubusercontent.com/790b10b4232e4c1b4cab99cc0d96668fe978184c0e4ad581a1da1f361fead886/68747470733a2f2f686162726173746f726167652e6f72672f776562742f68752f6a692f69722f68756a696972767067706637657377713838685f783761686c69772e706e67)

## Results 

Achieved a Dice score = 98.7, Test set accuracy = 99.46
 



## Environment Variables

### Hardware requirements
A server containing CUDA enabled GPU with compute capability 3.5 or above.


### Software requirements

`Pytorch version 0.4.1`   

`CUDA version 8+`  

`Python version 3.5+` 

`Albumentations` 





## References

```
@ARTICLE{arXiv:1801.05746,
         author = {V. Iglovikov and A. Shvets},
          title = {TernausNet: U-Net with VGG11 Encoder Pre-Trained on ImageNet for Image Segmentation},
        journal = {ArXiv e-prints},
         eprint = {1801.05746},
           year = 2018
        }
```
