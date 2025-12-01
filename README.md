Deep Joint Source–Channel Coding (Deep JSCC) with RL Optimization

Author: Bhinit Rout

Affiliation: School of Engineering, Vellore Institute of Technology (VIT)

📄 Abstract

This repository contains the official implementation of the paper "Deep Joint Source–Channel Coding for Robust Wireless Image Transmission."

Traditional wireless image transmission pipelines (JPEG + Channel Codes) suffer from the "cliff effect" in low-SNR regimes. This project introduces a Deep Joint Source–Channel Coding (Deep JSCC) framework that treats image transmission as an end-to-end learning problem.

Core Innovation: Unlike standard Deep JSCC approaches that rely solely on backpropagation through a differentiable channel layer, this framework integrates a Reinforcement Learning (Policy Gradient) objective. This allows the transmitter to actively explore and learn noise-resilient feature constellations.
