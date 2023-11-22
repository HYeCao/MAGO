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

![](.\log\halfcheetah\expert\adv-q.png)
![](.\log\halfcheetah\expert\ensemble-std.png)
![](.\log\halfcheetah\expert\reward.png)

HalfCheetah-random

![](.\log\halfcheetah\random\adv-q.png)
![](.\log\halfcheetah\random\ensemble-std.png)
![](.\log\halfcheetah\random\reward.png)

HalfCheetah-medium

![](.\log\halfcheetah\medium\adv-q.png)
![](.\log\halfcheetah\medium\ensemble-std.png)
![](.\log\halfcheetah\medium\reward.png)

HalfCheetah-medium-expert

![](.\log\halfcheetah\medium-expert\adv-q.png)
![](.\log\halfcheetah\medium-expert\ensemble-std.png)
![](.\log\halfcheetah\medium-expert\reward.png)

HalfCheetah-medium-replay

![](.\log\halfcheetah\mixed\adv-q.png)
![](.\log\halfcheetah\mixed\ensemble-std.png)
![](.\log\halfcheetah\mixed\reward.png)

Hopper-expert

![](.\log\hopper\expert\adv-q.png)
![](.\log\hopper\expert\ensemble-std.png)
![](.\log\hopper\expert\reward.png)

Hopper-random

![](.\log\hopper\random\adv-q.png)
![](.\log\hopper\random\ensemble-std.png)
![](.\log\hopper\random\reward.png)

Hopper-medium

![](.\log\hopper\medium\adv-q.png)
![](.\log\hopper\medium\ensemble-std.png)
![](.\log\hopper\medium\reward.png)

Hopper-medium-expert

![](.\log\hopper\medium-expert\adv-q.png)
![](.\log\hopper\medium-expert\ensemble-std.png)
![](.\log\hopper\medium-expert\reward.png)

Hopper-medium-replay

![](.\log\hopper\mixed\adv-q.png)
![](.\log\hopper\mixed\ensemble-std.png)
![](.\log\hopper\mixed\reward.png)

Walker2d-expert

![](.\log\walker2d\expert\adv-q.png)
![](.\log\walker2d\expert\ensemble-std.png)
![](.\log\walker2d\expert\reward.png)

Walker2d-random

![](.\log\walker2d\random\adv-q.png)
![](.\log\walker2d\random\ensemble-std.png)
![](.\log\walker2d\random\reward.png)

Walker2d-medium

![](.\log\walker2d\medium\adv-q.png)
![](.\log\walker2d\medium\ensemble-std.png)
![](.\log\walker2d\medium\reward.png)

Walker2d-medium-expert

![](.\log\walker2d\medium-expert\adv-q.png)
![](.\log\walker2d\medium-expert\ensemble-std.png)
![](.\log\walker2d\medium-expert\reward.png)

Walker2d-medium-replay

![](.\log\walker2d\mixed\adv-q.png)
![](.\log\walker2d\mixed\ensemble-std.png)
![](.\log\walker2d\mixed\reward.png)