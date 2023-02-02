# FYP-Wavelet-CycleGAN

Introduction

With the advent of technology, self-driving mobile also known as Autonomous Vehicle (AV) will gradually find its way into our daily lives in the coming years. However, environmental noise such as rain will disrupt the path of the AV which may result in accidents. To eliminate such risks, many researchers have been innovating and implementing new methods to remove rain. The most recent rain removal algorithms are the ID CGAN (Image De-raining using Conditional Generative Adversarial Network) & CycleGAN.

Real Rain Image (LEFT), Rain Removal by CycleGAN (MIDDLE), Zoom-in rain-streak (RIGHT)


![image](https://user-images.githubusercontent.com/78581569/216276887-1d614649-5bd0-470d-b559-524d081280c7.png) 
![image](https://user-images.githubusercontent.com/78581569/216276918-e0443fe3-0904-4dba-8e4a-1ae6b2ab3131.png) 
![image](https://user-images.githubusercontent.com/78581569/216277033-1d98d669-ce7f-4adb-9c40-b8ea8393ce5a.png)


Wavelet Transform

Haar Wavelet is used in this proposed solution. Haar wavelet one of the simplest WT uses an orthogonal and square function on the intervals of [0,1] to capture the frequency components in every spectrum. The input and the output coefficients are equal, thus, is recommended for image reconstruction. The diagram below shown the level 1 Wavelet Decomposition Tree.

![image](https://user-images.githubusercontent.com/78581569/216279525-ddef9b4a-c152-460b-84f1-a8a2afe6eb2e.png)



Solution

![image](https://user-images.githubusercontent.com/78581569/216277954-586da1e0-47e2-489b-a0e1-ae3b446abf96.png)
![image](https://user-images.githubusercontent.com/78581569/216277991-e6f4ae87-ab2c-4a7d-8e18-7e91ce788447.png)



