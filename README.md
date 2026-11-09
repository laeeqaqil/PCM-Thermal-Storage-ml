# Data-Driven Performance Prediction for Dual-Bank PCM Thermal Energy Storage

## Overview

This repository contains the machine-learning and data-analysis workflow for a
dual-bank lauric acid PCM latent heat thermal energy storage (LHTES) system
integrated with a solar thermal collector (0.726 m² aperture, 3 kg PCM).

Two models are developed:

1. **Random Forest** — predicts thermal efficiency from operating conditions
   (solar irradiance, ambient temperature, PCM temperatures, humidity).
   Test-set performance: **R² = 0.927**.
2. **LSTM** — predicts transient PCM/chamber temperature profiles as a
   time-series problem, supporting predictive control.

The work supports a published Indian patent (No. 202621015051 A) on a dual-zone
PCM thermal storage system with predictive control.

## Repository structure
