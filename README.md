# Q-Learning-Rocket
### Objecive
Make the rocket hover in a simulated continuous environment with reinforcement learning. We will use the Q-learning algorithm which is simple yet powerful. For pedagogical and computational reasons we will here use classical table-based Q-learning, but coupled with deep learning and large computational resources, this same algorithm is used in many recent advances in AI.

### Environment

The rocket can be controlled manually by the 'A','S','D' and 'W' buttons the keyboard.
The simulator is paused on 'R'.
The simulator is sped up on 'V' and slowed down on 'B'.
The graphics can be toggled off on 'M' for even faster simulation. This can be used to accelerate learning in parts II and III.
The learning controller (parts II and III) can be turned off on 'P' and turned on again on 'O'. Note: This should be done before controlling the rocket manually in later parts, otherwise it will confuse the learning algorithm
The learning controller can be told to stop exploring and focus on maximizing known utility by pressing 'E' (toggle). This should be done when it has converged.
Keys '1' and '2' are unused custom keys which may be used to trigger the corresponding functions in the learning controller if you desire additional functionality.
