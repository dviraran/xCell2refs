# xCell 2.0 pre-trained references

| Dataset               | Source        | Normalization | Normalization -SigMat | nSamples | nCellTypes | Method    | DataType     | Tissue | Comments                            |
|-----------------------|---------------|---------------|-----------------------|----------|------------|-----------|--------------|--------|-------------------------------------|
| Immune Cell Compendium| Kassandra     | TPM           | TPM                   | 3626     | 40         | RNA-seq   | Sorted cells | Blood  |                                     |
| TME Cell Compendium   | Kassandra     | TPM           | TPM                   | 8146     | 25         | RNA-seq   | Sorted cells | Tumor  |                                     |
| TS Blood              | Tabula Sapiens| No - counts   | CPM                   | 11921    | 18         | scRNA-seq | scRNA-seq    | Blood  |                                     |
| [BlueprintEncode](/references/BlueprintEncode.xCell2Ref.rds)       | celldex       | TPM           | LogCounts             | 259      | 43         | RNA-seq   | Sorted cells | Mixed  |                                     |
| LM22                  | CIBERSORT     | RMA*          | RMA*                  |          |            | Array     | Sorted cells | Mixed  | * In log-space, raw data for CIBERSORTx |


We invite users to upload their own xCell2 objects to https://github.com/dviraran/ and update this table accordingly.
