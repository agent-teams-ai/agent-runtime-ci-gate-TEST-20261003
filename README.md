# Disposable CI gate TEST

Two bounded GitHub Actions refusal trials use exact copies of the Agent Runtime aggregate policy from commit 34e76bdddd53fc37d68c55f2e585a0d4b151d754. The tested gate must stay red when a required lane fails or is skipped. Synthetic jobs do not execute runtime, providers, agents or user projects.

The verification job confirms the refusal, so the overall workflow is intentionally failed. Source files were covered by the original pinned strict TypeScript check. This repository is TEST-only evidence, not a product or release.
