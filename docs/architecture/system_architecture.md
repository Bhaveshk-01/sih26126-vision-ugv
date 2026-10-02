# System Architecture

## Autonomous Navigation Pipeline

Camera
  ↓
Visual Perception
  ↓
Obstacle / Terrain / Free-Space Information
  ↓
Traversability + Uncertainty Map
  ↓
Visual Localization
  ↓
Navigation Costmap
  ↓
Path Planning
  ↓
Motion Controller
  ↓
UGV

The system continuously receives new camera observations and updates
the navigation state to support dynamic obstacle avoidance and
replanning.
