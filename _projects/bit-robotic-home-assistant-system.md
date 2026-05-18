---
title: BIT - An AI-Powered Spatial-Intelligence Vision-Robotic Home Assistant System
description: AI-powered ROS2 robotic assistant for autonomous navigation, voice-command interaction, robotic manipulation, and multimodal perception for elderly and physically challenged individuals.
status: Active
featured: false
order: 6
image: /assets/images/projects/bit-home-assistant.jpg
duration: 2025 - Present
funding: University Research Grant
team:
  - Md Yasin Arafat
  - Farhana Mehazbin Tusti
  - Dr. Shahnewaz Siddique
---

![BIT Robotic Home Assistant System](/assets/images/projects/spatial-intelligence-robot-sim.jpeg)

## Overview

Assistive robotic systems capable of understanding natural language commands and operating autonomously in dynamic environments are becoming increasingly important for real-world human-robot interaction. This project develops BIT (Butler Intelligent ToolKit), an AI-powered robotic home assistant designed to provide physical assistance for elderly and physically challenged individuals. Built on a ROS2-based architecture with a Jetson SBC, STM32 real-time controller, and a 6-DOF robotic arm, the system integrates real-time perception, autonomous navigation, robotic manipulation, and multimodal AI reasoning to execute complex assistive tasks seamlessly.The system is particularly relevant for domestic robotics, healthcare assistance, intelligent caregiving, and collaborative human-robot interaction. By integrating computer vision, voice-command recognition, LLM/VLLM-based reasoning, SLAM-based navigation, and robotic manipulation, BIT provides a robust framework for interactive robotic assistance that extends beyond conventional automation, enabling robots to operate alongside humans naturally and safely.Using modern AI perception models and a modular ROS2 framework, the system has been validated on a real robotic platform integrating autonomous navigation, object tracking, robotic arm control, and voice-command-driven interaction. Real-world deployment demonstrates interactive user assistance, semantic scene understanding, intelligent object tracking, and autonomous delivery capabilities.

## Objectives

- Develop an AI-powered robotic assistant capable of autonomous navigation and real-time interaction in indoor environments.
- Implement voice-command-driven robotic motion, object tracking, and robotic arm manipulation.
- Enable autonomous localization and waypoint-based navigation for assistive delivery tasks.
- Integrate perception, robotic control, and LLM/VLLM-based reasoning into a unified ROS2 framework for multimodal human-robot interaction.
- Ensure operational safety through PID-based control, obstacle avoidance, and real-time hardware monitoring.

## Methodology

The proposed system leverages a modular ROS2 architecture deployed on NVIDIA Jetson platforms, integrating perception, AI reasoning, and coordinated motion control. Visual perception employs OpenCV, YOLOv5 TensorRT, NanoTrack TRT, and MediaPipe for real-time object detection, tracking, gesture recognition, and fall detection, where detected objects are mapped into actionable robotic behaviors through ROS2 communication pipelines. High-level task orchestration is managed by Large Language Models (LLMs) and Vision-Language Models (VLLMs), enabling natural-language command interpretation and semantic scene understanding for autonomous robotic interaction. For navigation, the system combines Simultaneous Localization and Mapping (SLAM Toolbox) with the Nav2 navigation stack to support obstacle-aware autonomous movement using a mecanum-wheel mobile base. Real-time robotic control is achieved through PID-based chassis control and inverse kinematics for the 6-DOF robotic arm, while a custom UART communication protocol ensures deterministic low-level execution between the ROS2 middleware and STM32 microcontroller. Finally, the integrated system is validated through real-world experiments involving voice interaction, autonomous navigation, robotic manipulation, semantic object tracking, and assistive task execution.

## Current Progress

Completed real-world implementation and validation for individual system modules:
  - Part 1: ROS2 and STM32 real-time communication framework
  - Part 2: Autonomous navigation using SLAM Toolbox and Nav2
  - Part 3: Voice-command interaction using ASR, LLM/VLLM, and TTS
  - Part 4: PID-based line following and object tracking
  - Part 5: Robotic arm manipulation and color sorting
  - Part 6: YOLOv5 TensorRT garbage classification
  - Part 7: Vision-based fall detection system
  - Part 8: LLM-guided robotic motion execution
  - Part 9: VLLM-based semantic tracking and navigation
- Real-world deployment and integrated task validation are ongoing across all assistive modules
- Upcoming milestones: on-device quantized LLM deployment, Bangla ASR integration, multi-object VLLM tracking, dynamic environment-aware navigation, and fully integrated assistive home deployment