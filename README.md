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


Run the main notebook:

python src/Notebook.ipynb


This will train and evaluate RF-QRC with optional denoising on chaotic datasets.

Citation

If you use this repository, please cite:

O. Ahmed, F. Tennie, L. Magri. Optimal training of finitely-sampled quantum reservoir computers for forecasting of chaotic dynamics. Quantum Machine Intelligence (2025).

License
