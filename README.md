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
