# H-ACI: Hierarchical Adaptive Conformal Inference for Medical Wearables

Implementation of **Hierarchical Adaptive Conformal Inference (H-ACI)** for reliable uncertainty quantification in streaming ECG data.

## Paper

"Hierarchical Adaptive Conformal Inference for Reliable Uncertainty Quantification in Edge-Deployable Medical Wearables"  
*Submitted to Device (Cell Press)*

## Key Features

- **Multi-scale adaptation**: Parallel conformal predictors at different timescales (K=3)
- **Coverage guarantees**: 91.1% coverage with 1.23 average set size on MIT-BIH
- **Few-shot personalization**: Deploy with only 5 calibration samples
- **Edge-deployable**: <3 KB memory, 1.87 ms latency

## Usage

Open notebook in Google Colab and run cells sequentially. Datasets download automatically from PhysioNet.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oussamaElallam/H-ACI-Medical-Wearables/blob/main/H_ACI_Medical.ipynb)

## Experiments

| Table | Description |
|-------|-------------|
| 1 | MIT-BIH main results |
| 6 | Few-shot personalization (5-50 samples) |
| 7 | Cross-dataset transfer (PTB-XL → Chapman) |
| 8 | UQ timing comparison |

## Datasets

- [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)
- [PTB-XL](https://physionet.org/content/ptb-xl/1.0.3/)
- [Chapman-Shaoxing](https://physionet.org/content/ecg-arrhythmia/1.0.0/)

## License

MIT
