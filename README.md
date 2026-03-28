# Laser Tracking Dual Servo System

## Overview
This project is a dual-servo laser tracking system that follows real-time input across two axes. The system uses stacked servo motors to control horizontal and vertical movement, allowing a mounted laser to track motion smoothly.

The base implementation was adapted from an existing open-source project, and I extended it by building the physical system, testing performance, and improving control behavior.

---

## System Design

- Arduino (C++)
- Dual servo motors (pan/tilt setup)
- PWM signal control
- Laser module mounted on servo frame

The system translates input into servo angles, allowing the laser to track movement dynamically.

---

## My Contributions

- Built the full physical system (servo mounting, wiring, laser integration)
- Tuned servo movement to improve smoothness and reduce jitter
- Tested system response under different movement speeds
- Adjusted control logic for better stability and tracking accuracy

---

## Challenges

- Servo jitter and unstable movement at certain angles  
- Limited precision due to PWM resolution  
- Maintaining smooth tracking across both axes simultaneously  

---

## Improvements

- Adjusted servo update timing to reduce jitter  
- Tuned angle increments for smoother motion  
- Improved responsiveness without sacrificing stability  

---

## Results

- Smooth real-time tracking across two axes  
- Improved stability compared to initial implementation  
- Reliable performance under continuous operation  

---

## Media

(Add photos and/or a short demo video here)

---

## Notes

This project was originally based on an open-source implementation, but was extended through hands-on building, testing, and performance tuning to better understand real-world servo control behavior.
