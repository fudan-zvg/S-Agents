<p align="center">
  <img src="figures/1_cover.jpeg" alt="S-Agents Icon"/>
</p>

# S-Agents: Self-organizing Agents in Open-ended Environment
> **[S-Agents: Self-organizing Agents in Open-ended Environment](https://arxiv.org/abs/2402.04578)**  
> Jiaqi Chen*, Yuxian Jiang*, Jiachen Lu and Li Zhang  
> Zhang Vision Group, Fudan Univerisity

In open-ended settings, optimizing collaboration for efficiency and effectiveness demands flexible adjustments. Despite this, current research mainly emphasizes fixed, task-oriented workflows and overlooks agent-centric organizational structures. Drawing inspiration from human organizational behavior, we introduce a self-organizing agent system (S-Agents) with a “tree of agents” structure for dynamic workflow, an “hourglass agent architecture” for balancing information priorities, and a “non-obstructive collaboration” method to allow asynchronous task execution among agents. This structure can autonomously coordinate a group of agents, efficiently addressing the challenges of an open and dynamic environment without human intervention.

### Methodology

1) A ``tree of agents" organizational structure, comprising a root node (leadership agent) and multiple leaf nodes (executor agents). The leadership agent autonomously arranges a flexible workflow without the need for human intervention.
<p align="center">
  <img src="figures/2_intro.jpeg" alt="S-Agents Icon"/>
</p>


2) An hourglass agent architecture that strives to balance priorities between the agent community and the physical environment, promoting coordinated actions.
<p align="center">
  <img src="figures/3_method.jpeg" alt="S-Agents Icon"/>
</p>

3) A Non-obstructive collaboration approach breaks away from the constraint of multiple intelligent agents sharing a fixed convergence beat, allowing agents to asynchronously execute collaborative tasks. This method is designed to alleviate delays induced by the slowest agent in each round, thereby enhancing overall efficiency.
<p align="center">
  <img src="figures/4_rollout.jpeg" alt="S-Agents Icon"/>
</p>


## 📜 Bibtex
If you find this work useful for your research, please cite our paper:
```bibtex
@article{chen2024sagent,
  title={S-Agents: self-organizing agents in open-ended environment},
  author={Chen, Jiaqi and Jiang, Yuxian and Lu, Jiachen and Zhang, Li},
  journal={arXiv preprint arxiv:2402.04578},
  year={2024}
}
```
>>>>>>> 1cbd85f4a1bbab6a9860d75315dcf742e829f62c
