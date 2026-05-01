# Pierre Emery

Hi I am a data science student at the University of Montreal.

---

## Projects

- **Glacier Segmentation from Satellite Imagery**  
  End-to-end supervised segmentation pipeline for alpine glaciers using
  multispectral satellite imagery. Built a quality-aware data pipeline
  (cloud/shadow scoring on Sentinel-2 SCL, median compositing, GLIMS
  outline rasterization), trained a U-Net with Attention Gates on
  Caucasus glaciers, and evaluated cross-region generalization on the
  Alps and Andes. Reached 0.83 IoU, outperforming a 5× larger
  ImageNet-pretrained DeepLabV3+ baseline.  
  → [Repository](https://github.com/pierre-emery/projet_glacier)

- **Montréal Road Collisions — Clustering & Classification**  
  End-to-end data science pipeline on 218k road collisions from the City
  of Montréal open dataset (2012–2021). Built data cleaning with 
  conditional imputation applied post train/val/test split to prevent 
  leakage, compared two clustering algorithms (K-means, DBSCAN) on 
  PCA-reduced features, and benchmarked supervised classifiers (SVM, 
  Random Forest, Decision Tree) under three class imbalance strategies 
  (baseline, class weighting, SMOTE). Final evaluation on a held-out 
  test set, with focus on the accuracy/recall trade-off for the 
  minority class (<1% of observations).  
  → [Repository](https://github.com/pierre-emery/classification_accidents)

- **NHL Hockey Analytics — Expected Goals (xG)**
  This project was a project meant for graduate students in the IFT6758 course. A friend of mine and myself decided to tackle it as a personal project and it is still in progress. For now we built a play-by-play data pipeline, engineered shot/context features (distance,   angle, game state), trained and evaluated models (logistic regression, XGBoost), and produced visualizations (interactive shot maps, ROC/calibration). 
  → Code: [Project Repository](https://github.com/Stephanope/Project-Hockey) | Results/Blog: [Blog/Results Repository](https://github.com/Stephanope/Blogpost-Hockey)

- **Introduction to Machine Learning – EPFL (CS-233)**  
  Classification on a tabular (heart disease) dataset (k-NN, logistic regression, k-means from scratch) and deep learning on medical images (DermaMNIST dataset) (MLP/CNN with PyTorch).  
  → [Repository](https://github.com/pierre-emery/introduction_ML)

- **Bioinformatics – Sequence Overlap & Assembly (IFT3295)**  
  Implemented dynamic-programming–based overlap alignment between DNA reads, built an overlap graph and reconstructed a longer genomic sequence from short reads.  
  → [Repository](https://github.com/pierre-emery/bioinfo-sequence-assembly)

- **Bioinformatics – Local Alignment (PLAST-like BLASTN) (IFT3295)**  
  Implemented a simplified BLASTN-style local alignment tool (PLAST): seed-and-extend search with contiguous/spaced seeds, greedy HSP extension, and bitscore / E-value filtering for significant hits.  
  → [Repository](https://github.com/pierre-emery/bioinfo_plast)

---

## 🎓 Academic background

- B.Sc. in Computer Science and Mathematics – Data Science option, Université de Montréal (2023–2026)
- Exchange semester at EPFL (Spring 2025) 

---

## Contact

- GitHub: [@pierre-emery](https://github.com/pierre-emery)  
- Email: pierre.emery@umontreal.ca
