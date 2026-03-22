# Fluid Sloshing Simulator

A neural network-based simulator for efficient and robust fuel sloshing dynamics in aerospace applications. This project explores deep learning methods to accelerate complex fluid-structure interaction simulations, providing a fast alternative to traditional computational fluid dynamics (CFD) solvers.

## Key Features
*   Implements DualFluidNet: an attention-based dual-pipeline network for accurate fluid motion prediction.
*   Specialized for simulating fuel sloshing under aircraft maneuvering conditions.
*   Provides significantly faster inference times compared to conventional numerical simulation.
*   Robust handling of free-surface flows and fluid-structure interactions.

## Tech Stack
*   Python
*   PyTorch
*   NumPy / SciPy
*   Matplotlib (Visualization)

## Getting Started
```bash
git clone https://github.com/zoreanuj/fluid-sloshing-simulator.git
cd fluid-sloshing-simulator
pip install -r requirements.txt
python train.py --config configs/default.yaml
```