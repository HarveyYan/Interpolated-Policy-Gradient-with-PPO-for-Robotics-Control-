## TRPO algorithm with Hindsight Experience Replay

- The main algorithm used here is Trust Region Policy Gradient (TRPO) for continuous control task. Basic environment from a newly introduced environment - Robotics. It is a multi-goal environment from OpanAI Gym and use the MuJoCo physic engine for fast and accurate simulation. 
- Mainly based on Fetch environment with four task and start from FetchReach-v0, the other three are FetchPush, FetchSlide, FetchPickAndPlace. 
- Parameters changing process during experiments will be saved at **plot-files**. So far *Success Rate*, *Mean Rewards*, *Policy Entropy* have obvious regular changing and they are important results/parameters.
- TODO:
  - [ ] Combine with Hintsight Experience Replay!!
  - [ ] Find out why during the first 1000 episodes the success rate are always low and with a low improvement. and try to address the problem
  - [ ] More experiments on pushing, sliding, pick&place
  - [ ] catch up with eligibility trace
  - [ ] change tanh to ReLU




