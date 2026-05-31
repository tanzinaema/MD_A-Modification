# MD-A-Modification


WP/WIP/
├── CLAUDE.md
├── MD&A(2009-2024)/                     ~118,612 .txt files
├── 1-4_combining_data(2009-24)/
│   ├── Stage 1/                         ✅ dataset_YYYY.json (2009–2024)
│   ├── Stage 2/                         ✅ combined_MD&A(2009-24).json (5.25 GB)
│   ├── Stage 3/                         ✅ metadata_corrected.csv
│   └── Stage 4/                         ✅ metadata_clean.csv + clean_MD&A.jsonl
├── 5_Preprocessing_Scoring_BT_Embed/
│   ├── Stage 5a.1/                      ✅ documents_bt.parquet
│   ├── Stage 5a.2/                      ✅ bt_scores.parquet + tfidf_idf.parquet
│   ├── Stage 5b.1/                      ✅ documents_common.parquet
│   ├── Stage 5b.1a/                     ✅ documents_common_structured.parquet
│   └── Stage 5b.2/                      ✅ tfidf_scores_common.parquet + tfidf_idf_common.parquet
├── 5b3/
│   ├── s1/                              ✅ DONE
│   │   ├── stage5b3_s1_chunk_inventory.py
│   │   ├── section_alignment.parquet    1,096,007 rows
│   │   ├── chunk_inventory.parquet      4,551,790 rows (3.67 GB)
│   │   ├── section_chunk_diagnostics.csv
│   │   ├── stage5b3_s1_summary.txt
│   │   ├── tau_validation.py            ✅ DONE (this session)
│   │   └── tau_validation/              ✅ DONE (this session)
│   │       ├── tau_pairs_prelabel.csv
│   │       ├── tau_validation_pairs.csv
│   │       ├── tau_validation_results.csv
│   │       └── tau_validation_summary.txt
│   ├── s2/                              🔲 PENDING — chunk embeddings (GPU)
│   │   ├── ci/                          context-isolated regime
│   │   │   ├── finbert_embeddings.parquet
│   │   │   ├── mpnet_embeddings.parquet
│   │   │   ├── fine5_embeddings.parquet
│   │   │   └── mistral_embeddings.parquet
│   │   └── ca/                          context-aware regime
│   │       ├── finbert_embeddings.parquet
│   │       ├── mpnet_embeddings.parquet
│   │       ├── fine5_embeddings.parquet
│   │       └── mistral_embeddings.parquet
│   ├── s3/                              🔲 PENDING — informativeness weights (next)
│   │   ├── stage5b3_s3_weights.py
│   │   ├── chunk_weights.parquet
│   │   ├── section_weights.parquet
│   │   └── stage5b3_s3_summary.txt
│   ├── s4/                              🔲 PENDING — symmetric chunk matching
│   └── s5/                              🔲 PENDING — document-level aggregation
├── 6_Financial_data/                    ✅ financial_panel.parquet (102,803 × 40)
├── 7_Regressions_BT_Embed/              ✅ Stage 7a done; 7b PENDING
│   ├── stage7a_bt_regressions.py
│   ├── regression_sample.parquet        21,069 firm-years
│   ├── eq2_results.txt
│   └── eq3_results.txt
└── (root)
    ├── merge_bt_scores_financials.py    ✅
    ├── bt_scores_with_financials.parquet
    └── bt_scores_with_financials.csv
"# MD_A-Modification" 
