## About Me

I am currently a software engineer and technical lead at [Swish Analytics](https://swishanalytics.com/), a next-generation oddsmaker for U.S. sportsbook data specializing in custom parlays, player props, and in-game betting. My ongoing contributions include leading the re-architecture of Swish's core simulation software. The effort has dramatically improved key performance metrics such as in-game latency, cost, server uptime, and model testing velocity.

My interests span broadly across various aspects of machine learning and software engineering. When I'm away from my computer, I follow college sports, travel, hike, and snow ski.


## Prior Experience

Previously, I was as a machine learning engineer at [Intellimize](https://www.intellimize.com/), a series B startup at the time. I worked on a variety of engineering and machine learning projects including designing and shipping a [fully implicit text recommendation service](https://www.intellimize.com/press/intellimize-releases-ai-powered-copy-suggestions-for-marketers-to-instantly-personalize-websites-that-convert-more) which provides text variations for any element on a website with no user input \[[example](https://www.linkedin.com/posts/intellimize_convertmore-writing-content-activity-6960991520355217408-iDxf?utm_source=linkedin_share&utm_medium=member_desktop_web)\]. This was built with OpenAI's API prior to the release of ChatGPT (and newer) models, thus requiring a significant amount of prompt engineering.

During, and for the summer following graduate school at Carnegie Mellon, I worked as a reearcher focusing on various aspects of autonomous racing after starting, and leading [CMU's Roborace team](https://www.cmu.edu/news/stories/archives/2020/july/roborace.html). Key contributions include building learn-to-race, a high-fidelity reinforcement learning and control environment, described below, which was published at ICCV and featured in a [safe learning workshop at ICML](https://learn-to-race.org/workshop-sl4ad-icml2022/).

Prior to graduate school, I worked as a pricing actuary working primarily on statistical modeling, and in the Spring of 2019, became an Associate of the Society of Actuaries. Additionally, I played professional football for the New York Giants in the preseason of 2017 as an outside linebacker.


## Publications

J. Herman, J. Francis, S. Ganju, A. Koul, A. Skabelkin, I. Zhukov, A. Gostev, M. Kumskoy, E. Nyberg. *Learn-to-Race: A Multimodal Control Environment for Autonomous Racing.* Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2021, pp. 9793-9802. \[[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Herman_Learn-To-Race_A_Multimodal_Control_Environment_for_Autonomous_Racing_ICCV_2021_paper.html)\] \[[code](https://github.com/learn-to-race/l2r)\] \[[PyPI](https://pypi.org/project/l2r/)\]


## Learn-to-Race

Inspired by many recent works using deep reinforcement learning to address highly complex problems, I created [learn-to-race](https://github.com/learn-to-race/l2r), an  OpenAI Gym compliant reinforcement learning & control environment. My hope is that the environment will help advance research in a variety of areas including safe reinforcement learning and multi-modal machine learning.

<iframe width="560" height="315" src="https://www.youtube.com/embed/a-RYPr6Wla4" title="Learning to Race using Reinforcement Learning (teaser)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>

I also wrote [distrib_l2r](https://github.com/hermgerm29/distrib_l2r) which is a custom, Kubernetes-based distributed approach to training agents with the environment. I also was able to achieve near human speed performance in the environment by creating a custom off-policy, asynchronous distributed RL system and running large scale experiments on [CMU PDL's](https://www.pdl.cmu.edu/index.shtml) compute clusters.
