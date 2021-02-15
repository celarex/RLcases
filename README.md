# RLcases (Timelines)

## 1.Platform for reinforcement learning research

**Objectives**

* v1.0
* [x] Modular design (independent environment, agent, training arena, learning algorithm, approximate function and auxiliary modules)
* [x] Open closed principle (implemented by wrapper design)
* [X] Multi-platform (support Pytorch and Tensorflow for convenient performance comparison with other open sources)
* [X] Multi-algorithm; Multi-model (implemented A2C,Acktr,PPO,... algorithms; CNN,RNN,... models)
* [X] Multi-CPU sampling; Multi-GPU calculation
* [X] Modules for custom environments (used pygame for 2d cases and Panda3D for 3d cases)
* [X] Automatic hyperparameter search (implemented by Optuna)
* v2.0
* [X] Modules for POMDPs (Inference in vision)
* [X] Modules for Multi-agent problems (Training arena for multi-player multi-type multi-agent without explicitly communication)
* v3.0
* [ ] Distributional calculation
* [ ] Model based algorithms
* [ ] Explicitly communications

**Results**

* v1.0
* [x] Surpass or do as well as OpenAI's Baselines on Atari and Mujoco cases
* v2.0
* [x] Performance similar with state-of-the-art algorithms on flickering Atari cases (POMDP cases)
* [x] Solved Starcraft minigames like micro management problems (Multi-agent cases)

**Animations**

Left:BeamRider's feature maps, Middle:Breakout's feature maps, Right:Visualizations of filters for MNIST

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/1_LayerVisualization_BeamRider.gif" alt="" width="240" height="240"> <img src="https://github.com/celarex/RLcases/blob/main/RLanimations/1_LayerVisualization_Breakout.gif" alt="" width="240" height="240"> <img src="https://github.com/celarex/RLcases/blob/main/RLanimations/1_WeightVisualization_mnist.gif" alt="" width="240" height="240">

## 2.Unmanned underwater and airborne monitorings

**Objectives**

* [X] Optimize controlling of multiple kinds of unmanned vehicles
* [X] Capture targets efficiently while avoiding collision with obstacles
* [X] Adapting for POMDP environments

**Results**

* Best Paper Award in SPIE Journal of Applied Remote Sensing, 2019 https://doi.org/10.1117/1.JRS.13.044509

**Sketches**

Task descriptions by stages

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/2_MultipleUnmannedVehicles.png" alt="" width="720" height="405">

## 3.Powernet running

**Objectives**

* Training topology controllers to control electricity transportation in power grids, while keeping people and equipment safe from irregular wave motion or natural disasters. 

**Results**

* [X] Ranked 4th in Learning to run a power network challenge
* [X] Invited talk for the Annual Meeting of IEEJ (The Institute of Electrical Engineers of Japan), 2020

**Animations**

A tiny example case of power grids

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/3_L2RPN.gif" alt="" width="720" height="405">

## 4.Maze Escape

**Objectives**

* General agent to escape from different mazes

**Results**

* Solved

**Animations**

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/4_Maze_Escape.gif" alt="" width="512" height="288">

## 5.Starcraft

**Objectives**

* General agents to win in very complex environments

**Results**

* Familiar with pysc2 APIs

## 6.Micromanagement

**Objectives**

* Starcraft's minigame like setting for optimal tactic learning

**Results**

* Long range units learned hit and run tactic, Short range units learned surround tactic. 

**Animations**

Left:Hit and run,Right:Surround

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/6_Micro_HitandRun.gif" alt="" width="480" height="224"> <img src="https://github.com/celarex/RLcases/blob/main/RLanimations/6_Micro_Surround.gif" alt="" width="480" height="224">

## 7.CCA

**Objectives**

* Control controllable cellular to guide controllable cellular automaton to a specific target state

**Results**

* Simple cases are Solved. 

**Animations**

Left: Small case, Middle: Large case, Right: Loop tree case

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/7_CCA_Small.gif" alt="" width="240" height="240"> <img src="https://github.com/celarex/RLcases/blob/main/RLanimations/7_CCA_Large.gif" alt="" width="240" height="240"> <img src="https://github.com/celarex/RLcases/blob/main/RLanimations/7_CCA_LoopTree.gif" alt="" width="240" height="240">

## 8.Halite

**Objectives**

* A resource management game where agent build and control a small armada of ships to collect more halite, a luminous energy source. 
https://www.kaggle.com/c/halite

**Results**

* Purely machine learned agent was an excellent collector with high collection efficiency, but not aggressive enough to beat top agents (with some hand-crafted features). 

**Animations**

Custom rendering for agent development

<img src="https://github.com/celarex/RLcases/blob/main/RLanimations/8_Halite_MultiAgent_Comp.gif" alt="" width="360" height="360">

## 9.Scan robots

**Objectives**

* Control multiple types of multiple robots to scan an area as soon as possible while avoiding static and dynamic obstacles.  

**Results**

* Well learned. 

**Animations**

![image](https://github.com/celarex/RLcases/blob/main/RLanimations/9_ScanRobo_MultiTypeMultiAgent_Coop.gif)
