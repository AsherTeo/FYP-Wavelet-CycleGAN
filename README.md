# FYP-Wavelet-CycleGAN

Introduction

With the advent of technology, self-driving mobile also known as Autonomous Vehicle (AV) will gradually find its way into our daily lives in the coming years. However, environmental noise such as rain will disrupt the path of the AV which may result in accidents. To eliminate such risks, many researchers have been innovating and implementing new methods to remove rain. The most recent rain removal algorithms are the ID CGAN (Image De-raining using Conditional Generative Adversarial Network) & CycleGAN. 

Below are example of Real Rain Image (LEFT), Rain Removal by CycleGAN (MIDDLE), Zoom-in rain-streak (RIGHT). 

![github-2](https://user-images.githubusercontent.com/78581569/216314764-6e1a4130-db0c-48ee-a526-a1278ee43b24.PNG)

Wavelet Transform

We proposed Haar Wavelet as our Wavelet Transform. Haar wavelet one of the simplest WT uses an orthogonal and square function on the intervals of [0,1] to capture the frequency components in every spectrum. The input and the output coefficients are equal, thus, is recommended for image reconstruction. The diagram below shown the level 1 Wavelet Decomposition Tree.

![image](https://user-images.githubusercontent.com/78581569/216279525-ddef9b4a-c152-460b-84f1-a8a2afe6eb2e.png)

In Discrete Wavelet Transform, signals are filtered by the low pass and high pass filter denoted as g(n) and h(n) shown in the above diagram. The two frequency sub bands are then further decomposed by applying low pass and high pass filter on g(n) and h(n) to produce four different down sampled frequency components. They are the LL (Approximation), LH (Horizontal), HL (Vertical), HH (Diagonal) shown below respectively.

![image](https://user-images.githubusercontent.com/78581569/216280595-fff912a1-e589-4bf5-9671-935d53cf5058.png) 
![image](https://user-images.githubusercontent.com/78581569/216280616-99dafefe-941d-4f95-a967-e991ac44f7a1.png)
![image](https://user-images.githubusercontent.com/78581569/216280636-e1dff99f-915e-4caa-8cba-08cd969b6e8a.png)
![image](https://user-images.githubusercontent.com/78581569/216280658-e7efb6ad-9b4a-4ad4-9f60-1366ecd27119.png)



Solution

![image](https://user-images.githubusercontent.com/78581569/216277954-586da1e0-47e2-489b-a0e1-ae3b446abf96.png)
![image](https://user-images.githubusercontent.com/78581569/216277991-e6f4ae87-ab2c-4a7d-8e18-7e91ce788447.png)



