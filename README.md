# MD-A-Modification

```text
WP/WIP/
|-- CLAUDE.md
|-- MD&A(2009-2024)/                     ~118,612 .txt files
|-- 1-4_combining_data(2009-24)/
|   |-- Stage 1/                         DONE dataset_YYYY.json (2009-2024)
|   |-- Stage 2/                         DONE combined_MD&A(2009-24).json (5.25 GB)
|   |-- Stage 3/                         DONE metadata_corrected.csv
|   `-- Stage 4/                         DONE metadata_clean.csv + clean_MD&A.jsonl
|-- 5_Preprocessing_Scoring_BT_Embed/
|   |-- Stage 5a.1/                      DONE documents_bt.parquet
|   |-- Stage 5a.2/                      DONE bt_scores.parquet + tfidf_idf.parquet
|   |-- Stage 5b.1/                      DONE documents_common.parquet
|   |-- Stage 5b.1a/                     DONE documents_common_structured.parquet
|   `-- Stage 5b.2/                      DONE tfidf_scores_common.parquet + tfidf_idf_common.parquet
|-- 5b3/
|   |-- s1/                              DONE
|   |-- s2/                              PENDING - chunk embeddings (GPU)
|   |-- s3/                              PENDING - informativeness weights
|   |-- s4/                              PENDING - symmetric chunk matching
|   `-- s5/                              PENDING - document-level aggregation
|-- 6_Financial_data/                    DONE financial_panel.parquet (102,803 x 40)
|-- 7_Regressions_BT_Embed/              DONE Stage 7a; 7b PENDING
`-- root/
    |-- merge_bt_scores_financials.py    DONE
    |-- bt_scores_with_financials.parquet
    `-- bt_scores_with_financials.csv
```