# Binghamton University ECD507 - Roboracer project for autonomous ML based RC cars
## Project Members:
  - Project Lead: Dylan Digiacomo (EE)
  - Finance Manager: Rishabh Hedge (CoE)
  - Hardware Lead: Andrew Meccariello (EE)
  - Software Lead: Charles Hodgins (CoE)
## Project Advisors:
  - Faculty Advisor: Prof. Douglas Summerville
  - Industry Advisors from Lockheed Martin:
      - Thomas Norton
      - Thomas Gaska
## Abstract
  - ECD507 F1 Tenth Autonomous Racecar is an ECD project sponsored by Lockheed Martin for the
2024-2025 academic year. It is a scale-up from the previous year’s ECD project using a larger car
capable of moving at 60mph. This project aims to test machine learning (ML) capabilities by
constructing a car based on the F1 Tenth Platform and having it run on an open-source AI/ML
platform. The car used for this project is a Traxxas Slash 4x4 Ultimate Edition, roughly 1/10th the
scale of an F1 car. The requirements for this project include the car being able to traverse around
a track autonomously, avoid obstacles, and recognize signs. The stretch goals for this project
include lane adjustment and the car reacting appropriately based on sign directives. The ML
platform is implemented on the NVIDIA Jetson Orin Nano (JON) which controls the car’s drive
system based on receiving data from an Inertial Movement Unit (IMU), a Lidar sensor, and a
camera. The ML model is trained using the different sensors. The ML platform is built usi
Robot Operating System 2 (ROS2) along with different frameworks such as Open Camera Visi
(OpenCV), and Pytorch.
