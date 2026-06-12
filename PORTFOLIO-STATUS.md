# Portfolio Status

Live CI and release status for the six flagship public repositories.

| Repository | CI | Release | Target version |
|---|---|---|---|
| [Learn AI Evaluation](https://github.com/nad-58/learn-ai-evaluation) | [![CI](https://github.com/nad-58/learn-ai-evaluation/actions/workflows/python-checks.yml/badge.svg)](https://github.com/nad-58/learn-ai-evaluation/actions/workflows/python-checks.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/learn-ai-evaluation?display_name=tag&sort=semver)](https://github.com/nad-58/learn-ai-evaluation/releases) | `v1.1.0` |
| [AI Model Validation Framework](https://github.com/nad-58/ai-model-validation-framework) | [![CI](https://github.com/nad-58/ai-model-validation-framework/actions/workflows/python-checks.yml/badge.svg)](https://github.com/nad-58/ai-model-validation-framework/actions/workflows/python-checks.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/ai-model-validation-framework?display_name=tag&sort=semver)](https://github.com/nad-58/ai-model-validation-framework/releases) | `v0.1.0` |
| [AI Architecture Stack](https://github.com/nad-58/ai-architecture-stack) | [![Docs](https://github.com/nad-58/ai-architecture-stack/actions/workflows/docs-checks.yml/badge.svg)](https://github.com/nad-58/ai-architecture-stack/actions/workflows/docs-checks.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/ai-architecture-stack?display_name=tag&sort=semver)](https://github.com/nad-58/ai-architecture-stack/releases) | `v0.1.0` |
| [Edge AI Computer Vision Deployment](https://github.com/nad-58/edge-ai-computer-vision-deployment) | [![CI](https://github.com/nad-58/edge-ai-computer-vision-deployment/actions/workflows/python-checks.yml/badge.svg)](https://github.com/nad-58/edge-ai-computer-vision-deployment/actions/workflows/python-checks.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/edge-ai-computer-vision-deployment?display_name=tag&sort=semver)](https://github.com/nad-58/edge-ai-computer-vision-deployment/releases) | `v0.1.0` |
| [LLM RAG Evaluation Governance](https://github.com/nad-58/llm-rag-evaluation-governance) | [![CI](https://github.com/nad-58/llm-rag-evaluation-governance/actions/workflows/python-checks.yml/badge.svg)](https://github.com/nad-58/llm-rag-evaluation-governance/actions/workflows/python-checks.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/llm-rag-evaluation-governance?display_name=tag&sort=semver)](https://github.com/nad-58/llm-rag-evaluation-governance/releases) | `v0.1.0` |
| [AI Computational Methods](https://github.com/nad-58/ai-computational-methods) | [![CI](https://github.com/nad-58/ai-computational-methods/actions/workflows/python-checks.yml/badge.svg)](https://github.com/nad-58/ai-computational-methods/actions/workflows/python-checks.yml) [![Numerical](https://github.com/nad-58/ai-computational-methods/actions/workflows/numerical-and-security.yml/badge.svg)](https://github.com/nad-58/ai-computational-methods/actions/workflows/numerical-and-security.yml) | [![Release](https://img.shields.io/github/v/release/nad-58/ai-computational-methods?display_name=tag&sort=semver)](https://github.com/nad-58/ai-computational-methods/releases) | `v0.2.0` |

## Recommended pin order

1. `learn-ai-evaluation`
2. `ai-model-validation-framework`
3. `ai-architecture-stack`
4. `edge-ai-computer-vision-deployment`
5. `llm-rag-evaluation-governance`
6. `ai-computational-methods`

## Release rule

Create a release only after the repository's latest CI workflow is green. Use the prepared release notes in each repository and create the tag from the current `main` branch.
