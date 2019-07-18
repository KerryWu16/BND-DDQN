# BND-DDQN

The tensorflow implmentation of paper: [Learn to Steer through Deep Reinforcement Learning](https://www.mdpi.com/1424-8220/18/11/3650)

Videos of our experiments are available at [Video1](https://www.youtube.com/watch?v=yixnmFXIKf4&t=27s) and [Video2](https://www.youtube.com/watch?v=19jrQGG1oCU&t=19s).

## Prerequisites

```
Python 3.5
Tensorflow 1.13.1
ROS Kinetic
```

## Instruction

Clone the pioneer_utils folder to your catkin workspace and catkin_make:
```
cd ~/catkin_ws/
catkin_make
source ~/catkin_ws/devel/setup.bash
```
Launch the simulator with command:
```
roslaunch pioneer_utils p3_world.launch
```    
Start training with command:
```
python main.py
```

## Citation

If you find this method useful in your research, please cite:
```
@article{wu2018learn,
  title={Learn to steer through deep reinforcement learning},
  author={Wu, Keyu and Abolfazli Esfahani, Mahdi and Yuan, Shenghai and Wang, Han},
  journal={Sensors},
  volume={18},
  number={11},
  pages={3650},
  year={2018},
  publisher={Multidisciplinary Digital Publishing Institute}
}
```
