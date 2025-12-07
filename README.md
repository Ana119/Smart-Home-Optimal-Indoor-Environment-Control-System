# OCF-IoTivity Smart Home Energy & Comfort Optimization System

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![IoTivity 2.2.2](https://img.shields.io/badge/IoTivity-2.2.2-green.svg)](https://iotivity.org/)
[![Java](https://img.shields.io/badge/Java-51.8%25-orange.svg)](https://www.java.com/)

An Open Connectivity Foundation (OCF) based prediction-assisted optimal control framework for smart homes that optimizes energy consumption while maximizing occupant thermal comfort. This is the **first scalable, secure, and interoperable optimal control solution** for smart-home IoT networks.

## 🌟 Key Achievements

- **36.82% Energy Savings** - Significant reduction in HVAC energy consumption
- **3.36ms Round Trip Time** - Ultra-low latency for real-time control
- **5s Average Response Time** - Fast actuator control and adjustment
- **Cohen's κ=0.765** - Substantial inter-rater agreement for thermal comfort prediction
- **R² > 0.94** - High accuracy in energy and environmental parameter prediction

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Setup Guide](#setup-guide)
- [Usage](#usage)
- [Results](#results)
- [API Documentation](#api-documentation)
- [Publication](#publication)
- [Contributing](#contributing)
- [Citation](#citation)
- [License](#license)

## 🎯 Overview

Traditional Home Energy Management Systems (HEMS) face significant challenges:
- **Interoperability issues** across heterogeneous IoT devices
- **Energy vs. Comfort trade-off** not adequately addressed
- **Scalability limitations** with proprietary protocols
- **Security and privacy concerns** in smart home networks

Our solution addresses these challenges through:

1. **OCF-IoTivity Framework** - Standardized, secure device connectivity
2. **Edge Intelligence** - LSTM models deployed on IoT devices for real-time predictions
3. **Improved Firefly Algorithm** - Enhanced optimization with inertia weight approach
4. **Dual-Objective Optimization** - Balances energy efficiency and occupant comfort

## ✨ Features

### Core Capabilities

- ✅ **Real-time Environmental Monitoring**
  - Temperature, humidity, air velocity sensing
  - Mean radiant temperature measurement
  - Energy consumption tracking

- ✅ **Predictive Analytics**
  - LSTM-based energy consumption prediction
  - Environmental parameter forecasting
  - PMV (Predicted Mean Vote) comfort prediction

- ✅ **Intelligent Optimization**
  - Modified Firefly Algorithm with logarithmic inertia weight
  - Multi-objective optimization (energy + comfort)
  - User preference-based control (α parameter)

- ✅ **OCF Connectivity**
  - Seamless peer-to-peer device communication
  - Protocol-agnostic interoperability
  - Secure device on-boarding and provisioning

- ✅ **Mobile Application**
  - Real-time environment monitoring
  - User preference configuration
  - Energy consumption visualization

## 🏗️ System Architecture

### Architecture of the Proposed Model
