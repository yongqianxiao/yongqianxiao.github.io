---
layout: post
title:  Experiment videos of DKMPC (or DDK-MPC)
subtitle: 
date: 2022-09-12
author:  XYQ
header-img: 
catalog:  true
tags:
    - Koopman operator
    - MPC
    - autonomous driving
    - trajectory tracking
---


## Videos

This is an improvement work from our previous paper:
@ARTICLE{xiao2023deep,
	author={Xiao, Yongqian and Zhang, Xinglong and Xu, Xin and Liu, Xueqing and Liu, Jiahang},
	journal={IEEE Transactions on Intelligent Vehicles}, 
	title={Deep Neural Networks With Koopman Operators for Modeling and Control of Autonomous Vehicles}, 
	year={2023},
	volume={8},
	number={1},
	pages={135-146},
	doi={10.1109/TIV.2022.3180337}}

---
the latest experiment results:
![classic RNN](https://od.lk/s/ODFfNzEzMDc0NDRf/DDKMPC_result1.jpg)
![classic RNN](https://od.lk/s/ODFfNzEzMDc0NDNf/DDKMPC_result2.jpg)

<video src="https://od.lk/s/ODFfNzEzMDcxOTJf/all_track_OK.mp4" controls></video>

if you cannot watch the video fluently, you could try to download it at https://od.lk/s/ODFfNzEzMDcxOTJf/all_track_OK.mp4;
Or you can watch it on the Zhihu website (Only for Chinese): 
https://www.zhihu.com/zvideo/1722301721152368641.
https://www.zhihu.com/zvideo/1722302936724643840.
---

Different from our previous work, this paper proposes a new modeling method for modeling vehicle dynamics, namely Deep Koopman Approach for Eigenfeatures Learning (DKEL, 深度Koopman本征学习方法) or Deep Direct Koopman (DDK, 深度直接Koopman). DKEL has significantly improved the modeling accuracy, and the vehicle model trained using urban road data can adapt to off-road roads (verified through control experiments).

**Our work has been accepted for ICRA 2023. ** The simulation code in the CarSim environment is available for download at (https://github.com/yongqianxiao/DDK). This includes the configuration file for the CarSim environment, the entire dataset, and the code for simulation control. With these files, you can reproduce the simulations discussed in the paper. This blog aims to showcase the experiment videos.

The following video is corresponding to the experiment scenes in the paper. If you cannot watch the video fluently, download it by the link https://od.lk/s/ODFfNjI4MDMzMjBf/DDK_ICRA2023.mp4.
<video src="https://od.lk/s/ODFfNjI4MDMzMjBf/DDK_ICRA2023.mp4" controls></video>

The video of more experiment scenes is as follows, and it can be downloaded at https://od.lk/s/ODFfNjI4MDMzMjFf/DDK_10min_ICRA2023.mp4.

<video src="https://od.lk/s/ODFfNjI4MDMzMjFf/DDK_10min_ICRA2023.mp4" controls></video>

Because the training set data of the DDK vehicle model are all collected from urban roads, to verify our method's generalization performance, we have recently added real-world experiments on off-road roads. 
The track results and experiment videos (download link: https://od.lk/d/ODFfNjc3MzAxNDNf/off_road.mp4) are as follows:
![classic RNN](https://od.lk/s/ODFfNjc3MzAxNjhf/off_road_ref.png)
![classic RNN](https://od.lk/s/ODFfNjc3MzAxNDJf/DKMPC_track_result.png)

<video src="https://od.lk/s/ODFfNjc3MzAxNDNf/off_road.mp4" controls></video>
