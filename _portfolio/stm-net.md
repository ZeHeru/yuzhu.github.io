---
title: "Reconstruct Molecular Orbitals from STM Images via AI"
excerpt: "Physics-driven STM image restoration with STM-Net; PSNR > 37 dB with 10% training data and > 43 dB on the full dataset."
collection: portfolio
permalink: /portfolio/stm-net
---

In a nutshell: **Are orbitals observable?**

This project reconstructs pristine molecular-orbital information from STM images. I simulate STM images at the DFT level using Bardeen's approximation and develop STM-Net, a physics-driven U-Net that separates s-wave molecular-orbital signals from p-wave CO-tip contributions.

Key ingredients include Tersoff-Hamann theory, Chen's derivative rule, STM simulation, DAE/U-Net/Mask2Former models, and physics-informed image restoration.

[Code](https://github.com/ZeHeru/STM_net/tree/main)
