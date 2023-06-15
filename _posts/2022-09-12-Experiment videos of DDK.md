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

This is an improvement work from our previous work:
@ARTICLE{xiao2023deep,
	author={Xiao, Yongqian and Zhang, Xinglong and Xu, Xin and Liu, Xueqing and Liu, Jiahang},
	journal={IEEE Transactions on Intelligent Vehicles}, 
	title={Deep Neural Networks With Koopman Operators for Modeling and Control of Autonomous Vehicles}, 
	year={2023},
	volume={8},
	number={1},
	pages={135-146},
	doi={10.1109/TIV.2022.3180337}}

Our work has been accepted to ICRA 2023. The simulation code in CarSim environment can be downloaded (https://github.com/yongqianxiao/DDK). It includes the config file of the CarSim environment, the whole datasets, and the code for simulation controlling. Based on these files, you can restore the simulation in the paper. This blog aims to show the experiment videos.

The following video is corresponding to the experiment scenes in the paper. If you cannot watch the video fluently, you can download it by the link https://od.lk/s/ODFfNjI4MDMzMjBf/DDK_ICRA2023.mp4.
<video src="https://od.lk/s/ODFfNjI4MDMzMjBf/DDK_ICRA2023.mp4" controls></video>

The video of more experiment scenes is as follows, and it can be downloaded at https://od.lk/s/ODFfNjI4MDMzMjFf/DDK_10min_ICRA2023.mp4.

<video src="https://od.lk/s/ODFfNjI4MDMzMjFf/DDK_10min_ICRA2023.mp4" controls></video>

Because the training set data of the DDK vehicle model are all collected from urban roads, in order to verify the generalization performance of our method, we have recently added real-world experiments on off-road roads. 
The track results and experiment videos (download link: https://od.lk/d/ODFfNjc3MzAxNDNf/off_road.mp4) are as follows:
![classic RNN](https://od.lk/s/ODFfNjc3MzAxNjhf/off_road_ref.png)
![classic RNN](https://od.lk/s/ODFfNjc3MzAxNDJf/DKMPC_track_result.png)

<video src="https://od.lk/s/ODFfNjc3MzAxNDNf/off_road.mp4" controls></video>
