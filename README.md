# LEGO-Based Mobile Robot Navigation and Structure Identification

## Project Overview

This project involves creating a LEGO-based mobile robot that autonomously navigates along a predefined circular path and accurately identifies a structure placed at the center of the path. The robot is designed to complete one full rotation around the circle, during which it detects and classifies the shape (Square, Circle, or Triangle) at the center. This project focuses on autonomous navigation, real-time shape detection, and optimization techniques to ensure smooth movement and accurate identification.

## Key Features

- **Autonomous Navigation:** 
  - The robot autonomously navigates a circular path with a fixed radius (1.3 meters) using either model-based control or sensor-based line-following.
  
- **Shape Identification:** 
  - The robot uses sensors to detect and classify a shape (Square, Circle, or Triangle) placed at the center of the circle, based on its dimensions.
  
- **Control Algorithms:** 
  - PID (Proportional-Integral-Derivative) control or other optimization techniques are used to ensure smooth and precise movement around the circular path.
  
- **Sensor-Based Detection:** 
  - The robot employs sensors to classify the shape within one full rotation. The accuracy of the shape classification and the time taken for detection are crucial for evaluation.
  
- **Time Efficiency:** 
  - The robot aims to detect the shape efficiently within a predefined time, allowing comparison of performance against other groups.

---

## Project Structure

### 1. **Navigation Mechanism:**
   - The robot can navigate the circular path using either mathematical modeling or line-following sensors.
   - If model-based navigation is chosen, control algorithms are developed to ensure the robot follows a circular trajectory with a radius of 1.3 meters.
   - If sensor-based navigation is selected, the robot uses line-following sensors to trace the circular path.

### 2. **Shape Detection:**
   - The robot detects the structure in the center of the circle by measuring its dimensions and classifies it as either a square, circle, or triangle.
   - The detection process occurs within one complete rotation of the robot around the path.

### 3. **Optimization and Control:**
   - The robot applies PID control or other optimization methods to minimize deviations from the circular path and ensure smooth movement.
   - The system continuously adjusts its velocity and heading to maintain accuracy during navigation and shape detection.

### 4. **Code and Algorithms:**
   - Source code for both navigation and detection algorithms is included.
   - Block diagrams, flowcharts, and mathematical models for navigation and shape detection are provided to better understand the algorithms.

---

## Installation

To set up the project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Thisakya-Anudini/LEGO-Robot-Nav-Shape-Identifier.git
