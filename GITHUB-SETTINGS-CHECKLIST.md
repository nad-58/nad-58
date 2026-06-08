# GitHub Settings Checklist

The following improvements require manual GitHub settings because they cannot be changed through the current repository file connector.

## 1. Remove accidental repository

Repository to review:

```text
nad-58/nad-58-nad-58
```

If it is genuinely empty and accidental:

1. Open the repository.
2. Go to **Settings**.
3. Scroll to **Danger Zone**.
4. Select **Delete this repository**.
5. Confirm the repository name.

Do not delete `nad-58/nad-58`; that is the correct profile repository.

## 2. Add repository topics

### Learn AI Evaluation

```text
ai-evaluation
machine-learning
model-validation
dataset-quality
fairness
robustness
monitoring
python
educational
```

### AI Architecture Stack

```text
ai-architecture
systems-engineering
layered-architecture
ai-governance
ai-testing
deployment-patterns
risk-management
```

### AI Computational Methods

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

### Edge AI Computer Vision Deployment

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

### LLM RAG Evaluation Governance

```text
llm
rag
generative-ai
ai-evaluation
groundedness
retrieval
hallucination
ai-governance
```

## 3. Enable Discussions

Recommended for:

- `learn-ai-evaluation`
- `ai-architecture-stack`
- `ai-computational-methods`
- `edge-ai-computer-vision-deployment`
- `llm-rag-evaluation-governance`

Suggested categories:

- Q&A
- Ideas
- Show and tell
- Announcements

## 4. Pin profile repositories

Recommended pinned repositories:

1. `learn-ai-evaluation`
2. `ai-model-validation-framework` when public again
3. `ai-architecture-stack`
4. `edge-ai-computer-vision-deployment`
5. `llm-rag-evaluation-governance`
6. `ai-computational-methods`

## 5. Create GitHub Projects

Recommended project boards:

- **AI Evaluation Roadmap** for `learn-ai-evaluation`
- **Portfolio Quality and Releases** across the main repositories
- **ISP Development Roadmap** for remaining pipeline stages

## 6. Create releases

After CI passes, create initial releases for mature public repositories:

- `learn-ai-evaluation`: `v0.2.0`
- `ai-computational-methods`: `v0.1.0`
- `edge-ai-computer-vision-deployment`: `v0.1.0`
- `llm-rag-evaluation-governance`: `v0.1.0`
- `ai-architecture-stack`: `v0.1.0`

## 7. Verify Actions

Open the **Actions** tab of each Python repository and confirm the most recent workflow run passes. Review and correct any dependency or path issue before adding a CI badge to the README.
