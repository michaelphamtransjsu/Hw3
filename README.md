# Data Mining Video Series

This project contains six approximately ten-minute walkthroughs covering clustering, automated machine learning, GPU-accelerated data science, and low-code machine learning. Each video focuses on the notebook’s most important code, explains the corresponding results, and discusses why the techniques matter in a real data-mining workflow.

> **Video links:** The videos have not been added to this workspace yet. Replace each **Video URL pending** label below with the final YouTube, Google Drive, or other published video link.

## Video index

| # | Video | Topics | Watch | Presenter script |
|---:|---|---|---|---|
| 1 | K-means: Zero to Hero | Objective function, Lloyd’s algorithm, initialization, choosing K, failure cases, embeddings, and monitoring | **Video URL pending** | [Open script](video-scripts/01-kmeans-zero-to-hero-script.md) |
| 2 | AutoGluon: Capabilities Tour | Classification, regression, quantiles, time series, multimodal learning, embeddings, and foundation models | **Video URL pending** | [Open script](video-scripts/02-autogluon-capabilities-tour-script.md) |
| 3 | AutoGluon: Zero to Hero | Baselines, metrics, thresholds, leakage, calibration, explainability, deployment, and drift | **Video URL pending** | [Open script](video-scripts/03-autogluon-zero-to-hero-script.md) |
| 4 | NVIDIA RAPIDS: Zero to Hero | cuDF, cuML, GPU benchmarking, clustering, XGBoost, SHAP, memory, and CPU–GPU trade-offs | **Video URL pending** | [Open script](video-scripts/04-nvidia-rapids-zero-to-hero-script.md) |
| 5 | PyCaret: Capabilities Tour | Classification, regression, tuning, fraud detection, clustering, anomalies, forecasting, text, and deployment | **Video URL pending** | [Open script](video-scripts/05-pycaret-capabilities-tour-script.md) |
| 6 | PyCaret: Zero to Hero | Preprocessing choices, model comparison, leakage, interpretation, fairness, MLOps, and diagnostics | **Video URL pending** | [Open script](video-scripts/06-pycaret-zero-to-hero-script.md) |

## 1. K-means: Zero to Hero

This video derives the K-means objective, implements Lloyd’s algorithm from scratch, and explains why centroids are arithmetic means. It also covers K-means++ initialization, validation metrics, choosing the number of clusters, common geometric failure cases, high-dimensional embeddings, and production monitoring.

- **Video:** Video URL pending
- **Script:** [01-kmeans-zero-to-hero-script.md](video-scripts/01-kmeans-zero-to-hero-script.md)
- **Notebook:** `1_Copy of final_kmeans_zero_to_hero.ipynb`

## 2. AutoGluon: Capabilities Tour

This video demonstrates the breadth of AutoGluon through binary and multiclass classification, regression, quantile prediction, rare-event detection, time-series forecasting, text and image models, semantic search, tabular foundation models, explainability, and deployment.

- **Video:** Video URL pending
- **Script:** [02-autogluon-capabilities-tour-script.md](video-scripts/02-autogluon-capabilities-tour-script.md)
- **Notebook:** `2_Copy of final_autogluon_capabilities_tour.ipynb`

## 3. AutoGluon: Zero to Hero

This video follows an AutoGluon project from a baseline through model training, metric selection, threshold optimization, calibration, leakage checks, feature importance, deployment, monitoring, and error analysis.

- **Video:** Video URL pending
- **Script:** [03-autogluon-zero-to-hero-script.md](video-scripts/03-autogluon-zero-to-hero-script.md)
- **Notebook:** `3_Copy of final_autogluon_zero_to_hero.ipynb`

## 4. NVIDIA RAPIDS: Zero to Hero

This video explains when GPU acceleration helps data science workloads. It covers cuDF, `cudf.pandas`, cuML, honest CPU–GPU benchmarks, device-resident pipelines, clustering and dimensionality reduction, XGBoost with GPU SHAP, serialization, and drift monitoring.

- **Video:** Video URL pending
- **Script:** [04-nvidia-rapids-zero-to-hero-script.md](video-scripts/04-nvidia-rapids-zero-to-hero-script.md)
- **Notebook:** `4_Copy of final_nvidia_rapids_zero_to_hero.ipynb`

## 5. PyCaret: Capabilities Tour

This video tours PyCaret’s classification, regression, clustering, anomaly-detection, and forecasting modules. It also demonstrates tuning, blending, stacking, threshold optimization, text features, SHAP explanations, saving pipelines, and generating an API.

- **Video:** Video URL pending
- **Script:** [05-pycaret-capabilities-tour-script.md](video-scripts/05-pycaret-capabilities-tour-script.md)
- **Notebook:** `5_Copy of final_pycaret_capabilities_tour (1).ipynb`

## 6. PyCaret: Zero to Hero

This video presents the complete PyCaret lifecycle while making its hidden decisions visible. It examines preprocessing knobs, train-test splitting, model comparison, regression leakage, SHAP reason codes, fairness, drift, retraining, error analysis, and the final shipping checklist.

- **Video:** Video URL pending
- **Script:** [06-pycaret-zero-to-hero-script.md](video-scripts/06-pycaret-zero-to-hero-script.md)
- **Notebook:** `6_Copy of final_pycaret_zero_to_hero.ipynb`

## Recording notes

- Run every notebook before recording and collapse long installation logs.
- If a rerun produces different timing results, present the values displayed in the current session.
- Treat GPU speed-ups as hardware-specific measurements, not universal constants.
- Keep the held-out test set untouched until the final evaluation.
- Explain code by purpose rather than reading it character by character.

## Download

The complete presenter-script package is available as [data-mining-video-scripts.zip](data-mining-video-scripts.zip).

