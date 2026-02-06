# DNN-Based Power System State Estimation (MATLAB Project)

Portfolio project demonstrating a data-driven state estimation pipeline for a power
transmission system using a Deep Neural Network (DNN). The workflow includes
MATLAB-based dataset generation (multiple loading scenarios), noise modeling
(multi-level Gaussian measurement noise), DNN training, and evaluation on the
IEEE 14-bus system.

This project was also used as the basis for an IEEE conference publication (PDF
included in this repository).

## Key Highlights

- Designed a complete data-driven state estimation workflow in MATLAB
- Generated large-scale training data using load-flow simulations with multiple
  P–Q loading scenarios on the IEEE 14-bus system
- Modeled realistic measurement uncertainty using multi-level Gaussian noise
  to reflect practical metering conditions
- Trained and evaluated a Deep Neural Network (DNN) for voltage magnitude and
  angle estimation
- Compared robustness and behavior against classical WLS-based state estimation
- Translated research results into a reproducible engineering workflow suitable
  for offline analysis and fast inference

## Project Scope & Limitations

- This project was implemented primarily in MATLAB as an offline research and
  engineering workflow
- The focus is on data generation, noise modeling, neural network training, and
  evaluation rather than on deployable software
- Experimental scripts and datasets were developed for research purposes and are
  not included as reusable or production-ready code
- The repository is intended to demonstrate problem formulation, modeling
  decisions, and engineering reasoning rather than to serve as a ready-to-run tool

## Tools & Technologies

- MATLAB (load-flow simulation, data generation, neural network training)
- Deep Neural Networks (fully connected, multi-layer architecture)
- Power System Analysis (state estimation, IEEE 14-bus system)
- Statistical Noise Modeling (multi-level Gaussian measurement noise)
- Data Preprocessing and Scaling
- Offline Model Evaluation and Performance Analysis

## Related Research Publication

The work presented in this project formed the basis for an IEEE conference
publication, which validates the methodology and results through peer review.

**Title:** Data Driven Approach for Power System State Estimation with Consideration of Multi-Level Noise  
**System:** IEEE 14-bus power transmission network  
**Focus:** Robust DNN-based state estimation under realistic measurement noise

The paper PDF is included in this repository for reference.
