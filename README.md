# Offline Model-based Adversarial Game for policy Optimization

## Installation
1. Install [MuJoCo 2.0.0](https://github.com/deepmind/mujoco/releases) to `~/.mujoco/mujoco200`.
2. Create a conda environment and install requirements.
```
cd MAGO
conda env create -f MAGO_env.yml
conda activate MAGO_env
```

## Usage
For example, use the following command to run Hopper-expert-v2 benchmark in D4RL.

```
python main.py --task=hopper-expert-v2
```
Detailed configuration can be found in `config.py`.


#### Logging
By default, TensorBoard logs are generated in the `log/` directory.

#### Experiments
We show the experimental result figures here.

HalfCheetah-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\expert\reward.png)

HalfCheetah-random

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\random\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\random\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\random\reward.png)

HalfCheetah-medium

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium\reward.png)

HalfCheetah-medium-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium-expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium-expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\medium-expert\reward.png)

HalfCheetah-medium-replay

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\mixed\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\mixed\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\halfcheetah\mixed\reward.png)

Hopper-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\expert\reward.png)

Hopper-random

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\random\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\random\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\random\reward.png)

Hopper-medium

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium\reward.png)

Hopper-medium-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium-expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium-expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\medium-expert\reward.png)

Hopper-medium-replay

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\mixed\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\mixed\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\hopper\mixed\reward.png)

Walker2d-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\expert\reward.png)

Walker2d-random

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\random\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\random\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\random\reward.png)

Walker2d-medium

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium\reward.png)

Walker2d-medium-expert

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium-expert\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium-expert\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\medium-expert\reward.png)

Walker2d-medium-replay

![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\mixed\adv-q.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\mixed\ensemble-std.png)
![](E:\PyCharm\OfflineRL\MAGO\MAGO\log\walker2d\mixed\reward.png)