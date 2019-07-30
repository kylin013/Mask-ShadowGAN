# Mask-ShadowGAN


by Xiaowei Hu, Yitong Jiang, Chi-Wing Fu, and Pheng-Ann Heng

This implementation is written by Xiaowei Hu at the Chinese University of Hong Kong.

***


## Citation

@inproceedings{hu2019mask,        
&nbsp;&nbsp;&nbsp;&nbsp;  title={{Mask-ShadowGAN}: Learning to Remove Shadows from Unpaired Data},         
&nbsp;&nbsp;&nbsp;&nbsp;  author={Hu, Xiaowei and Jiang, Yitong and Fu, Chi-Wing and Heng, Pheng-Ann},         
&nbsp;&nbsp;&nbsp;&nbsp;  booktitle={ICCV},        
&nbsp;&nbsp;&nbsp;&nbsp;  year={2019},        
&nbsp;&nbsp;&nbsp;&nbsp;  note={to appear},       
}

        
## Requirement
* Python 3.5
* PyTorch 1.0
* torchvision
* numpy

  
## Train
1. Select the training sets (USR, SRD, or ISTD ) and set the path of the dataset in ```train_Mask-ShadowGAN.py```
2. Run ```train_Mask-ShadowGAN.py```


## Test   
1. Select the testing sets (USR, SRD, or ISTD ) and set the path of the dataset in ```test.py```
2. Run ```test.py```

