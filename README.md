# DSPy With Knowledge Graphs

Notebook and video companion for exploring how [DSPy](https://github.com/stanfordnlp/dspy) pipelines can be combined with knowledge-graph context.

Watch the walkthrough: [DSPy with Knowledge Graphs](https://www.youtube.com/watch?v=mHREErgLmi0)

## Project Question

DSPy can optimize language-model pipelines without hand-tuning every prompt. Knowledge graphs can add structured context and explicit relationships. This project asks:

> Does adding knowledge-graph context make a DSPy RAG pipeline more useful than a vanilla DSPy RAG baseline?

The notebook compares a standard DSPy retrieval pipeline with a custom DSPy + knowledge-graph pipeline, using a concrete knowledge source so the tradeoffs are visible.

## What This Demonstrates

- How to structure a DSPy experiment around a retrieval task.
- How knowledge-graph context can be introduced into an LLM pipeline.
- Why evaluation matters even when the architecture sounds obviously better.
- How to explain emerging AI frameworks through a runnable notebook rather than slides alone.

## Files

- `dspy_with_kg.ipynb` - main exploratory notebook.
- `README.md` - project overview and video link.

## How To Use

Open the notebook and run it top to bottom:

```bash
jupyter notebook dspy_with_kg.ipynb
```

The notebook starts from environment setup, then uses Elon Musk's Wikipedia page as the working knowledge source.

## Portfolio Note

This repo is part of a larger set of AI education projects focused on RAG, knowledge graphs, retrieval evaluation, and code-backed explanations of model behavior.
