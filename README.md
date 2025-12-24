Smart Helmet and Accident Detection System
 Overview

The Smart Helmet and Accident Detection System is an IoT-based safety solution designed to enhance the protection of two-wheeler riders. The system integrates multiple sensors with an ESP32 microcontroller to ensure helmet compliance, prevent drunk driving, detect accidents in real time, and automatically send emergency alerts with location details.

This project aims to reduce road accident fatalities by minimizing emergency response time and enforcing responsible riding behavior through intelligent automation.

 Objectives

Ensure the rider wears the helmet before vehicle ignition

Detect alcohol consumption and prevent drunk driving

Automatically detect accidents using motion sensors

Send real-time emergency alerts with GPS location

Improve road safety using low-cost embedded and IoT technologies

 System Architecture

The system is built around the ESP32 microcontroller, which collects data from multiple sensors and triggers actions based on predefined conditions.

Key Functional Modules:

Helmet Wear Detection

Alcohol Detection

Accident Detection

Location Tracking

Emergency Alert System

 Hardware Components

ESP32 Microcontroller – Central processing and wireless communication

MPU6050 Accelerometer & Gyroscope – Accident and tilt detection

MQ-3 Alcohol Sensor – Detects alcohol in rider’s breath

IR Sensor – Detects helmet usage

GPS (via Google Maps integration) – Location tracking

Buzzer & LEDs – Audio-visual alerts

Rechargeable Battery – Power supply

 Software Components

Arduino IDE – Programming and firmware upload

Embedded C/C++ – Control logic and sensor interfacing

Twilio API – SMS/WhatsApp emergency alerts

ESP32 Web Server – Location updates and monitoring

 Working Principle

The IR sensor verifies whether the helmet is worn.

The MQ-3 sensor checks for alcohol levels in the rider’s breath.

The MPU6050 continuously monitors acceleration and orientation.

If a severe impact and abnormal tilt are detected, an accident is confirmed.

GPS coordinates are captured and sent via Twilio to registered emergency contacts.

A manual SOS trigger is also provided for emergencies.

 Results

Helmet usage, alcohol detection, and accident detection achieved 93–96% accuracy

Emergency alerts delivered within 5 seconds

Reliable real-time location sharing through Google Maps

Successful SMS/WhatsApp alert delivery using Twilio

 Future Enhancements

Machine learning-based accident severity classification

Dedicated mobile application for live tracking and alerts

Integration of health monitoring sensors (heart rate, ECG)

Cloud-based data logging and analytics

Compact and lightweight helmet module design

 Academic Details

Course: Mini Project

Degree: Bachelor of Engineering (B.E.)

Branch: Electronics and Communication Engineering

University: Visvesvaraya Technological University (VTU)

Institute: Bangalore Institute of Technology, Bengaluru

Academic Year: 2025–2026

 Team Members

Rakshita (1BI23EC124)

Shreya Biradar (1BI23EC149)

 Project Guide

Ms. V. Shylaja
Assistant Professor
Department of Electronics and Communication Engineering
Bangalore Institute of Technology
