# Climate Forecasting Models

This repository contains two deep‐learning–based weather forecasting pipelines built with PyTorch Lightning and ClimateLearn. You will find:

- **Two model variants**  
  - **ResNet Forecasting (24 hrs)** — a ResNet‐based encoder–decoder  
  - **U-Net Forecasting (24 hrs)** — a classic U-Net architecture  
  - **Pretrained checkpoints** and **training logs** for each variant  
- A single Jupyter notebook (`Model.ipynb`) that runs end-to-end training, evaluation, and result reproduction  
- A `requirements.txt` listing all Python dependencies  

Follow the steps below to reproduce our results on your machine.

## 1. Run Step

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. **Create a Python environment**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

3. **Running the Models**  
   ```bash
   jupyter notebook Model.ipynb


