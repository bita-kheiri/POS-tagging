POS Tagging Domain Robustness
R code and results for evaluating UDPipe's pretrained english-ewt model on formal (UD_English-EWT test split) vs. informal (Tweebank v2 test split) text, as part of a research poster examination (Trends in Natural Language Processing (1. Parallelgruppe), Universität Trier).
Contents
udpipe_project.Rmd — full analysis code (tagging, accuracy, per-tag precision/recall/F1, confusion matrices, manual error sampling)
*.conllu — gold-standard test splits used
per_tag_results_*.csv, confusion_matrix_*.csv — computed results
tweet_error_sample_for_manual_review-new.csv — 30 manually categorized tagging errors
*.png — result visualizations
Data sources
UD_English-EWT: https://github.com/UniversalDependencies/UD_English-EWT
Tweebank v2: https://github.com/Oneplus/Tweebank
