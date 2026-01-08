# LLMs in swarm intelligence (UAV swarm)

## 1. Paper Name：Cloud-Edge Collaborative UAV Swarm Path Planning With Deep-thinking LLM Fine-Tuning

### 1.1 Brief Introduction

In this work, we propose a UAV swarm path planning framework based on LLM deep thinking fine-tuning under a cloud-edge collaborative architecture, used to guide UAVs in completing path planning tasks using local perception information.

In our framework, large LLMs (LLMs) are deployed on the cloud and receive all perception information from the UAV side to provide movement decisions for the current time step when communication is good. Small LLMs (SLMs) are deployed on the UAV side and make movement decisions using partial perception information when communication quality is poor (using less information to ensure inference quality). Since the UAV's perception range is fixed, cloud-based LLMs can utilize all perception information for more comprehensive reasoning and move a longer distance in a single step. The architecture is shown in Fig. 1.

 ![Fig. 1. LLM-Based UAV Swarm Path Planning Framework.](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/architecture/01.png?raw=true)**Fig. 1 LLM-Based UAV Swarm Path Planning Framework.**

### 1.2 Highlights

* A significant exploration of LLM-based swarm intelligence.
* Unlike previous methods, we do not use global information during training.
* We propose corresponding methods to address the lack of foresight caused by UAVs using only local perception information.
* We propose a continual online learning mechanism for LLMs.

### 1.3 Open Plan

The experimental data for this work has been uploaded to Hugging Face and will be made publicly available along with the code immediately upon paper acceptance.

 ![dataset](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/dataset/my_dataset.png?raw=true)

## 2.experimental results

**==The swarm intelligence path planning performance of our proposed method under different scene sizes (LLaMA 3.2-3B-4bit)==**

* Scene size: 20m × 20m

 ![20m](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/change_scene_size_res/size_20%C3%9720.gif?raw=true)

* Scene size: 40m × 40m

 ![40m](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/change_scene_size_res/size_40%C3%9740.gif?raw=true)

* Scene size: 60m × 60m

 ![60m](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/change_scene_size_res/size_60%C3%9760.gif?raw=true)

* Scene size: 80m × 80m

 ![80m](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/change_scene_size_res/size_80%C3%9780.gif?raw=true)

* Scene size: 100m × 100m

 ![100m](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/change_scene_size_res/size_100%C3%97100.gif?raw=true)

### 2.1 The comparison of path planning performance of LLM models

#### 2.1.1 The comparison of path planning performance of different LLMs

 ![01](https://github.com/2230307855/LLMs-in-swarm-intelligence/blob/main/markdown_files/figure/res/LLM_compare/1.png?raw=true)

#### 2.1.2 The comparison of path planning performance of different SLMs


### 2.2 The comparison of path planning performance of different methods

### 2.3 The performance comparison of different methods in dynamic scenarios

### 2.4 The performance of the proposed method in random scenes of different sizes

### 2.5 The comparison of local movement decision-making performance across different methods

### 2.6 Comparison of Training and Running time for Different Methods