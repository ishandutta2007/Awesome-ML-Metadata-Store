# Awesome-ML-Metadata-Store

## Top ML Metadata Store Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Experiment Tracking, Model Registry, Lineage, Artifact Metadata & MLOps Observability*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **ML Metadata Stores**. These systems record experiments, parameters, metrics, artifacts, models, and lineage so teams can reproduce results, compare runs, and govern the ML lifecycle.



**Examples** include MLflow, Weights & Biases, Neptune.ai, Comet ML, ClearML, Kubeflow Metadata, Vertex AI Metadata, SageMaker ML Lineage, Fiddler AI, and Arize Phoenix (the category leaders).



**Open-source emphasis**: Experiment tracking and metadata have strong open options. **MLflow**, **ClearML**, **Arize Phoenix**, **Google ML Metadata**, and related projects provide production-capable self-hosted stores. Commercial platforms still lead in polished collaboration UIs, managed hosting, and advanced LLM/observability features. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[MLflow (Databricks managed & others)](https://mlflow.org/)**  

  Open-source AI engineering platform widely used for experiment tracking, model registry, and evaluation; available as fully managed services (e.g., on Databricks) as well as self-hosted.



- **[Weights & Biases](https://wandb.ai/)**  

  Leading experiment tracking and collaboration platform with strong visualization, sweeps, and growing LLM/Weave observability features.



- **[Neptune.ai](https://neptune.ai/)**  

  Metadata-focused experiment tracking platform known for flexible querying, clean UI, and strong organization of runs and artifacts.



- **[Comet ML](https://www.comet.com/)**  

  Experiment tracking and MLOps platform with collaboration, model registry, and production monitoring capabilities.



- **[ClearML Hosted](https://clear.ml/)**  

  Managed offering of the ClearML stack covering experiment tracking, orchestration, and data/model management.



- **[Kubeflow Metadata / Google ML Metadata integrations](https://www.kubeflow.org/)**  

  Metadata components used within Kubeflow Pipelines (backed by Google’s ML Metadata library) for lineage and artifact tracking.



- **[Vertex AI Metadata](https://cloud.google.com/vertex-ai)**  

  Managed metadata and lineage service inside Google Cloud Vertex AI for tracking artifacts, executions, and pipeline lineage.



- **[Amazon SageMaker ML Lineage Tracking](https://aws.amazon.com/sagemaker/)**  

  Native lineage and metadata capabilities within SageMaker for tracking data, models, and workflow relationships.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  Model performance and explainability platform that stores and surfaces monitoring and metadata insights for production models.



- **[Arize Phoenix (hosted options) & Arize platform](https://arize.com/)**  

  Observability and evaluation platform; Phoenix provides open-source tracing and evaluation with commercial Arize offerings for production scale.



## Open-Source GitHub Projects

- **[MLflow](https://github.com/mlflow/mlflow)**  

  The most widely adopted open-source platform for experiment tracking, model registry, evaluation, and now broader AI engineering (agents/LLMs). Fully self-hostable.



- **[ClearML](https://github.com/allegroai/clearml)**  

  Open-source MLOps suite with experiment tracking, orchestration, data versioning, and model management; strong self-hosted story.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source AI observability and evaluation library for tracing LLM and ML applications, with rich metadata and visualization.



- **[Google ML Metadata (MLMD)](https://github.com/google/ml-metadata)**  

  Library for recording and retrieving metadata associated with ML workflows; powers lineage in TensorFlow Extended (TFX) and Kubeflow Pipelines.



- **[Kubeflow Metadata (legacy & integrations)](https://github.com/kubeflow/metadata)**  

  Historical Kubeflow metadata components (now largely superseded by MLMD integrations) for tracking pipeline artifacts and executions.



- **[Aim](https://github.com/aimhubio/aim)**  

  Open-source, self-hosted experiment tracking tool focused on a fast UI and flexible metadata exploration.



- **[DVC + Studio open components](https://github.com/iterative/dvc)**  

  Data and model versioning with experiment tracking capabilities; pairs well with Git-centric ML workflows.



- **[Sacred + Omniboard](https://github.com/IDSIA/sacred)**  

  Lightweight open-source experiment organization framework with observer and dashboard options.



- **[Polyaxon](https://github.com/polyaxon/polyaxon)**  

  Open-source platform for managing ML experiments, tracking, and orchestration with a strong self-hosted option.



- **[Guild AI](https://github.com/guildai/guildai)**  

  Open-source experiment tracking and run management tool that works with existing scripts without heavy instrumentation.



### Additional Strong Open-Source Options

- Starting with **MLflow** for the broadest ecosystem, model registry, and zero-lock-in self-hosting.

- Choosing **ClearML** when you want tracking plus orchestration in one open stack.

- Using **Arize Phoenix** for LLM/agent tracing and evaluation metadata.

- Combining **ML Metadata (MLMD)** with Kubeflow or TFX for formal lineage graphs.

- Accepting that polished multi-user collaboration, advanced visualizations, managed scaling, and enterprise SSO still favor commercial platforms (Weights & Biases, Neptune, Comet, managed MLflow, etc.).

- Focusing open-source efforts on reproducible experiment records, lineage, and data ownership.



**Frameworks for building custom systems**: Instrument training scripts with MLflow/ClearML/Phoenix → store parameters, metrics, and artifacts → register models → query lineage for audits and debugging → optionally sync selected runs to a commercial UI for collaboration. Suitable for teams that need control over metadata storage and compliance. Many organizations still adopt hosted trackers for speed and team features while keeping the option to self-host.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- ML metadata stores often contain proprietary models, datasets, and business metrics. Self-hosted deployments require proper access control, encryption, and retention policies. This list is not security or compliance advice.



---

**Made for ML engineers, data scientists, and MLOps teams who need reliable experiment and lineage tracking.**

Let's keep ML metadata reproducible, queryable, and as open as practical.
