# Introduction
On the road, in addition to traffic signs, there are also large billboards or led billboards. If you stick to only a certain ad, it's a pity because not all ads are suitable for everyone. Specifically, G63 drivers will be more interested in golf-related ads.
<p align="center">
    <img style="width: 30%" src="Image/Introduction.png"/>
</p>
So one idea is how to customize the ad to suit the driver audience. Whether these ads reflect the individual driver's interest is a matter of concern. However, overall, the following is how ads work:

1. Demographic analysis.
2. Identify their interests.
3. Show ads that reflect these interests.

In this chapter, we will learn how to build an intelligent billboard vision system by assessing the driver's vehicle type. More specifically, we will extract the basic characteristics of each vehicle for comparison and classification.

# Configuration
```bash
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 460.32.03    Driver Version: 460.32.03    CUDA Version: 11.2     |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|                               |                      |               MIG M. |
|===============================+======================+======================|
|   0  Tesla P100-PCIE...  Off  | 00000000:00:04.0 Off |                    0 |
| N/A   43C    P0    29W / 250W |      0MiB / 16280MiB |      0%      Default |
|                               |                      |                  N/A |
+-------------------------------+----------------------+----------------------+
                                                                               
+-----------------------------------------------------------------------------+
| Processes:                                                                  |
|  GPU   GI   CI        PID   Type   Process name                  GPU Memory |
|        ID   ID                                                   Usage      |
|=============================================================================|
|  No running processes found                                                 |
+-----------------------------------------------------------------------------+
```

# Reference
- Deep Learning for Computer Vision with Python, Practitioner Bundle, Dr. Adrian Rosebrock, 1st Edition (1.2.1)
 
