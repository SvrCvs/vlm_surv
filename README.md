# VERITAS: A VLM-Based Forensic Framework for Surveillance Video Analysis

This repository contains the official implementation and evaluation materials for the paper:

> **VERITAS – A Vision-Language Based Forensic Framework for Surveillance Videos**  
> Submitted to *IEEE Transactions on Information Forensics and Security (TIFS)*.

---

## Project Structure

```
notebooks/
├── 0_dataset/     # Dataset preparation and prompt tiering
├── 1_models/      # Evaluation notebooks per VLM (Qwen, LLaVA, InstructBLIP, DeepSeek)
├── 2_metrics/     # CMUS score computation
└── 3_analysis/    # Performance visualizations and aggregation
```

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/SvrCvs/vlm_surv.git
cd vlm_surv
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run a model evaluation notebook:

```bash
jupyter notebook notebooks/1_models/tot_qwen.ipynb
```

---

## 📊 CMUS Metric

The **Composite Model Utility Score (CMUS)** balances:
- Semantic Accuracy
- Hallucination Avoidance
- Inference Efficiency

It is computed in [`notebooks/2_metrics/metrics.ipynb`](notebooks/2_metrics/metrics.ipynb), and visualized in [`notebooks/3_analysis/`](notebooks/3_analysis/).

---

## 📁 Dataset Access

Due to GitHub's file size limits, CSV files are hosted externally and available upon request:

- [`dataset.csv`](https://your-link-here)
- [`dataset_results.csv`]

These are referenced by the model evaluation and metric computation notebooks.

---

## Citation

```bibtex
@article{veritas2025,
  title     = {VERITAS: A VLM-Based Forensic Framework for Surveillance Videos},
  author    = {Author Name and Collaborators},
  journal   = {EURASIP J. Adv. Signal Process. (submitted)},
  year      = {2025}
}
```

---

## 📬 Contact

For questions or collaborations, please get in touch via email to: saverio.cavasin@phd.unipd.it
