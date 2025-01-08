---
layout: post
date: 2024-09-12 00:00:00
inline: true
related_posts: false
---

**[Research] Adaptive Neural Gradient Fields for Robot Planning and Control with Hardware in the Loop**  

We present a novel optimization-based approach for robot planning and control that significantly enhances performance and efficiency. Our method leverages neural networks to learn and model gradient fields, enabling more sophisticated handling of hardware differentiation challenges in real-world robotic systems.
In experimental validation using the Gymnasium HalfCheetah-v4 environment, our policy demonstrates remarkable sample efficiency. With just 100 training iterations and optimization over a 10-timestep horizon, we achieve stable forward locomotion with precise endpoint control. The trained agent successfully maintains continuous forward movement while accurately stopping at designated target positions, highlighting the method's effectiveness in both trajectory following and terminal state convergence.
This concise training paradigm represents a significant advancement in sample-efficient learning for complex locomotion tasks, particularly in scenarios requiring precise position control.

<video width="750" controls>
  <source src="/assets/video/100itr.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
