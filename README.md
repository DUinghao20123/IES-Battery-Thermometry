IES-Battery-Thermometry

Code and representative experimental data associated with the paper:

Operando electrochemical thermometry: A few-shot domain alignment framework for real-time core temperature monitoring in lithium-ion batteries

eScience Energy

Overview

This repository provides the implementation of the few-shot domain alignment network (FSDA-Net) for non-invasive lithium-ion battery internal temperature estimation using electrochemical impedance measurements.

The framework combines dynamic impedance sensing with few-shot domain alignment to enable temperature estimation across different battery chemistries and aging states.

Repository Contents

The IES_Temperature_Estimation_Data_Code.rar archive contains:

Python code: FSDA-Net implementation for battery internal temperature estimation.

MATLAB code: Impedance–temperature correlation analysis.

Source data: Offline impedance measurements used for model training.

Alignment data: Few-shot target-domain samples used for model adaptation.

Target data: Representative impedance measurements and internal temperature labels used for model evaluation.

Usage

Download and extract the RAR archive.

Install the required Python packages, including PyTorch, NumPy, SciPy, and Matplotlib.

Adjust the data file paths in the Python scripts according to your local directory structure.

Run FSDA-NET.py for model training and temperature estimation.

Data Availability

This repository provides representative datasets for reproducing selected temperature estimation results. Additional experimental data are available from the corresponding author upon reasonable request.

License

This repository is distributed under the MIT License. See the LICENSE file for details.
