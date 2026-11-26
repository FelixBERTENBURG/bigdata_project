# bigdata_project

cat << 'EOF' > README.md
# Framework Big Data Project

## Authors
- BERTENBURG Félix
- NOM2 Prénom2

## Prerequisites
- Onyxia cluster access (S3 MinIO, Jupyter/VSCode, Spark/DuckDB)
- Python 3.10+

## Dataset
- **Name:** [À compléter]
- **URL:** [À compléter]
- **License:** [À compléter]
- **Download date:** [À compléter]
- **Size:** [Entre 1 Mo et 5 Mo]

## Problem statement
[Maximum 3 phrases décrivant la problématique et le résultat attendu.]

## S3 paths
- **Bucket:** `s3://<votre-bucket>/`
- **Raw data:** `s3://<votre-bucket>/raw/`
- **Processed data:** `s3://<votre-bucket>/processed/`

## Procedure for reproduction
1. Upload raw files to S3 (`mc cp ...`)
2. Run processing pipeline (`python src/...`)
3. Verify output in S3 processed path
EOF