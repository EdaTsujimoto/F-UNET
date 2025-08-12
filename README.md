Repo-F-UNet: Semi-Supervised Road Damage Segmentation for Intelligent Transportation Systems
This repository contains code and resources for our paper:


Overview
A modular, semi-supervised segmentation framework designed to detect and localize both subtle surface degradations and large-scale obstructions in road environments. The framework integrates three core components:

Hybrid Dataset Integration – Combines multiple sources to capture both routine and disaster-induced road conditions.

Teacher–Student Semi-Supervised Learning – Reduces annotation requirements by leveraging pseudo-labeling and progressive self-training.

F-L-D-E Module – Enhances class-specific feature learning, improving detection of rare and small-scale anomalies.

This approach is tailored for annotation-scarce, visually heterogeneous, and operationally complex environments common in ITS and post-disaster scenarios.

Datasets
The framework uses a hybrid dataset combining:

PDRDDJ – Post-Disaster Dataset Japan

SoDR – Social Media Dataset for Disaster-Induced Road Damage

RDD2022 – Road Damage Dataset 2022 (Japan)

The unified taxonomy includes 11 classes.

Results

Removed to avoid plagiarism.

Repository Structure
funet_mini/ – Minimal version of the framework with 20% labeled setting

supplementary documents / since paper is only 10 pages we'll share supportive results here which didn't fit on paper.

scripts/ – Data preprocessing, training, and evaluation scripts

configs/ – Model and training configuration files

README.md – This document
