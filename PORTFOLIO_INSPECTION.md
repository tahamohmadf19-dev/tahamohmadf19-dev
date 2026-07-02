# GitHub Portfolio Inspection and Execution Notes

This file records the current portfolio polish state and the next execution priorities.

## Current status

- Profile README was updated from student-style wording into early-career AI and Data Science positioning.
- Priority projects now appear in the profile README.
- The main portfolio still depends on repository-level cleanup, especially README quality, reproducibility, and risk reduction.

## Priority repositories

1. rag-document-search
2. AI-Agent-Router
3. bank-marketing-classification
4. customer-segmentation-kmeans
5. movie-review-sentiment-analysis-bilstm
6. vehicle-co2-emissions-prediction

## Repository classification

| Repository | Action | Reason |
| --- | --- | --- |
| rag-document-search | Pin and improve | Strongest LLM/RAG signal; needs architecture, API examples, and limitations |
| AI-Agent-Router | Pin and improve | Strong LangGraph signal; needs safer wording and setup clarity |
| bank-marketing-classification | Pin and improve | Good PySpark ML signal; needs dependency file consistency and verified metric wording |
| customer-segmentation-kmeans | Pin after cleanup | Good DS/business analytics signal; README formatting needs cleanup |
| movie-review-sentiment-analysis-bilstm | Pin after cleanup | Good NLP signal; README has a placeholder clone URL to fix |
| vehicle-co2-emissions-prediction | Pin and improve | Good regression/feature-engineering signal; needs dependency file consistency |
| Cypher-Rat-v5 | Recommend private/archive | Unrelated to AI/Data Science and may weaken recruiter trust |

## Manual GitHub profile actions

- Update GitHub bio to: AI and Data Science practitioner focused on ML pipelines, NLP, LLM/RAG systems, LangGraph agents, PySpark, FastAPI, and production-oriented AI projects.
- Reorder pinned repositories in the priority order listed above.
- Add relevant topics to each repository only when the technology is actually used.

## Repository quality standard

Each priority repository should include:

- Problem statement
- Solution overview
- Tech stack
- Dataset/source notes
- Methodology
- Verified results or clearly marked placeholders
- How to run locally
- Screenshots or demo placeholders
- Limitations
- Future improvements
- License

## Unsupported claims to avoid

- Senior-level positioning
- Production readiness without deployment, tests, and packaging evidence
- Docker support without a working Dockerfile
- CI/CD without workflow files
- Metrics that cannot be verified from notebooks or code
- Deployment claims without a live demo or deployment documentation
