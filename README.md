# Lightly (lightly-ai)

Lightly is a data-curation and active-learning platform for computer vision. The LightlyOne platform exposes a REST API at https://api.lightly.ai for managing datasets, samples, embeddings, cloud datasources, selection / active-learning runs (the LightlyOne Worker), tags, and jobs. Lightly also maintains the open-source lightly self-supervised learning SDK, plus LightlyTrain and LightlyEdge products.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lightly-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lightly-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Computer Vision
- Data Curation
- Active Learning
- Embeddings

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Lightly Datasets API

Create, list, update, and delete LightlyOne datasets (image, video, crop, and embedding dataset types), look datasets up by name, query child datasets, and register dataset uploads on the LightlyOne platform.

- **Human URL:** [https://docs.lightly.ai/docs](https://docs.lightly.ai/docs)
- **Base URL:** `https://api.lightly.ai/v1`

#### Tags

- Datasets
- Computer Vision
- Data Curation

#### Properties

- [Documentation](https://docs.lightly.ai/docs)
- [API Reference](https://docs.lightly.ai/lightly.api.html)
- [OpenAPI](openapi/lightly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/lightly-ai/lightly)

### Lightly Samples and Embeddings API

Manage samples within a dataset (create, list, read, update) with signed read / write URLs, and manage embeddings — list, delete, request signed CSV read / write URLs, mark embeddings processed, and trigger 2D embedding projection jobs.

- **Human URL:** [https://docs.lightly.ai/docs/embeddings](https://docs.lightly.ai/docs/embeddings)
- **Base URL:** `https://api.lightly.ai/v1`

#### Tags

- Samples
- Embeddings
- Vectors

#### Properties

- [Documentation](https://docs.lightly.ai/docs/embeddings)
- [API Reference](https://docs.lightly.ai/lightly.api.html)
- [OpenAPI](openapi/lightly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/lightly-ai/lightly)

### Lightly Datasources API

Configure and inspect the cloud datasource backing a dataset (S3, GCS, Azure, or local), list raw data, metadata, and prediction files in the datasource, and track the processed-until timestamp for incremental ingestion.

- **Human URL:** [https://docs.lightly.ai/docs/set-up-your-first-dataset](https://docs.lightly.ai/docs/set-up-your-first-dataset)
- **Base URL:** `https://api.lightly.ai/v1`

#### Tags

- Datasources
- Cloud Storage
- S3

#### Properties

- [Documentation](https://docs.lightly.ai/docs/set-up-your-first-dataset)
- [API Reference](https://docs.lightly.ai/lightly.api.html)
- [OpenAPI](openapi/lightly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/lightly-ai/lightly)

### Lightly Selection and Active Learning API

Register LightlyOne Workers and schedule compute-worker runs that execute a selection / active-learning configuration over a dataset, producing curated subsets via embeddings, metadata, and model predictions, plus run artifacts and logs.

- **Human URL:** [https://docs.lightly.ai/docs/customize-a-selection](https://docs.lightly.ai/docs/customize-a-selection)
- **Base URL:** `https://api.lightly.ai/v1`

#### Tags

- Selection
- Active Learning
- Worker

#### Properties

- [Documentation](https://docs.lightly.ai/docs/customize-a-selection)
- [API Reference](https://docs.lightly.ai/lightly.api.html)
- [OpenAPI](openapi/lightly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/lightly-ai/lightly)

### Lightly Jobs and Tags API

Poll asynchronous platform jobs by id, and manage dataset tags — create initial and named tags, delete tags, and export tagged subsets to ZIP, filename lists, Label Studio, Labelbox, and Sama label-task formats.

- **Human URL:** [https://docs.lightly.ai/docs](https://docs.lightly.ai/docs)
- **Base URL:** `https://api.lightly.ai/v1`

#### Tags

- Jobs
- Tags
- Export

#### Properties

- [Documentation](https://docs.lightly.ai/docs)
- [API Reference](https://docs.lightly.ai/lightly.api.html)
- [OpenAPI](openapi/lightly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/lightly-ai/lightly)

### Lightly Self-Supervised Learning SDK (OSS)

The open-source (Apache-2.0) lightly Python library for self-supervised representation learning on images (SimCLR, MoCo, DINO, BYOL, and more). It is a pip-installable PyTorch SDK and is distinct from the hosted LightlyOne platform REST API; the same package also ships the ApiWorkflowClient used to call the platform.

- **Human URL:** [https://docs.lightly.ai/self-supervised-learning/](https://docs.lightly.ai/self-supervised-learning/)
- **Base URL:** `https://github.com/lightly-ai/lightly`

#### Tags

- SDK
- Open Source
- Self-Supervised Learning

#### Properties

- [Documentation](https://docs.lightly.ai/self-supervised-learning/)
- [GitHub](https://github.com/lightly-ai/lightly)

## Common Properties

- [GitHub Organization](https://github.com/lightly-ai)
- [LinkedIn](https://www.linkedin.com/company/lightly-tech)
- [Website](https://www.lightly.ai)
- [Documentation](https://docs.lightly.ai/)
- [Plans](plans/lightly-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/lightly-ai-rate-limits.yml)
- [Fin Ops](finops/lightly-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
