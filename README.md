<div align="center">
# DevConTorchCPU <!-- omit in toc -->
Development container for ML with PyTorch on CPU
</div>

## Purpose
*Development container* drastically improve DX.  
In *Machine Learning*, GPU is indispensable for training, but CPU environment is sufficient and cost-effective for development.  
If we have **dev container of PyTorch for CPU**, the ML DX come true.  
This is it.  

## Design
We assume **Deployment on Google Colaboratory**.  
All library versions basically follow it.  

### Contents
- Python
- NumPy
- PyTorch cpu (can install colab-exact cuda version, but it is heavy (e.g. 1.11.0cpu 169.1 MB vs 1.11.0cu113 1637.0 MB))
- Torchaudio cpu
