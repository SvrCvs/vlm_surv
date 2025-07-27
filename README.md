# VESSI - VLM-Enhanced Support for Surveillance and Investigations

This repository contains the official implementation and evaluation materials for the paper:

> **VESSI - VLM-Enhanced Support for Surveillance and Investigations**  
> Submitted to *Forensic Science International: Digital Investigation*.

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

## Dataset Access

Due to GitHub's file size limits, our own CSV files are hosted externally and available upon request:

- [`dataset.csv`]('https://github.com/Xuange923/Surveillance-Video-Understanding?tab=readme-ov-file')
- [`dataset_results.csv`]

These are referenced by the model evaluation and metric computation notebooks.

---

## Citation

```bibtex
@article{veritas2025,
  title     = {VESSI - VLM-Enhanced Support for Surveillance and Investigations},
  author    = {Saverio Cavasin, Pietro Tedeschi, Alessandro Brighente, Simone Milani, Mauro Conti},
  journal   = {Forensic Science International: Digital Investigation (submitted)},
  year      = {2025}
}
```

---

## Contact

For questions or collaborations, please get in touch via email to: saverio.cavasin@phd.unipd.it
