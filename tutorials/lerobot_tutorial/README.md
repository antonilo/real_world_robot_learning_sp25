# lerobot tutorial

colab uses python 3.11.11

## Diffusion/PushT
took about 2 min to train 1000 offline steps on keypoint-based dataset on 3060

can get a decent policy at 20000 offline steps

took about 493 min to train 200000 offline steps 

## ALOHA/ACT
took about 3 min to train 1000 offline steps on state-based dataset on 3060

280 min (4.7 hours) to train 100000 offline steps on 3060

## extra steps needed locally
`import torch` throws error (https://github.com/pytorch/pytorch/issues/111469#issuecomment-1773937884):
`export LD_LIBRARY_PATH=$HOME/.pyenv/versions/lerobot_tutorial/lib64/python3.11/site-packages/nvidia/nvjitlink/lib:$LD_LIBRARY_PATH`

`pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121`