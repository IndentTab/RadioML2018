# Collaborative Multi-task Deep Learning for 6G Spectrum Sensing
#### 6G Wireless | Collaborative Learning | Spectrum Sensing

## Abstract
In next-generation cognitive radio (CR) and 6G networks, intelligent spectrum sensing is required for efficient wideband spectrum access. This project explores a collaborative learning approach using multi-task CNNs to enable distributed spectrum sensing under partial observation scenarios. Models are trained locally on synthetic and real modulation datasets and aggregated using shared weight fusion and per-task head averaging. Interference effects are studied by adding new devices with unseen spectrum classes.

## Project Structure
```bash
├── data/                         # Input data (RadioML, synthetic .pth files)
│   ├── GOLD_XYZ_OSC.0001_1024.hdf5
│   ├── RefinedNewData/SNRs/...   # Generated synthetic datasets
├── notebooks/
│   ├── baseline_model.ipynb      # Initial RadioML multi-task CNN
│   ├── synthetic_generator.ipynb # Dataset generation per paper's cases
├── README.md
└── requirements.txt
```
### Project is a WIP
### README is a WIP
