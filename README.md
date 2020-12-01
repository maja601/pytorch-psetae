# Code Adaption of _Satellite Image Time Series Classification with Pixel-Set Encoders and Temporal Self-Attention (CVPR 2020, Oral)_


Adapted PyTorch implementation of the model presented in 
["Satellite Image Time Series Classification with Pixel-Set Encoders 
and Temporal Self-Attention"](https://openaccess.thecvf.com/content_CVPR_2020/html/Garnot_Satellite_Image_Time_Series_Classification_With_Pixel-Set_Encoders_and_Temporal_CVPR_2020_paper.html) published ar CVPR 2020.


[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Garnot_Satellite_Image_Time_Series_Classification_With_Pixel-Set_Encoders_and_Temporal_CVPR_2020_paper.html) abstract:

*Satellite image time series, bolstered by their growing availability, are at the forefront of an extensive effort towards 
automated Earth monitoring by international institutions. In particular, large-scale control of agricultural parcels is 
an issue of major political and economic importance. In this regard, hybrid convolutional-recurrent neural architectures 
have shown promising results for the automated classification of satellite image time series. We propose 
an alternative approach in which the convolutional layers are advantageously replaced with encoders operating 
on unordered sets of pixels to exploit the typically coarse resolution of publicly available satellite images. 
We also propose to extract temporal features using a bespoke neural architecture based on self-attention 
instead of recurrent networks. We demonstrate experimentally that our method not only outperforms previous 
state-of-the-art approaches in terms of precision, but also significantly decreases processing time and memory 
requirements. Lastly, we release a large open-access annotated dataset as a benchmark 
for future work on satellite image time series.*


## Credits

- The **Temporal Attention Encoder** is heavily inspired by 
[the works of Vaswani et al.](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf) on the Transformer, 
and [this pytorch implementation](https://github.com/jadore801120/attention-is-all-you-need-pytorch) 
served as code base for the TAE.py script. 
- Credits to  github.com/clcarwin/ for [the pytorch implementation](github.com/clcarwin/focal_loss_pytorch) 
of the focal loss


```
@article{garnot2019psetae,
  title={Satellite Image Time Series Classification with Pixel-Set Encoders and Temporal Self-Attention},
  author={Sainte Fare Garnot, Vivien  and Landrieu, Loic and Giordano, Sebastien and Chehata, Nesrine},
  journal={CVPR},
  year={2020}
}

```
