---
title: "Self-Summarization Deep Research Agent"
collection: projects
date: 2026-04-01
link: https://github.com/tommyma3/self-summarization-agent
---

[*GitHub Repository*](https://github.com/tommyma3/self-summarization-agent)

- Built a self-summarizing research agent for BrowseComp-Plus that iteratively executes tool calls (e.g. search, retrieve docs) while automatically compacting interaction history to operate within a fixed context window.
- Developed an end-to-end reinforcement learning pipeline with vLLM-based rollout generation, reward-aligned trajectory extraction, and GRPO training using VERL.
- Enabled Qwen3.5-9B to solve long-horizon research tasks with context compaction, achieving a **2× improvement in accuracy** on BrowseComp-Plus.
