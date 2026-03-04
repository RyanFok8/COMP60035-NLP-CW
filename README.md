
# COMP60035 NLP Coursework  
**Patronising and Condescending Language (PCL) Detection**

This project tackles **binary classification of patronising and condescending language (PCL)** using the **Don't Patronize Me! dataset**. The goal is to build a model that can detect whether a paragraph contains patronising language towards vulnerable communities.

---

# Setup

Install the required Python dependencies:

```bash
pip install -r requirements.txt

## Project Structure

```
├── dontpatronizeme_pcl.tsv
├── README.md
├── requirements.txt
│
├── BestModel/
│   ├── best_model.ipynb
│   └── output/
│       ├── run_summary.json
│       ├── dev.csv
│       ├── test.csv
│       └── checkpoints/
│           ├── roberta_focal_seed42.pt
│           ├── roberta_focal_seed52.pt
│           └── roberta_focal_seed62.pt
│
├── train/
│   ├── train_semeval_parids-labels.csv
│   └── dev_semeval_parids-labels.csv
│
└── test/
    └── task4_test.tsv
```