# fall-2024-final-project-team-11

## Abstract
We propose developing an autonomous car navigation system using Rapidly-Exploring Random Trees (RRT) with LiDAR for real-time environment mapping and obstacle detection.  Using LiDAR, the system will create a virtual map, enabling the RRT algorithm to identify viable paths around obstacles. A local planner using the Regulated Pure Pursuit Controller will use generated waypoints to guide the car to the target, while real-time controls (x = u̇, v̇, θ̇) will manage the car’s movement. This setup allows for real-time decision-making, enabling the car to differentiate between obstacles on the fly and navigate dynamically toward its goal.

<hr>
