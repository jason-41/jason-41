<div align="center">

# Hi, I'm Jason (Jia Cao) 👋

### Robotics · Control · Robot Learning

M.Sc. Mechanical Engineering at the Technical University of Munich (TUM)

[LinkedIn](https://www.linkedin.com/in/jia-cao41/) · [Repositories](https://github.com/jason-41?tab=repositories)

</div>

## About me

I build robotic systems across perception, planning and control, learning, simulation, and real-robot deployment. My recent work spans 3D visuomotor policy training on a Franka Panda, model- and learning-based quadrotor control, and voice-commanded manipulation on a biped humanoid.

- 🎓 M.Sc. Mechanical Engineering at TUM — focus on robotics, control, and machine learning
- 🦾 Hands-on experience with Franka Panda and AiNex biped humanoid robots
- 🚁 Control and robot-learning experience in JAX/MuJoCo quadrotor simulation
- 🔍 Interested in 3D visuomotor control, imitation learning, and robust long-horizon manipulation

> Open to a full-time robotics algorithms & control internship starting in late September 2026 (6+ months).

## Research focus

### Long-Horizon Manipulation with 3D Diffusion Policy on a Franka Panda

*Semester thesis · May–September 2026*

- Built an end-to-end ROS 1 + DP3 real-robot pipeline: teleoperated data collection, depth point clouds and robot states/actions, dataset conversion and validation, policy training, deployment, inference, and evaluation.
- Designed an asynchronous perception–inference–control architecture and optimized point-cloud sampling, action dispatch, and execution scheduling for smoother online robot motion.
- Developed a coffee-cup 6D pose pipeline with Qwen-VL, HQ-SAM, FoundationPose, Cutie, and Kalman filtering, then transformed the estimate into the robot frame for grasp-trajectory adaptation.
- Extended the coffee-pouring baseline toward rotated-cup, out-of-distribution scenarios and a hybrid long-horizon manipulation framework combining high-level task states with low-level DP3 visuomotor control.

**Stack:** ROS 1 · Python · PyTorch · DP3 · FoundationPose · VLMs · 3D point-cloud perception · Franka Emika Panda

## Featured projects

### [Voice-Commanded Pick-and-Place on an AiNex Biped Humanoid](https://github.com/jason-41/ainex_devops)

A ROS 2 manipulation system combining speech interaction, LLM-based instruction parsing, visual navigation, model-based reaching, and reinforcement-learning grasp control.

- Implemented closed-loop pre-grasp reaching with Pinocchio kinematics, cubic task-space trajectories, Cartesian PD control, and damped least-squares inverse kinematics.
- Designed a ROS 2 task state machine and custom messages integrating ASR/TTS, LLM parsing, ArUco navigation, biped locomotion, grasping, and release.
- Built a MuJoCo grasp environment, trained a PPO policy with randomized targets, and deployed it in Gazebo Harmonic for closed-loop sim-to-sim validation.
- Participated in physical-robot debugging of navigation, turning, grasping, and release.

**Stack:** ROS 2 · Python · Pinocchio · OpenCV · MuJoCo · Gazebo Harmonic · Stable-Baselines3

---

### Crazyflow Quadrotor Tracking — Model- and Learning-Based Control

[Course framework](https://github.com/learnsyslab/ARLDM-Advanced-Robot-Learning-And-Decision-Making)

Implemented and compared PD, LQR/iLQR, linear and nonlinear MPC, data-driven dynamics-residual models, Gaussian process-enhanced MPC, and PPO in a JAX-based quadrotor simulator.

- Formulated optimal-control problems with CasADi/acados and learned dynamics residuals with sparse variational Gaussian Processes.
- Reduced mean figure-eight position-tracking error from 8.86 cm to 7.23 cm with GP-enhanced MPC versus nominal MPC in the matched evaluation.
- Implemented batched rollouts, generalized advantage estimation, and PPO clipped updates; trained a random-trajectory policy with a 0.9 s preview across 1,024 parallel environments.

**Stack:** Python · JAX · Crazyflow/MuJoCo MJX · Gymnasium · CasADi · acados · GPyTorch · PyTorch · Docker

## More public work

- 🚗 [Autonomous Driving Team Project](https://github.com/jason-41/Autonomous-Driving-Team-Project-25SS) — ROS 1 + Unity stack with A* planning, trajectory generation, and PID control; I implemented the trajectory generator and controller.
- 💱 [Exchange-rate Monitor](https://github.com/jason-41/exchange-rate-monitor) — a packaged Windows utility for monitoring CNY exchange rates against major currencies.

## Engineering toolbox

| Area | Tools and methods |
| --- | --- |
| Programming & engineering | Python · C++ · Linux · Git · Docker · NumPy/SciPy · MATLAB/Simulink |
| Robotics systems | ROS 1/2 · TF · URDF · RViz · Pinocchio · OpenCV |
| Simulation | MuJoCo/MJX · Gazebo Harmonic · Gymnasium |
| Planning, control & optimization | Kinematics/dynamics · trajectory generation · motion planning · impedance control · PD · LQR/iLQR · MPC · GP-enhanced MPC · CasADi · acados |
| Robot learning | PyTorch · JAX · GPyTorch · imitation learning · reinforcement learning · 3D Diffusion Policy |
| Perception | RGB-D and point clouds · segmentation · 6D pose estimation and tracking · robot-frame transformations |

I also follow current work on ACT, RT-2, the π series, world models, and world action models while keeping my hands-on focus on DP3 training, deployment, and evaluation.

## Education & languages

- **Technical University of Munich** — M.Sc. Mechanical Engineering, expected August 2027
- **Xi'an Jiaotong University** — B.Eng. Mechanical Engineering, 2024
- **Languages:** Chinese (native) · English (IELTS 7.5) · Cantonese (conversational)

## Let's connect

I'm interested in robotics algorithms, control, robot learning, and real-world manipulation. Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/jia-cao41/).
