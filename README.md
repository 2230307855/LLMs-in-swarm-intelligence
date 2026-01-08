# LLMs in swarm intelligence (UAV swarm)

### 论文名称：Cloud-Edge Collaborative UAV Swarm Path Planning With Deep-thinking LLM Fine-Tuning

In this work, we propose a UAV swarm path planning framework based on LLM deep thinking fine-tuning under a cloud-edge collaborative architecture, used to guide UAVs in completing path planning tasks using local perception information. 

In our framework, large LLMs (LLMs) are deployed on the cloud and receive all perception information from the UAV side to provide movement decisions for the current time step when communication is good. Small LLMs (SLMs) are deployed on the UAV side and make movement decisions using partial perception information when communication quality is poor (using less information to ensure inference quality). Since the UAV's perception range is fixed, cloud-based LLMs can utilize all perception information for more comprehensive reasoning and move a longer distance in a single step. The architecture is shown in Fig. 1.

![architecture](markdown_files\figure\architecture\01.png)![architecture](图片路径)

Unlike previous methods, we do not use global information during training. Meanwhile, we propose corresponding methods to address the lack of foresight caused by UAVs using only local perception information. 

The experimental data for this work has been uploaded to Hugging Face and will be made publicly available along with the code immediately upon paper acceptance.

The following is the presentation of experimental results.