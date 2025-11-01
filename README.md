# Improved-Conditional-GAN-Based-Channel-Estimation-for-MIMO-OFDM-Systems
Source codes of the article: [1] M. Ye et al., "Improved Conditional GAN-Based Channel Estimation for MIMO-OFDM Systems," in IEEE Transactions on Cognitive Communications and Networking, doi: 10.1109/TCCN.2025.  

 

If you use this simulation code package in any way, please cite the original paper [1] above. 
The author in charge of this simulation code pacakge is: Ming Ye (email: mye@seu.edu.cn).

Ackonwledge: We are very grateful for the author of following reference papers. Our source code is improved based on their source code. 
[19] P. Jiang, C. -K. Wen, S. Jin, and G. Y. Li, “Dual CNN-based channelestimation for MIMO-OFDM systems,” IEEE Trans. Commun., vol. 69,
no. 9, pp. 5859-5872, Sep. 2021.


[29] Y. Dong, H. Wang, and Y.-D. Yao, “Channel estimation for one-bit multiuser massive MIMO using conditional GAN,” IEEE Commun. Lett.,
vol. 25, no. 3, pp. 854–858, Mar. 2021.

Please note that the MATLAB R2020a, Python 3.8 and Tensorflow 2.6.0 are used for this simulation code package,  and there may be some imcompatibility problems among different versions. 

*********************************************************************************************************************************
How to use this simulation code package?

This folder contains codes for channel estimation executed in Python.

Channel data generation:  Channel data generation is performed in MATLAB, and the accompanying archive data.zip contains both the raw channel data and the Least Squares (LS) channel estimates.
 
Channel estimation: Use the script main_cGAN521.py from the archive tex5_cGAN52.zip to train and test the proposed improved cGAN.

 
[tex5_cGAN52.zip](https://github.com/user-attachments/files/23262987/tex5_cGAN52.zip)    

*********************************************************************************************************************************
It is noted that there may be some differences in the results of different training processes. 

Enjoy the reproducible research!

