# Willy Arison ANDRIAMBOLAMANANA

**MSc in Mathematical Sciences (Distinction) | AIMS Rwanda**
Aspiring researcher in Deep Learning, Topological Data Analysis, and Optimization.
Seeking PhD opportunities starting Fall 2026.

**Location:** Antananarivo, Madagascar  
**Email:** willy.andriambolamanana@aims.ac.rw  
**GitHub:** [github.com/willy-arison](https://github.com/willy-arison)

---

## Research Interests

Deep Learning · Activation Functions · Topological Data Analysis ·
Signal Processing · Time Series Forecasting · Mathematical Optimization ·
Stochastic Processes · Machine Learning for Health

---

## Education

### MSc in Mathematical Sciences
**African Institute for Mathematical Sciences (AIMS), Rwanda** | Sep 2024 -- Jun 2025

- **Thesis:** Implementation and Evaluation of the Geletu-Hoffmann Function as an Activation Function in Deep Learning
- **Supervisor:** Prof. Abebe Geletu W. Selassie, German Research Chair, AIMS Rwanda
- **Co-supervisor:** Dr. Roger Fidele Ranomenjanahary, AIMS Rwanda
- **Honors:** Distinction (GPA: 4.88 / 5.0)
- **Relevant coursework:** Algorithms and Data Structures, Statistical Machine Learning, Introduction to Deep Learning, Introduction to Probability and Statistics, Data-Driven Optimization, Stochastic Processes

### BSc in Applied Mathematics
**University of Antananarivo, Madagascar** | 2019 -- 2022

- **Relevant coursework:** Optimization and Numerical Analysis, Probability, Statistics, Differential Equations

---

## Thesis

**Title:** *Implementation and Evaluation of the Geletu-Hoffmann Function as an Activation Function in Deep Learning*

Proposed a novel parametric activation function, the **Geletu-Hoffmann Function (GHF)**. It belongs to the sigmoidal (S-shaped) category, is monotonic, smooth, and continuously differentiable with adjustable output range parameters.

**Experiments conducted on 6 benchmark datasets:**
- MNIST, Fashion MNIST, SVHN, CIFAR-10, CIFAR-100 (image classification)
- IMDB Reviews (text classification / sentiment analysis)

**Architectures tested:** MLP, CNN, LSTM, ResNet  
**Compared against:** Sigmoid, Tanh, ReLU, Leaky ReLU, Mish

GHF outperformed all competing functions on text classification (LSTM + IMDB), achieved lower training/validation losses on simple CNN and MLP architectures, and demonstrated fast convergence reaching high accuracy within few epochs.

**Future work:** Test on YOLO and Transformers, automate GHF parameter tuning during training, evaluate with AdamW/RMSprop, and study theoretical behavior.

---

## Projects

### Activation Function Research (Thesis)
**Technologies:** Python, PyTorch, PyTorch Lightning, Jupyter Notebook

I implemented the experimental pipeline for the **Geletu-Hoffmann Function GHF(x) = τ(x; τ, m₁, m₂)** — a parametric sigmoidal activation with tunable output range [m₁, m₂]. Unlike ReLU (non-smooth at 0) or tanh (fixed [-1, 1]), GHF's adjustable asymptotes enable adaptive gradient scaling per layer. I tested across 6 datasets, 4 architectures (MLP, CNN, LSTM, ResNet), and 5 competing activations — gaining hands-on experience designing novel contributions and systematic benchmarking.

### Handwritten Digit Classification Using Topological Features
**Technologies:** Python, scikit-learn, Giotto-TDA, Matplotlib

I classified MNIST digits using **persistent homology** instead of raw pixels. I transformed images into persistence diagrams encoding **(birth, death)** of H₀, H₁ homology classes across filtration scales, then trained a Random Forest on the topological feature space. I learned how topological features complement pixel-based methods — bridging pure math and applied ML.

### Incremental Algorithm and Gauss Reduction for Simplicial Complexes
**Technologies:** Python, Jupyter Notebook, Topological Data Analysis

I implemented **Betti number βₖ = rank(Hₖ)** computation using the boundary operator **∂ₖ: Cₖ → Cₖ₋₁** with **∂∘∂ = 0** for persistent homology. I gained practical experience in computational algebraic topology, directly supporting my TDA research interests.

### Signal Classification — Respiratory Sound Dataset
**Technologies:** Python, Librosa, PyTorch, 1D CNN, MFCC

I developed a 1D CNN for asthma-relevant wheezing detection from respiratory audio. I extracted **MFCC features via STFT → Mel-scale filterbank → DCT**, then applied 1D convolutions for sequential feature extraction. Achieved **~95% validation accuracy**. I learned how spectral signal processing and convolutional feature extraction combine for medical ML research.

### Time Series Forecasting with XGBoost
**Technologies:** Python, XGBoost, Pandas, Jupyter Notebook

I built gradient-boosted regression trees minimizing **L = Σᵢ l(yᵢ, ŷᵢ) + Σₖ Ω(fₖ)**, with lag features, seasonal encoding, and multi-ID cross-series learning. This taught me additive ensemble methods and multi-step forecasting — transferable to quantitative finance and climate research.

### Image Classification — Animals-90 (Kaggle)
**Technologies:** Python, PyTorch, ResNet-50

I built a ResNet-50 for 90-class classification using **F(x) + x** residual learning, achieving **85% validation accuracy**. I learned how skip-connections mitigate vanishing gradients — essential for designing deep architectures in research.

### Text Classification — IMDB Sentiment Analysis
**Technologies:** Python, PyTorch, Transformers

I built a transformer classifier using **multi-head self-attention (softmax(QKᵀ/√d)V)**, achieving **91% test accuracy**. I gained practical experience with attention mechanisms that power modern NLP and multimodal research.

### Made in Rwanda — Content Recommender (AIMS Hackathon)
**Technologies:** Python, SBERT, TF-IDF, scikit-learn

I built a cross-lingual (English/French) product recommender using **cosine similarity in SBERT embedding space (ℝ³⁸⁴)** with a **TF-IDF (tf·log(N/df))** alternative and algorithmic fairness constraints. I learned to navigate trade-offs between dense and sparse representations under CPU-only, low-bandwidth constraints.

### Cryptography — RSA Encryption/Decryption
**Technologies:** Python, Jupyter Notebook

I implemented RSA from scratch: integer factorization **n = pq**, **e·d ≡ 1 (mod φ(n))**, Extended Euclidean algorithm for Bézout coefficients, and Miller–Rabin probabilistic primality testing. This deepened my understanding of number theory foundations that underpin mathematical ML research.

### Merge Sort — Even-Odd Violation Counting
**Technologies:** Python, NumPy, Jupyter Notebook

I solved **(even, odd) inversion counting** via divide-and-conquer, reducing **O(n²) → O(n log n)**. I learned to adapt classical algorithms for novel combinatorial problems.

### Mars Sol Problem — Martian Calendar
**Technologies:** Python

I modeled Martian time using modular arithmetic with non-standard periodicity: 24-month years, irregular month lengths, custom leap year rules.

---

## Work Experience

### Marketing Data Analysis Intern
**RegardBeauty, Cite Planton Antananarivo, Madagascar** | Jul 2025 -- Dec 2025

- Extracted data from multiple sources
- Cleaned, normalized, aggregated, and merged datasets
- Defined and computed KPIs
- Extracted data-driven insights for business decisions
- Built ML models to estimate missed revenue from out-of-stock events
- Developed ML models to optimize budget allocation per product over future periods
- Performed FSN (Fast, Slow, Non-moving) inventory analysis
- Constructed analytical reports using Google Sheets

---

## Skills

| Category | Skills |
|---|---|
| **Programming** | Python (Matplotlib, scikit-learn, Seaborn, NumPy, SciPy, PyTorch, PyTorch Lightning, Flask, LangChain, Streamlit), R, PostgreSQL, MySQL |
| **Machine Learning / AI** | Deep Learning (CNN, LSTM, ResNet, Transformers), XGBoost, Random Forest, SBERT, TF-IDF, Topological Data Analysis (Giotto-TDA) |
| **Technical** | Project management (Notion), Git/GitHub |
| **Office** | Microsoft Excel, Word, PowerPoint, Google Sheets |
| **Languages** | Malagasy (native), English (B2), French (B2) |

---

## Awards

- **Bank of Kigali Academic Honor Award** — awarded for academic excellence at AIMS Rwanda

---

## Conferences & Workshops

- **A-PIC 25** (Probability, Information Theory, and Combinatorics) — University of Rwanda, November 2025
- **A-PIC 24** (African Summer School for Probability, Information Theory, and Combinatorics) — AIMS Rwanda, August 2024 (Certificate)


