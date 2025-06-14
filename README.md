# AnomalyGPT

## 🧾 Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Demonstration](#demonstration)

## Overview

AnomalyGPT is a large vision-language model (LVLM) framework designed for industrial anomaly detection, combining the interpretability of natural language with powerful visual reasoning. Built on top of pretrained components such as ImageBind, Vicuna-7B, and PandaGPT, AnomalyGPT can detect and localize visual defects in manufacturing objects using both textual prompts and support images.

Unlike traditional anomaly detectors that rely on handcrafted features or dense patch comparisons, AnomalyGPT leverages the strengths of Large Language Models (LLMs) to generate natural language justifications and detailed pixel-level anomaly maps.

This repository contains:
- Setting up the Virtual Machine on Google Cloud Console (recommended if your OS RAM is less than 32 GB)
- Reproduced evaluation pipelines for MVTec-AD and VisA datasets
- Benchmarking procedure for zero-, one-, and two-shot settings

## Getting Started

### 1. Virtual Machine Setup
This content would guide you through the detailed procedure of installing a Virtual Machine via SSH from Google Cloud Console. To do the following, follow these steps:<br><br>
i) Make sure you have a valid google account, and remaining credit score of atleast 150 $ for the model to run most of its components and have a quota for 1 GPU (if not, request a quota for increasing the credit to atleast 150 $)<br>

ii) On the Cloud Console, navigate to Google Compute Engine -> VM instances<br>

iii) Create a new instance<br>

iv) Select NVIDIA L4 and region should be selected based on this <a href="https://cloud.google.com/compute/docs/gpus/gpu-regions-zones">link</a><br>

v) Select the g2-standard-8 series (with 8 vCPU, 4 core, 32 GB memory or higher, if the budget allows)<br>

vi) Make sure the image of VM is selected to <b>Deep Learning VM with CUDA 11.8 M126</b><br>

This way, the Virtual Machine with NVIDIA CUDA support is created and a browser specific-SSH terminal is also opened, asking you to install NVIDIA driver for you (you must allow it by typing and entering "yes")<br>

In order to integrate the SSH terminal into the VS Code, watch this video - [https://youtu.be/Cb13DAB59Po?si=30gMQu1rhx4gn7LO]<br>

Now the virtual machine is set up. Let us continue with the project

### 2. Code Reproduction Process

Clone the repository locally:

<pre> okj </pre>

## Demonstration
