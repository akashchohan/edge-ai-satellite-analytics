# Edge AI Satellite Analytics

This project explores lightweight AI pipelines for analysing Earth Observation (EO) imagery directly on low-power edge computing devices such as NVIDIA Jetson and Raspberry Pi.

The goal is to investigate how satellite image analytics can be executed closer to the sensor using constrained hardware, enabling faster processing and reduced data transmission requirements.

## Motivation

Modern satellites collect large volumes of imagery that must be transmitted to ground stations before analysis. This creates latency and bandwidth limitations.

Edge AI enables onboard processing so that satellites can extract useful insights directly on the platform before transmission.

## Objectives

- Develop lightweight computer vision models for EO image analysis
- Optimise inference for low-power devices
- Evaluate model performance under constrained compute conditions
- Explore applications such as atmospheric pattern detection and environmental monitoring

## Planned Experiments

- Satellite dataset preprocessing
- Lightweight CNN model testing
- Model quantisation and optimisation
- Deployment tests on Raspberry Pi and Jetson devices

## Target Hardware

- NVIDIA Jetson Nano / Orin Nano
- Raspberry Pi 4 / Raspberry Pi Zero

## Tech Stack

Python  
PyTorch  
OpenCV  
NumPy

## Future Work

- Implement prototype inference pipelines
- Evaluate energy efficiency of models
- Benchmark latency on embedded hardware
