# awesome-robot-navigation
**> Non-exhaustive paper list for robot visual navigation (mainly for indoor scenes)**

Quick jump: 

- [Survey](#survey)
- [Simulator](#simulator)
- [Visual Navigation](#visual-navigation)
- [Visual Semantic Navigation](#visual-semantic-navigation)
- [Room Navigation](#room-navigation)
- [Vision-and-Language Navigation](#vision-and-language-navigation)
- [Hardware Deployment](#hardware-deployment)
- [Some Research Groups](#some-research-groups):
	- AllenAI
	- [Saurabh Gupta](#saurabh-gupta-uiuc)
	- [SVL Lab](#svl-lab-stanford)
	- [BAIR](#berkeley-ai-research)

## Survey

* Visual Navigation for Mobile Robots: A Survey. Journal of Intelligent and Robotic Systems, 2008
* On Evaluation of Embodied Navigation Agents. Arxiv 2018
* From Seeing to Moving: A Survey on Learning for Visual Indoor Navigation (VIN). Arxiv 2020

## Simulator

* **AI2-THOR** [[Website](https://ai2thor.allenai.org/)] [[Github](https://github.com/allenai/ai2thor)] [[Challenge@CVPR2020](https://github.com/allenai/robothor-challenge)]
  * Maintainer: Allen Institute for Artificial Intelligence 
  * AI2-THOR: An interactive 3D environment for visual AI. Arxiv 2017
  * RoboTHOR: An Open Simulation-to-Real Embodied AI Platform. CVPR 2020
* **Gibson** [[Website](http://svl.stanford.edu/igibson/)] [[Github](https://github.com/StanfordVL/iGibson)] [[Challenge@CVPR2020](https://github.com/StanfordVL/GibsonSim2RealChallenge)]
  * Maintainer: Stanford SVL Lab
  * Gibson Env: real-world perception for embodied agents. CVPR 2018
  * Interactive Gibson: A Benchmark for Interactive Navigation in Cluttered Environments. ICRA 2020 (RA-L)
* **Habitat** [[Website](https://aihabitat.org/)] [[Github/Habitat_lab](https://github.com/facebookresearch/habitat-lab)] [[Github/Habitat_sim](https://github.com/facebookresearch/habitat-sim)] [[Challenge@CVPR2020](https://github.com/facebookresearch/habitat-challenge)]
  * Maintainer: Facebook
  * Habitat: A Platform for Embodied AI Research. ICCV 2019
* **House3D** [[Github](https://github.com/facebookresearch/House3D)]
  * Maintainer: Facebook
  * Building Generalization Agents with a Realistic and Rich 3D Environment. Arxiv 2018
* **Matterport 3D** [[Website](https://niessner.github.io/Matterport/)] [[Github](https://github.com/niessner/Matterport)]
  * Maintainer: Princeton & Stanford & TUM
  * Matterport3D: Learning from RGB-D Data in Indoor Environments. 3DV 2017


## Visual Navigation

* Target-driven visual navigation in indoor scenes using deep reinforcement learning. ICRA 2017

## Visual Semantic Navigation

* Visual Semantic Navigation using Scene Priors. ICLR 2019
* Visual Representations for Semantic Target Driven Navigation. ICRA 2019
* Learning to Learn How to Learn: Self-Adaptive Visual Navigation Using Meta-Learning. CVPR 2019 
  * [[code](https://github.com/allenai/savn)]
* Object Goal Navigation using Goal-Oriented Semantic Exploration. ECCV 2020
* Improving Target-driven Visual Navigation with Attention on 3D Spatial Relationships. Arxiv 2020
* Semantic Visual Navigation by Watching YouTube Videos. Arxiv 2020
* Target driven visual navigation exploiting object relationships.  Arxiv 2020

## Room Navigation

* Building Generalization Agents with a Realistic and Rich 3D Environment. Arxiv 2018
* Bayesian Relational Memory for Semantic Visual Navigation. ICCV 2019

## Neural Exploration

* Learning to Explore using Active Neural SLAM. ICLR 2020

## Vision-and-Language Navigation

* ...


## Hardware Deployment

* ...

## Some Research Groups

### Saurabh Gupta (UIUC)

* [Unifying Map and Landmark Based Representations for Visual Navigation](https://arxiv.org/pdf/1712.08125.pdf) Arxiv 2017
  * ***\*Saurabh Gupta\****, David Fouhey, Sergey Levine, Jitendra Malik
* [Cognitive Mapping and Planning for Visual Navigation](https://arxiv.org/pdf/1702.03920v2.pdf) CVPR 2017
  * ***\*Saurabh Gupta\****, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik
* [On Evaluation of Embodied Navigation Agents](https://arxiv.org/pdf/1807.06757.pdf) Arrive 2018
  * Peter Anderson, Angel Chang, Devendra Chaplot, Alexey Dosovitskiy, ***\*Saurabh Gupta\****, Vladlen Koltun, Jana Kosecka, Jitendra Malik, Roozbeh Mottaghi, Manolis Savva, Amir Zamir
* [PyRobot: An Open-Source Robotics Framework for Research and Benchmarking](https://arxiv.org/pdf/1906.08236.pdf) Arxiv 2019
  * Adithyavairavan Murali*, Tao Chen*, Kalyan Vasudev Alwala*, Dhiraj Gandhi*, Lerrel Pinto, ***\*Saurabh Gupta\****, Abhinav Gupta
* [Cognitive Mapping and Planning for Visual Navigation](https://arxiv.org/pdf/1702.03920.pdf) IJCV 2019
  * ***\*Saurabh Gupta\****, Varun Tolani, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik
* [Learning Exploration Policies for Navigation](https://arxiv.org/pdf/1903.01959.pdf) ICLR 2019
  * Tao Chen, ***\*Saurabh Gupta\****, Abhinav Gupta
* [Combining Optimal Control and Learning for Visual Navigation in Novel Environments](https://arxiv.org/pdf/1903.02531.pdf) CoRL 2019
  * Somil Bansal, Varun Tolani, ***\*Saurabh Gupta\****, Jitendra Malik, Claire Tomlin
* [Learning Navigation Subroutines by Watching Videos](https://arxiv.org/pdf/1905.12612.pdf) CoRL 2019
  * Ashish Kumar, ***\*Saurabh Gupta\****, Jitendra Malik
* [Learning to Move With Affordance Maps](https://openreview.net/pdf?id=BJgMFxrYPB) ICLR 2020
  * William Qi, Ravi Mullapudi, ***\*Saurabh Gupta\****, Deva Ramanan
* [Learning to Explore Using Active Neural Mapping](https://openreview.net/pdf?id=HklXn1BKDH) ICLR 2020
  * Devendra Chaplot, Dhiraj Gandhi, ***\*Saurabh Gupta\****, Abhinav Gupta, Ruslan Salakhutdinov
* [Neural Topological SLAM for Visual Navigation](https://saurabhg.web.illinois.edu/pdfs/chaplot2020neural.pdf) CVPR 2020
  * Devendra Chaplot, Ruslan Salakhutdinov, Abhinav Gupta, ***\*Saurabh Gupta\****
* [Semantic Curiosity for Active Visual Learning](https://arxiv.org/pdf/2006.09367.pdf) ECCV 2020
  * Devendra Chaplot*, Helen Jiang*, ***\*Saurabh Gupta\****, Abhinav Gupta
* [Semantic Visual Navigation by Watching YouTube Videos](https://arxiv.org/pdf/2006.10034.pdf) Arxiv 2020
  * Matthew Chang, Arjun Gupta, ***\*Saurabh Gupta\****

### SVL Lab (Stanford)

* [TARGET-DRIVEN VISUAL NAVIGATION IN INDOOR SCENES USING DEEP REINFORCEMENT LEARNING](http://web.stanford.edu/~yukez/papers/icra2017.pdf) ICRA 2017
  * [Yuke Zhu](http://web.stanford.edu/~yukez/), Roozbeh Mottaghi, Eric Kolve, Joseph J. Lim, Abhinav Gupta, Li Fei-Fei, and Ali Farhadi
* [TRANSLATING NAVIGATION INSTRUCTIONS IN NATURAL LANGUAGE TO A HIGH-LEVEL PLAN FOR BEHAVIORAL ROBOT NAVIGATION](https://arxiv.org/abs/1810.00663) EMNLP 2018
  * Xiaoxue Zang, Ashwini Pokle, Marynel Vázquez, Kevin Chen, Juan Carlos Niebles, Alvaro Soto and Silvio Savarese
* [BEHAVIORAL INDOOR NAVIGATION WITH NATURAL LANGUAGE DIRECTIONS](http://svl.stanford.edu/assets/papers/behavior-indoor-navigation.pdf) HRI 2018 (Late Breaking Reports)
  * Xiaoxue Zang, Marynel Vázquez, Juan Carlos Niebles, Alvaro Soto, Silvio Savarese
* [A DEEP LEARNING BASED BEHAVIORAL APPROACH TO INDOOR AUTONOMOUS NAVIGATION](https://arxiv.org/pdf/1803.04119v1.pdf) ICRA 2018
  * Gabriel Sepulveda, Juan Carlos Niebles, and Alvaro Soto
* [HRL4IN: HIERARCHICAL REINFORCEMENT LEARNING FOR INTERACTIVE NAVIGATION WITH MOBILE MANIPULATORS](https://sites.google.com/view/hrl4in/home) CoRL 2019
  * Chengshu (Eric) Li, Fei Xia, Roberto Martín-Martín, Silvio Savarese
* [SITUATIONAL FUSION OF VISUAL REPRESENTATION FOR VISUAL NAVIGATION](https://arxiv.org/pdf/1908.09073.pdf) ICCV 2019
  * William B. Shen, Danfei Xu, Yuke Zhu, Leo Guibas, Li Fei-Fei, Silvio Savarese
* [DEEP VISUAL MPC-POLICY LEARNING FOR NAVIGATION](https://ieeexplore.ieee.org/document/8750823) IROS 2019 (IEEE RA-L)
  * Noriaki Hirose, Fei Xia, Roberto Martin-Martin, Amir Sadeghian, Silvio Savarese
* [A BEHAVIORAL APPROACH TO VISUAL NAVIGATION WITH GRAPH LOCALIZATION NETWORKS](https://arxiv.org/abs/1903.00445) RSS 2019
  * Kevin Chen, Juan Pablo de Vicente, Gabriel Sepúlveda, Fei Xia, Alvaro Soto, Marynel Vázquez, Silvio Savarese
* [INTERACTIVE GIBSON: A BENCHMARK FOR INTERACTIVE NAVIGATION IN CLUTTERED ENVIRONMENTS](https://arxiv.org/abs/1910.14442) ICRA 2020 (IEEE RA-L)
  * Fei Xia, William B. Shen, Chengshu Li, Priya Kasimbeg, Micael Tchapmi, Alexander Toshev, Roberto Martín-Martín, Silvio Savarese
* [LOOK, LISTEN, AND ACT: TOWARDS AUDIO-VISUAL EMBODIED NAVIGATION](https://jiajunwu.com/papers/avn_icra.pdf) ICRA 2020
  * Chuang Gan*, Yiwei Zhang*, Jiajun Wu, Boqing Gong, Joshua B. Tenenbaum

### Berkeley AI Research

* [BADGR: An Autonomous Self-Supervised Learning-Based Navigation System](https://arxiv.org/pdf/2002.05700.pdf) Arxiv 2020
  * Gregory Kahn, Pieter Abbeel, Sergey Levine 
* [Composable Action-Conditioned Predictors: Flexible Off-Policy Learning for Robot Navigation](https://arxiv.org/pdf/1810.07167.pdf) CoRL 2018
  * Gregory Kahn*, Adam Villaflor*, Pieter Abbeel, Sergey Levine
* [Self-supervised Deep Reinforcement Learning with Generalized Computation Graphs for Robot Navigation](https://arxiv.org/pdf/1709.10489.pdf) ICRA 2018
  * Gregory Kahn, Adam Villaflor, Bosen Ding, Pieter Abbeel, Sergey Levine 
* [PLATO: Policy Learning using Adaptive Trajectory Optimization](http://arxiv.org/pdf/1603.00622) ICRA 2017
  * Gregory Kahn, Tianhao Zhang, Sergey Levine, Pieter Abbeel 

### FAIR

### AllenAI

