# Portfolio Maturity Plan

This plan defines the final GitHub profile actions needed to move the portfolio from quality-controlled repositories to a mature, versioned public portfolio.

## Flagship repositories

1. `learn-ai-evaluation`
2. `ai-model-validation-framework`
3. `ai-architecture-stack`
4. `edge-ai-computer-vision-deployment`
5. `llm-rag-evaluation-governance`
6. `ai-computational-methods`

## Release targets

| Repository | Target tag | Release title | Prepared notes |
|---|---|---|---|
| `learn-ai-evaluation` | `v1.1.0` | Automated Benchmarking and Regression Evaluation | `docs/release_notes_1_1_0.md` |
| `ai-model-validation-framework` | `v0.1.0` | Initial Public Validation Framework | `docs/release-notes-v0.1.0.md` |
| `ai-architecture-stack` | `v0.1.0` | Initial AI Architecture Stack | `docs/release-notes-v0.1.0.md` |
| `edge-ai-computer-vision-deployment` | `v0.1.0` | Initial Edge AI Deployment Toolkit | `docs/release-notes-v0.1.0.md` |
| `llm-rag-evaluation-governance` | `v0.1.0` | Initial LLM/RAG Evaluation Toolkit | `docs/release-notes-v0.1.0.md` |
| `ai-computational-methods` | `v0.2.0` | Complete Numerical Examples | `docs/release-notes-v0.2.0.md` |

## Repository topics

### learn-ai-evaluation

```text
ai-evaluation
machine-learning
model-validation
dataset-quality
fairness
robustness
monitoring
llm-evaluation
rag-evaluation
python
```

### ai-model-validation-framework

```text
ai-validation
model-validation
dataset-validation
fairness
robustness
calibration
monitoring
ai-governance
python
```

### ai-architecture-stack

```text
ai-architecture
systems-engineering
layered-architecture
ai-governance
ai-testing
deployment-patterns
risk-management
```

### edge-ai-computer-vision-deployment

```text
edge-ai
computer-vision
embedded-ai
quantization
latency
model-optimization
hardware-aware-ml
python
```

### llm-rag-evaluation-governance

```text
llm
rag
generative-ai
ai-evaluation
groundedness
retrieval
hallucination
ai-governance
python
```

### ai-computational-methods

```text
artificial-intelligence
machine-learning
symbolic-ai
knowledge-graphs
neural-networks
metaheuristics
python
educational
```

## Pin order

1. Learn AI Evaluation
2. AI Model Validation Framework
3. AI Architecture Stack
4. Edge AI Computer Vision Deployment
5. LLM RAG Evaluation Governance
6. AI Computational Methods

## GitHub Project structure

Create a user-level project named:

```text
AI Portfolio Roadmap
```

Recommended views:

- Board by status
- Table by repository
- Roadmap by target release

Recommended fields:

| Field | Values |
|---|---|
| Status | Backlog, Ready, In progress, Review, Done |
| Repository | Six flagship repositories plus ISP and local backlight dimming |
| Priority | Critical, High, Medium, Low |
| Work type | Release, CI, Documentation, Testing, Security, Example, Profile |
| Target version | Version tag or next milestone |

## Release checklist

For each repository:

- [ ] Latest CI is green
- [ ] README is current
- [ ] Changelog/release notes are current
- [ ] Version metadata matches the tag
- [ ] No confidential or restricted material is present
- [ ] Create tag and GitHub release
- [ ] Confirm release badge resolves correctly
- [ ] Add repository topics
- [ ] Link release from portfolio roadmap

## Completion criteria

The portfolio maturity cycle is complete when all six flagship repositories have versioned releases, topics, live badges, and pinned profile visibility, and the user-level project tracks future work.
