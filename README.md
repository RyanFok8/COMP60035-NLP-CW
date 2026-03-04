# COMP60035 NLP CW

Install dependencies:
`pip install -r requirements.txt`

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