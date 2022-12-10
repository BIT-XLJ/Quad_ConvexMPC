# LTV MPC for Quadruped Locomotion

![Quadruped Trotting](gif/edited_states_turn_trot.gif)



## Abstract
This paper presents a state-of-the-art optimal controller for quadruped locomotion. The robot dynamics is represented using a single rigid body (SRB) model. A linear time-varying model predictive controller (LTV MPC) is proposed by using linearization schemes. Simulation results show that the LTV MPC can execute various gaits, such as trot and crawl, and is capable of tracking desired reference trajectories even under unknown external disturbances. The LTV MPC is implemented as a quadratic program using $qpOASES$ through the $CasADi$ interface at 50 Hz. The proposed MPC can reach up to 1 m/s top speed with an acceleration of 0.5 m/s$^2$ executing a trot gait. 
