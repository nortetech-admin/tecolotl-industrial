# Tecolotl Industrial

Industrial computer vision system for real-time safety monitoring using edge AI.


## Overview

Tecolotl Industrial is an edge AI system designed to monitor industrial environments in real time using computer vision.  
The system runs on low-cost hardware (Raspberry Pi + AI camera) and focuses on detecting unsafe conditions during operations such as welding.


## Problem

In many industrial environments, safety compliance depends on manual supervision, which is:

- Inconsistent
- Hard to scale
- Reactive instead of preventive

This leads to undetected risks and unsafe behaviors on the shop floor.


## Solution

Deploy an autonomous vision system that:

- Detects human presence in workstations
- Identifies active operations (e.g. welding)
- Captures real-world data for model training
- Enables future detection of PPE compliance and unsafe conditions


## System Concept

1. Camera detects a person in a workstation  
2. System triggers image capture  
3. Images are stored locally and uploaded to the cloud  
4. Dataset is curated and used to train detection models  


## Tech Stack

- Raspberry Pi
- Sony IMX500 (AI Camera)
- Python
- Computer Vision (YOLO - planned)
- Google Drive (data collection)


## Current Focus

- Dataset collection in real industrial environments  
- Detection of human presence  
- Automated image capture pipeline  


## Status

🚧 Early stage — data collection and system prototyping


## Vision
Build a scalable industrial monitoring system that improves safety, visibility, and operational intelligence using AI.
