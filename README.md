# Conditional-Probability-Correction-in-Power-Outage-Risk-Analysis-under-Extreme-Weather

This repository provides the code implementation for the paper **"Bias in sequential Monte Carlo simulation for power outage risk analysis under extreme weather: A perspective based on conditional probability"**, including implementations for the two test systems (System#1 and System#2) featured in the paper. Details of the paper and citation format will be provided later.

Under normal circumstances, after configuring Python, Jupyter Notebook, and the required third-party libraries, you can directly execute `main.ipynb` to obtain the simulation results. Result files are saved in the `SolutionFolder` directory. `main.ipynb` contains visualization code (recommended to run this notebook using VS Code, Jupyter Notebook, or Jupyter Lab) and will directly display the expected outage curve images.

The code **only supports execution on Windows platforms** using Python 3.8, Python 3.11, or Python 3.12. It is recommended to install the required third-party libraries in a dedicated virtual environment.  

**Example setup:**  
```bash
conda create -n SMC_python311 python=3.11  
activate SMC_python311  
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```
