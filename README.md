# Mobilenet-GAN
本repo利用MobileNet_v1中depth-wise seperable结构作为GAN的鉴定器，参数没有调到最优，因此训练过程不稳定且收敛较慢。笔者大概训练1280张图100+个epoch才达到差强人意的效果。代码下载即用，简单易懂。  

This repo take depth-wise seperable structure in Mobilenet_v1 as the discriminator of GAN.However the network is not perfectly optimized,so you may find it unstable and converge very slowly.It takes me 100+ epochs to train 1280 anime images to get a almost satisfing result. the code is easy to understand and free to take.  
DCGAN:  
![DCGAN](https://github.com/jasonrayshd/Mobilenet-GAN/blob/master/DCGAN.gif)  
MBN+GAN:  
![MBN+GAN](https://github.com/jasonrayshd/Mobilenet-GAN/blob/master/Depth-Wise%20Seperable%20GAN.gif)  
normalize imgs to 0,1 instead of -1,1:   
![normalize to 0,1 instead of -1,1](https://github.com/jasonrayshd/Mobilenet-GAN/blob/master/%E5%BD%92%E4%B8%80%E5%8C%96%E5%88%B0(0%2C1).gif)
