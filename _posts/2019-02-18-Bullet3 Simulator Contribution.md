---
layout: post
title: Bullet3/pybullet Simulator Contribution
---

**Bullet3/pybullet** is very popular physics simulator, widely used for reinforcement learning, graphics and robotics. 

Now the deep_mimic environment has the **support for a popular motion capture dataset, Human3.6M**. I've contributed an specialized **inverse kinematics** module to pybullet_env/deep_mimic, so the 3D position data(not necessary needs to be in Human3.6M) can be transformed to quaternions(control parameters), which can be used by the humanoid agent in bullet simulator. See [[Bullet3](https://github.com/bulletphysics/bullet3/pull/2105)]
