## About Me


I am currently machine learning engineer at [Intellimize](https://www.intellimize.com/). I previously worked at Carnegie Mellon's School of Computer Science focusing on various aspects of autonomous racing after starting and leading [CMU's Roborace team](https://www.cmu.edu/news/stories/archives/2020/july/roborace.html) following a master's program there. Previously, Jimmy performed statistical modeling for 2 years as a pricing actuary, and in the Spring of 2019, became an Associate of the Society of Actuaries. Jimmy played professional footabll for the New York Giants in the preseason of 2017 as an outside linebacker.

My interests span broadly across various aspects of machine learning including building efficient machine learning systems.


## Experience


## Publications

J. Herman, J. Francis, S. Ganju, A. Koul, A. Skabelkin, I. Zhukov, A. Gostev, M. Kumskoy, E. Nyberg. *Learn-to-Race: A Multimodal Control Environment for Autonomous Racing.* Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2021, pp. 9793-9802. \[[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Herman_Learn-To-Race_A_Multimodal_Control_Environment_for_Autonomous_Racing_ICCV_2021_paper.html)\] \[[code](https://github.com/learn-to-race/l2r)\] \[[PyPI](https://pypi.org/project/l2r/)\]


## Learn-to-Race

Inspired by many recent works using deep reinforcement learning to address highly complex problems, I created [learn-to-race](https://github.com/learn-to-race/l2r), an  OpenAI Gym compliant reinforcement learning & control environment. This work has been featured in ICCV and was used in a [safe learning challenge at ICML](https://learn-to-race.org/workshop-sl4ad-icml2022/).

I also wrote [distrib_l2r](https://github.com/hermgerm29/distrib_l2r) which is a custom, Kubernetes-based distributed approach to training agents with the environment. In partnership with CMU's Parallel Data Lab, I trained the following Soft Actor-Critic agent to learn-to-race, from scratch, after about 2 million timesteps in the environment.

<iframe width="560" height="315" src="https://www.youtube.com/embed/a-RYPr6Wla4" title="Learning to Race using Reinforcement Learning (teaser)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
