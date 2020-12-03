# Code Adaption of _Satellite Image Time Series Classification with Pixel-Set Encoders and Temporal Self-Attention (CVPR 2020, Oral)_ for the ML Reproducibility Challenge 2020

Adapted PyTorch implementation of the model presented in 
["Satellite Image Time Series Classification with Pixel-Set Encoders 
and Temporal Self-Attention"](https://openaccess.thecvf.com/content_CVPR_2020/html/Garnot_Satellite_Image_Time_Series_Classification_With_Pixel-Set_Encoders_and_Temporal_CVPR_2020_paper.html) published ar CVPR 2020.

## Credits

- The **Temporal Attention Encoder** is heavily inspired by 
[the works of Vaswani et al.](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf) on the Transformer, 
and [this pytorch implementation](https://github.com/jadore801120/attention-is-all-you-need-pytorch) 
served as code base for the TAE.py script. 
- Credits to  github.com/clcarwin/ for [the pytorch implementation](github.com/clcarwin/focal_loss_pytorch) 
of the focal loss
- The original implementation https://github.com/VSainteuf/pytorch-psetae
