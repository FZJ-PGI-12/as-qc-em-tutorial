# Autumn School Quantum Computing and Simulations for Energy Materials
## Qiskit tutorial

[![pipeline status](https://jugit.fz-juelich.de/pgi-12/documents/teaching/autumn_school_qcs_energy_materials/badges/main/pipeline.svg)](https://jugit.fz-juelich.de/pgi-12/documents/teaching/autumn_school_qcs_energy_materials/-/commits/main) 

This is an tutorial to get you started with the basics of quantum computation and the syntax used in Qiskit.

### Guide

We have prepared two tutorials to teach you the very basics of quantum computation as well as a simplified method of the quantum phase estimation which allows you to determine the eigenenergies of a $H_2$ molecule. You can find them in

- [T1_Quantum_circuits.ipynb](https://jugit.fz-juelich.de/teaching/ws_qfe/-/blob/main/T1_Quantum_circuits.ipynb)
- [T2_Quantum_phase_estimation.ipynb](https://jugit.fz-juelich.de/teaching/ws_qfe/-/blob/main/T2_Quantum_phase_estimation.ipynb)

If you are interested in real quantum hardware you can read the nootebook

- [use_ibmq_computer.ipynb](https://jugit.fz-juelich.de/teaching/ws_qfe/-/blob/main/use_ibmq_computer.ipynb)

### Installation

Recommended: Use some virtual environment. E.g. [conda over miniforge](https://github.com/conda-forge/miniforge), and create a new environment:

    conda create -n qiskit

Activate environment

    conda activate qiskit

Install required packages

    conda install pip
    pip install -r requirements.txt
