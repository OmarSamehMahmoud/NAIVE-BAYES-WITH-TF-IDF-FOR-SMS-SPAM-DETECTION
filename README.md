# SMS Spam Detection - Naive Bayes with TF-IDF
## Reference Paper
"Leveraging Large Language Models for Cybersecurity: Enhancing SMS Spam Detection" (2025)
arXiv: https://arxiv.org/abs/2502.11014

## Execution
pip install -r requirements.txt
Run notebook cells sequentially. Fully CPU-compatible.

## Reproducibility
- Random seed: 42
- Stratified 80/20 train/test split
- TF-IDF: max_features=3000, sublinear_tf=True
- Multinomial NB: alpha=1.0 (Laplace smoothing)
- Class imbalance handled via stratified sampling and balanced weights in baselines
