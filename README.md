# 3D-UNet
- A 3D-UNet architecture with the Squeeze-and-Excitation (SE) attention mechanism implementation.

## The 3D-UNet architecture comprises two parts: 
 - encoding path: 3D U-Net architecture with 3 levels of double 3D convolution and 3D max pooling
 - decoding path: 3D U-Net architecture with 3 levels of double 3D convolution and 3D upsampling

and the network architecture realizes end-to-end training.

## SE 
 - was used to focus on the advantages of feature channels, further improving the accuracy of the network

Based on the article: "Fault Recognition Method Based on Attention Mechanism and the 3D-UNet" by Ting Yu, Xin Wang,
Tong Jun Chen and Chang Wei Ding.
