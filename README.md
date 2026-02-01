# LogiTech-AI-Systems
AI-based driver fatigue detection system for the logistics industry. Uses computer vision and deep learning to monitor driver alertness.
#Driver Fatigue Detection System

## Project Overview
South Africa’s logistics industry faces major risks due to driver fatigue, especially among long-haul truck drivers. Fatigue leads to slower reaction times, reduced alertness, and often fatal accidents. Manual supervision of every driver is not feasible.

This project proposes a camera-based fatigue detection system that monitors drivers in real-time using a webcam feed. By analyzing facial features such as eye blinks, yawning, and nodding off, the system raises a loud alert when signs of drowsiness are detected, potentially saving lives and reducing accidents in the logistics sector.

## Problem Statement
- Truck drivers often drive long hours, leading to fatigue.  
- Fatigue is one of the leading causes of road accidents in logistics.  
- Manual monitoring is not practical for every vehicle.
- ## Proposed Solution
We are building a local camera application that can:
- Detect driver fatigue signs (slow blinking, yawning, nodding off).  
- Provide a live camera feed with detection results.  
- Trigger an alert system when drowsiness is detected.  

## Technology Stack
- Python (Backend) → Core logic.  
- OpenCV → Handles camera input and image processing.  
- MediaPipe → Detects facial landmarks (eyes, mouth, head position).  
- Flask → Enables communication between browser and backend.  
- Datasets → Includes collected pictures and videos (open/closed eyes, yawns, etc.) for testing.  
## System Workflow
1. Camera Input → Captures driver face in real-time.  
2. Face & Eye Detection → Uses MediaPipe to track landmarks.  
3. Fatigue Analysis → Checks for yawning, blinking frequency, nodding.  
4. Fatigue Status → Displays as `Normal` or `Drowsy`.  
5. Alert → If drowsiness is detected, system plays a loud warning sound.  

## Team Work Division
- Backend (Python) → Implement fatigue detection logic.  
- OpenCV Integration → Handle live video feed and image processing.  
- Flask App → Build browser-based interface for testing and monitoring.  
- Testing → Record short videos and collect examples (open eyes, closed eyes, yawning).  
- Report Writing → Document research, implementation, and results.
- ## Dataset
- Images and videos of drivers with various states (normal, blinking, yawning, drowsy).  
- Used for testing the detection process.  

## Future Improvements
- Add mobile app integration for real-world deployment.  
- Implement cloud connectivity for fleet monitoring.  
- Explore advanced methods for higher accuracy.  

## Research Background
The solution is based on research into South Africa’s logistics sector, where fatigue is a major contributor to accidents. A camera-based system provides a scalable and practical solution to enhance road safety, reduce accidents, and improve logistics efficiency.
