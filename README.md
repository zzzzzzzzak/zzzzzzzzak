# Siddiqui Zakir Ali

**Senior Machine Learning Engineer • Multimodal Systems • Numerical Computing**  
📍 Global / Remote • [zak.siddiqui16@gmail.com](mailto:zak.siddiqui16@gmail.com) • [GitHub: @zzzzzzzzak](https://github.com/zzzzzzzzak) • [Live Portfolio](https://zzzzzzzzak.github.io/portfolio/)

---

### Executive Profile

Senior Machine Learning Engineer specializing in **model development, high-throughput inference systems, numerical computing, and multimodal architectures**. Experienced in architecting end-to-end production systems spanning low-precision quantization kernels, frontier LLM agent evaluation harnesses, dual-stream computer vision forensics, and dense video retrieval engines.

```
Core Specializations:
  ├── Deep Learning Systems (Quantization INT4/INT8, PEFT LoRA/QLoRA/(IA)³, Flash Softmax, GPU/CUDA)
  ├── Multimodal & Computer Vision (Dual-Stream 2D FFT Forensics, Video RAG, Temporal Grounding)
  ├── Experimentation & Decision Science (CUPED Variance Reduction, Sequential SPRT, SRM Diagnostics)
  ├── Agent & LLM Evaluation (Statistical Hypothesis Testing, McNemar/Permutation Tests, CI Gates)
  └── Quantitative Modeling & Data Pipelines (Walk-Forward Backtesting, High-Throughput SQLite/Parquet)
```

---

### Featured Flagship Repositories

| Repository | Domain & Architecture | Core Tech Stack | CI Status |
| :--- | :--- | :--- | :---: |
| **[ab-testing-experimentation-platform](https://github.com/zzzzzzzzak/ab-testing-experimentation-platform)** | Enterprise experimentation engine: CUPED variance reduction (41.5% sample savings), Wald's Sequential SPRT (6.3× peeking protection), Chi-square SRM diagnostic forensics, and Streamlit command center. | Python, Statsmodels, SciPy, Streamlit | [![CI](https://github.com/zzzzzzzzak/ab-testing-experimentation-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/ab-testing-experimentation-platform/actions/workflows/ci.yml) |
| **[multimodal-peft-adapter-engine](https://github.com/zzzzzzzzak/multimodal-peft-adapter-engine)** | Modular Parameter-Efficient Fine-Tuning (PEFT): LoRA ($W_0 + \frac{\alpha}{r}BA$), QLoRA (NF4 4-bit NormalFloat + double quantization), (IA)³ activation scaling (<0.15% params), benchmarked VLM backbone. | PyTorch, CUDA, PEFT, Streamlit | [![CI](https://github.com/zzzzzzzzak/multimodal-peft-adapter-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/multimodal-peft-adapter-engine/actions/workflows/ci.yml) |
| **[quant-ops-engine](https://github.com/zzzzzzzzak/quant-ops-engine)** | High-performance inference engine: INT4/INT8 bit-packing (7.47× compression), Flash Online Softmax, Chan-Golub-LeVeque LayerNorm, GradientHealthMonitor hooks. | PyTorch 2.5, CUDA, NumPy | [![CI](https://github.com/zzzzzzzzak/quant-ops-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/quant-ops-engine/actions/workflows/ci.yml) |
| **[spatial-frequency-deepfake-detector](https://github.com/zzzzzzzzak/spatial-frequency-deepfake-detector)** | Dual-stream deepfake forensics: SE-ResNet spatial boundaries + 2D FFT azimuthal power spectrum decay ($1/f^\alpha$), cross-attention gating, Grad-CAM attribution, video EMA. | PyTorch, 2D FFT, OpenCV, Streamlit | [![CI](https://github.com/zzzzzzzzak/spatial-frequency-deepfake-detector/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/spatial-frequency-deepfake-detector/actions/workflows/ci.yml) |
| **[multimodal-temporal-video-rag](https://github.com/zzzzzzzzak/multimodal-temporal-video-rag)** | Dense video retrieval & temporal moment grounding: HSV/motion shot segmentation, contrastive dual-encoders, vector indexing, cross-modal attention re-ranking. | PyTorch, Vector Search, OpenCV, Streamlit | [![CI](https://github.com/zzzzzzzzak/multimodal-temporal-video-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/multimodal-temporal-video-rag/actions/workflows/ci.yml) |
| **[llm-agent-eval-harness](https://github.com/zzzzzzzzak/llm-agent-eval-harness)** | Production LLM & agent evaluation framework: 60-task golden benchmark (code, tool trajectories, QA anti-hallucination), paired permutation & McNemar hypothesis tests, CI regression gate CLI. | Python, SciPy, Pytest, PyYAML | [![CI](https://github.com/zzzzzzzzak/llm-agent-eval-harness/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/llm-agent-eval-harness/actions/workflows/ci.yml) |
| **[equity-forecasting-pipeline](https://github.com/zzzzzzzzak/equity-forecasting-pipeline)** | Quantitative equity pipeline: 120-ticker SQLite/Parquet warehouse, 10-window walk-forward backtest (RMSE + Sharpe ratio), automated 45-second morning briefing digest, Streamlit dashboard. | Python, SQLite, Statsmodels, Parquet, Streamlit | [![CI](https://github.com/zzzzzzzzak/equity-forecasting-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/equity-forecasting-pipeline/actions/workflows/ci.yml) |
| **[customer-churn-retention-analysis](https://github.com/zzzzzzzzak/customer-churn-retention-analysis)** | Cost-sensitive customer churn modeling: 7,043 customer records, cost matrix optimization (\$257k net retained value simulation), calibrated decision thresholding, Streamlit UI. | Python, Scikit-learn, Pandas, Streamlit | [![CI](https://github.com/zzzzzzzzak/customer-churn-retention-analysis/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/customer-churn-retention-analysis/actions/workflows/ci.yml) |
| **[enterprise-sales-bi-analytics](https://github.com/zzzzzzzzak/enterprise-sales-bi-analytics)** | Enterprise BI & Data Warehousing: Normalized Star Schema (40k fact records), SQL CTEs & window functions, Power BI DAX measure catalog, interactive Streamlit executive dashboard. | Python, SQLite, SQL, Power BI DAX, Streamlit | [![CI](https://github.com/zzzzzzzzak/enterprise-sales-bi-analytics/actions/workflows/ci.yml/badge.svg)](https://github.com/zzzzzzzzak/enterprise-sales-bi-analytics/actions/workflows/ci.yml) |

---

### Technical Competency Matrix

```
Machine Learning & Deep Learning:
  • Frameworks: PyTorch 2.x, TorchVision, Hugging Face Transformers, Scikit-learn
  • Parameter-Efficient Fine-Tuning (PEFT): LoRA (Low-Rank Decomposition), QLoRA (NF4 Double Quantization), (IA)³
  • Architecture Design: Vision Transformers, ResNet/CNN, Cross-Attention, Multi-modal Encoders, Dual Streams
  • Numerical Optimization: INT8/INT4 Bit-Packing, Shifted Two-Pass LayerNorm (Chan-Golub-LeVeque), Flash Softmax
  • Explainability: Grad-CAM, 2D FFT Azimuthal Power Spectrum, Cross-Modal Attention Heatmaps

Experimentation, Causal Inference & Decision Science:
  • Variance Reduction: CUPED (Univariate & Multivariate Pre-Experiment Covariates, OLS Residualization)
  • Continuous Monitoring: Wald's Sequential Probability Ratio Test (SPRT), Alpha-Spending Boundaries
  • Quality & Diagnostics: Sample Ratio Mismatch (SRM) Chi-Square Diagnostics, Multi-Dimensional Slicing
  • Hypothesis Testing: Welch's t-test, Mann-Whitney U, Bootstrap 95% CIs, FDR Benjamini-Hochberg

Retrieval, RAG & Vector Systems:
  • Video & Multimodal RAG: Temporal Shot Boundary Segmentation, Keyframe Attention Pooling, Temporal Grounding
  • Dense Retrieval: In-memory Dense Vector Indexing (Cosine / Inner Product), HNSW ANN principles
  • Evaluation: Recall@k, Temporal IoU (tIoU), mAP, Latency p50/p95/p99 Profiling

Evaluation & MLOps Infrastructure:
  • Frontier Agent Evals: Multi-turn Tool Trajectory F1, Sandboxed Code Execution, Anti-Hallucination Grounding
  • Statistical Rigor: Paired Permutation Tests, McNemar Significance Tests, Bootstrap 95% Confidence Intervals
  • CI/CD Automation: GitHub Actions workflows, automated regression gates, reproducible Pytest test suites

Data Engineering & Systems:
  • Languages: Python (Proficient), SQL (Advanced: CTEs, Windowing Functions, Index Optimization)
  • Data Warehousing: SQLite, Apache Parquet, Star Schema Dimensional Modeling
  • Production Dashboards: Streamlit Decision UIs, Power BI DAX Modeling
```

---

### Contact & Collaboration

- **Interactive ML Portfolio**: [zzzzzzzzak.github.io/portfolio](https://zzzzzzzzak.github.io/portfolio/)
- **Photography & Imaging**: [zzzzzzzzak.github.io](https://zzzzzzzzak.github.io/)
- **Email**: [zak.siddiqui16@gmail.com](mailto:zak.siddiqui16@gmail.com)
- **GitHub**: [github.com/zzzzzzzzak](https://github.com/zzzzzzzzak)
- **Role Focus**: Senior ML Engineer • AI Research & Data Lab Contractor
