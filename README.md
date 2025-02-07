# VR Rehabilitation Game for Post-Stroke Recovery

## Overview
The **VR Rehabilitation Game** is designed to aid post-stroke recovery by immersing users in an engaging virtual environment. Developed in **Unreal Engine 5** for its robust support for Meta Quest, the project enables intuitive user interactions such as object manipulation, teleportation, and combat, creating a therapeutic and enjoyable experience.

## Features

### 1. **Object Interaction and Movement**
- Users can grab and manipulate objects.
- Teleportation using controllers or hand gestures for intuitive navigation.
- Grab a pistol to shoot at enemies or move objects by shooting them.

### 2. **Dynamic Enemies and Health Systems**
- **Robots**: Equipped with health bars that deplete upon collisions (environment or pistol projectiles). Upon destruction:
  - An explosion effect occurs.
  - The robot disappears.
- **Stormtroopers**: Static meshes that react similarly to robots upon being shot.
- **SKM Quinn**: Performs animations based on interactions:
  - First hit: "Crying" animation.
  - Subsequently attacks the user and can be defeated.
- **Witch**: Reacts to gunfire by jumping and moving towards the user, eventually defeated by gunshots.

### 3. **Basketball Activity**
- Users can throw basketballs at groups of robots or a pyramid of cubes:
  - Robots topple over, experience collisions, lose health, and trigger a large explosion.
  - Cubes in the pyramid collapse on impact.
- Continuous play: New basketballs spawn at the original location after being thrown.

### 4. **AI Therapist**
- Integrated an AI character acting as a virtual therapist:
  - Motivates users to perform rehabilitation activities.
  - Designed for interactions that encourage movement of a semi-paralyzed limb.

### 5. **Experimental Hand Tracking**
- Implemented hand tracking for controller-free interactions.
- Gestures enable teleportation and object manipulation via collisions.

## Technical Details
- Developed in **Unreal Engine 5** for high-fidelity graphics and VR support.
- Dynamic animations, health systems, and interactions for an immersive experience.
- Continuous spawning mechanisms for uninterrupted gameplay.
- Explosions and physics-based interactions for realism and engagement.

## Future Enhancements
- Improved AI therapist with speech capabilities for real-time feedback.
- Enhanced hand tracking for more precise and natural interactions.
- Additional rehabilitation-focused activities for diverse user needs.

---
This project demonstrates the potential of VR in therapeutic contexts, combining fun gameplay mechanics with purposeful recovery activities.
