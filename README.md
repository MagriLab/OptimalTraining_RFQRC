# OptimalTraining_RFQRC
Implementation of recurrence-free quantum reservoir computing (RF-QRC) with denoising methods for optimal training under finite sampling.

## Repository Structure
- `src/Notebook.ipynb` – Main workflow notebook: training and prediction with RF-QRC, QRC, and classical reservoirs.  
- `src/QRC/rfqrc.py` – Recurrence-free quantum reservoir implementation (Qiskit).  
- `src/QRC/qrc.py` – Standard quantum reservoir implementation.  
- `src/QRC/crc.py` – Classical reservoir computing / Echo State Network implementation.  
- `src/QRC/denoise.py` – Denoising routines (SVD truncation, filtering).  
- `src/QRC/systems.py` – Dynamical systems definitions (e.g., Lorenz63, Lorenz96).  
- `src/QRC/validation.py` – Hyperparameter search and recycle validation routines.  

## Usage
Install dependencies:
```bash
pip install -r requirements.txt

```
Then run the following notebook
```bash

python Notebook.ipynb
```


## Citation
If you use this code in your research, please cite the corresponding paper:

Robust quantum reservoir computers for forecasting chaotic dynamics: generalized synchronization and stability (https://arxiv.org/abs/2506.22335)
