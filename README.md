# irl-imitation
Implementations of selected inverse reinforcement learning / imitation learning algorithms in Python

#### Algorithms implemented 

- [linear inverse reinforcement learning (Ng & Russell 2000)](#linear-inverse-reinforcement-learning)

## Linear inverse reinforcement learning

- Following Ng & Russell 2000 paper: [Algorithms for Inverse Reinforcement Learning](http://ai.stanford.edu/~ang/papers/icml00-irl.pdf)

```
$ python linear_irl_gridworld.py --act_random=0.3 --gamma=0.5 --l1=10 --r_max=10
```

<img src="imgs/rmap_gt.jpg" width="200"> <img src="imgs/vmap_gt.jpg" width="200"> <img src="imgs/rmap_lirl.jpg" width="200"> <img src="imgs/rmap_lirl_3d.jpg" width="200"> 