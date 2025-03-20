# LEAP Hand: Low-Cost, Efficient, and Anthropomorphic Hand
This repository contains the URDF, IsaacGym environment and sim2real deployment code for the paper "LEAP Hand: Low-Cost, Efficient, and Anthropomorphic Hand for Robot Learning" ([https://arxiv.org/abs/2309.06440](https://arxiv.org/abs/2309.06440)).  

## Installation
 
Setup a conda environment (optional)

```
conda create -n leapsim python=3.8
conda activate leapsim
```
Install Pytorch using [these instructions](https://pytorch.org/get-started/locally/)

Download the Isaac Gym Preview 4 release from the [website](https://developer.nvidia.com/isaac-gym), then
follow the installation instructions in the documentation  
```
cd isaacgym/python
pip install -e .
```
Clone and install leapsim python packages
```
git clone https://github.com/leap-hand/LEAP_Hand_Sim
cd LEAP_Hand_Sim
pip install matplotlib gitpython numpy==1.20.3 wandb
pip install -e .
```
## Fuse minimal-stable PPO with LEAP Hand repos

## Citing
```
@article{
	shaw2023leaphand,
	title={LEAP Hand: Low-Cost, Efficient, and Anthropomorphic Hand for Robot Learning},
	author={Shaw, Kenneth and Agarwal, Ananye and Pathak, Deepak},
	journal={Robotics: Science and Systems (RSS)},
	year={2023}
}
```
