# Willy Arison Andriambolamanana

**Research Assistant, AIMS Rwanda** · MSc in Mathematical Sciences (Distinction)

I work on online and randomized algorithms, competitive analysis, graph exploration, and computational topology. I am applying for PhD positions in theoretical computer science and algorithms.

Kigali, Rwanda · [willy.andriambolamanana@aims.ac.rw](mailto:willy.andriambolamanana@aims.ac.rw) · [CV (PDF)](Willy_Arison_Andriambolamanana_CV.pdf)

---

## Research

### Online Graph Exploration on Weighted Cycles *(manuscript in preparation)*
*With Dr. Jan Hązła, AIMS Rwanda (Sep 2026 – Present)*

We analyze **RandHeavyTest₀.₅**, a randomized algorithm for online exploration of weighted cycles introduced by Baligács, Hązła, and Volk ([arXiv:2607.11203](https://arxiv.org/abs/2607.11203)). Using a stopping time at the first discovery of either of the two heaviest edges together with a supermartingale potential function, we cover both heavy and light cycles and prove an upper bound of **1 + λ₀ ≈ 1.3073** on the competitive ratio (down from **1 + r ≈ 1.3143**, against the **1.2922** lower bound for RandHeavyTest₀.₅), with a strictly smaller bound on light cycles.

### Geletu-Hoffmann Activation Function in Deep Learning *(MSc Thesis)*
*AIMS Rwanda · Advisor: Prof. Abebe Geletu W. Selassie (Apr 2025 – Jun 2025)* · [Code](https://github.com/willy-arison/Machine-learning)

Proved Lipschitz continuity and differentiability of the Geletu-Hoffmann function (GHF), a parametric sigmoidal activation with tunable asymptotes `[m₁, m₂]`, and evaluated it in PyTorch across 5 models (MLP, two CNNs, LSTM, ResNet-20) and 6 datasets against 5 baselines including ReLU and Mish. GHF outperformed all 5 baselines on IMDB text classification and converged faster on the image benchmarks.

---

## Selected Repositories

### Algorithms, Topology & Cryptography
- **[Incremental Algorithm and Gaussian Reduction for Simplicial Complexes](https://github.com/willy-arison/Incremental-Algorithm)** (`Python`, `NumPy`) — Computes Betti numbers `βₖ = rank(Hₖ)` via Gaussian elimination over boundary matrices `∂ₖ : Cₖ → Cₖ₋₁`.
- **[Handwritten Digit Classification with Persistent Homology](https://github.com/willy-arison/Handwritten-Digit-Classification-Using-Topological-Features-and-RandomForestClassifier)** (`Python`, `Giotto-TDA`, `scikit-learn`) — Extracts `H₀` and `H₁` persistence diagrams across filtration scales and trains a Random Forest classifier on topological features.
- **RSA Encryption and Decryption from Scratch** (`Python`) — Key generation, encryption, and decryption using the Extended Euclidean algorithm and Miller–Rabin primality testing.
- **Even-Odd Inversion Counting** (`Python`, `NumPy`) — Divide-and-conquer adaptation of Merge Sort to count `(even, odd)` inversions in `O(n log n)` time.

### Machine Learning & Applied Projects
- **Respiratory Sound Classification** (`Python`, `PyTorch`, `Librosa`) — 1D CNN on MFCC features for wheezing detection (~95% validation accuracy).
- **Made in Rwanda: Cross-Lingual Recommender** (`Python`, `SBERT`, `TF-IDF`, `scikit-learn`) — English/French product recommender from the AIMS Hackathon with fairness constraints for CPU-only deployment.
- **Time Series Forecasting with XGBoost** (`Python`, `XGBoost`, `Pandas`) — Multi-series forecasting with lag features and seasonal encodings.
- **IMDB Sentiment & Animals-90 Classification** (`Python`, `PyTorch`) — Transformer classifier on IMDB (91% test accuracy) and ResNet-50 on Animals-90 (85% validation accuracy).
