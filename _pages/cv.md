---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV as PDF]({{ base_path }}/files/cv.pdf)

Contact
======
* Yu Zhu
* Email: [23210220065@m.fudan.edu.cn](mailto:23210220065@m.fudan.edu.cn)
* GitHub: [ZeHeru](https://github.com/ZeHeru)
* Google Scholar: [Google Scholar](https://scholar.google.com/)
* Location: Shanghai, China

Education
======
* **M.Sc., Department of Chemistry, Fudan University**, Shanghai, China, 09 2023 - 06 2026
  * Supervisor: Prof. Xin Xu and Young Researcher Sai Duan
  * Research interests: machine learning force fields, open-set recognition, scanning tunneling microscopy
* **B.Sc., College of Chemistry, Chemical Engineering and Materials Science, Soochow University**, Suzhou, China, 09 2019 - 06 2023
  * GPA: 3.8/4.0 (92.1/100)
  * Supervisor: Prof. Jianlin Yao and Assoc. Prof. Minmin Xu
  * Research interests: surface-enhanced Raman spectroscopy and fingerprint imaging
* Received verbal admission to the Ph.D. program at the California Institute of Technology for Fall 2026, advised by Prof. William A. Goddard III.

Experience
======
* **AI for Science Intern, Microsoft Research**, Shanghai, China, 07 2024 - 06 2025
  * Contributed to Microsoft's materials modeling framework, [MatterSim](https://www.microsoft.com/en-us/research/articles/mattersim/).
  * Developed generalized benchmarks to inform model architecture design and training data generation.
  * Ran inference on models up to 1B parameters and managed high-throughput datasets with up to 200M entries.
  * Built parallel computational pipelines on Azure Cloud for up to 10K concurrent tasks.
  * Worked with MatterSim and other universal machine learning force field architectures.

Projects
======
* **[Reconstruct Molecular Orbitals from STM Images via Artificial Intelligence Approaches](https://github.com/ZeHeru/STM_net/tree/main)**, 01 2024 - 07 2024
  * In a nutshell: Are orbitals observable?
  * Simulated STM images at the DFT level using Bardeen's approximation.
  * Developed STM-Net, a physics-driven U-Net, to segment s-wave molecular-orbital signals from p-wave CO-tip contributions.
  * Incorporated Tersoff-Hamann theory and Chen's derivative rule; reached PSNR > 37 dB with 10% of the training data and > 43 dB on the full dataset.
  * Key skills: STM simulation, DAE, U-Net, Mask2Former.
* **[MatterSim: A Deep Learning Atomistic Model](https://github.com/microsoft/mattersim)**, 07 2024 - 06 2025
  * In a nutshell: a unified multimodal foundation model for precise and generalizable in silico materials characterization.
  * Built benchmarks and computational workflows for model architecture design, data generation, and materials property prediction.
  * Key skills: VASP, Python, atomate2, joblib, phonopy, phono3py, ESEN, MACE, ORB.
* **MPBR: Multimodal Progressive Bidirectional Reasoning for Open-Set Fine-Grained Recognition**, 01 2025 - 06 2025
  * In a nutshell: suppressing semantic drift in open-set recognition.
  * Developed benchmark pipelines and evaluated leading OSR models on iNat2021-OSR.
  * Prior MPBR work improved state of the art on iNat2021-OSR by 2.6% AUROC and 2.5% OSCR and was submitted to ICCV 2025.
  * Key skills: t-SNE, Grad-CAM, Swin Transformer, HAN-OSFGR.
* **SERS Imaging on Flexible Substrates for Fingerprint Identification Research**, 04 2021 - 06 2023
  * Developed a SERS-based imaging approach for fingerprint recognition and chemical mapping of latent and live fingerprints.
  * Collected fingerprint samples, performed SERS imaging, and analyzed the results.
  * Key skills: SERS mapping, Origin visualization.

Publications
======
1. **Yu Zhu**, R. Xue, H. Ren, Y. Chen, W. Yan, B. Wu, S. Duan, H. Zhang, L. Chi, and X. Xu. "[Reconstructing Pristine Molecular Orbitals from Scanning Tunneling Microscope Images via Artificial Intelligence Approaches](https://pubs.acs.org/doi/10.1021/jacsau.5c00310)." *J. Am. Chem. Soc. Au*, 2025.
2. J. Li, Z. Chen, Q. Wang, H. Yang, Z. Lu, G. Li, S. Chen, **Yu Zhu**, X. Liu, J. Tan, M. Tang, Y. Zhou, C. Zeni, A. Fowler, D. Zügner, R. Pinsler, M. Horton, T. Xie, T.-Y. Liu, H. Liu, T. Qin, B. Lv, D. Donadio, and H. Hao. "[Probing the Limit of Heat Transfer in Inorganic Crystals with Deep Learning](https://doi.org/10.48550/arXiv.2503.11568)." 2025.
3. H. Yang, X. Liu, C. Hu, Y. Zhou, Y. Shi, C. Liu, J. Li, G. Li, Q. Wang, **Yu Zhu**, Z. Chen, S. Chen, C. Zeni, M. Horton, R. Pinsler, A. Fowler, D. Zügner, T. Xie, J. Smith, L. Sun, Y. Chen, Y. Bai, L. Kong, H. Hao, and Z. Lu. "[MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures](https://doi.org/10.48550/arXiv.2405.04967)." 2024.
4. J. Tan, P. Jing, **Yu Zhu**, and Y. Liu. "[MPBR: Multimodal Progressive Bidirectional Reasoning for Open-Set Fine-Grained Recognition](https://openaccess.thecvf.com/content/ICCV2025/html/Tan_MPBR_Multimodal_Progressive_Bidirectional_Reasoning_for_Open-Set_Fine-Grained_Recognition_ICCV_2025_paper.html)." *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025, pp. 1282-1291.
5. M. Wu, J. Tan, **Yu Zhu**, and J. Ren. "[KappaFormer: Physics-aware Transformer for lattice thermal conductivity via cross-domain transfer learning](https://arxiv.org/abs/2604.03547)." *arXiv*, 2026.
