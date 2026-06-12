---
title: "Multimodal Research Agent & Evaluation Platform"
excerpt: "An end-to-end RAG system for radar and computer vision literature — papers, tables, and figures — with agentic retrieval workflows and a rigorous evaluation harness for retrieval quality, faithfulness, and citation correctness."
collection: portfolio
permalink: /portfolio/multimodal-research-agent/
---

A personal research tool that ingests scientific PDFs across radar and computer vision literature and makes them genuinely searchable — not just the text, but the **tables and figures** too.

**What it does**

* Processes scientific PDFs with Nemotron Parse, preserving document structure across text, tables, and figures
* Indexes content with embedding models and vector search, with reranking for precision
* Runs agentic workflows for evidence gathering, cross-paper comparison, and grounded summaries
* Evaluates itself: retrieval quality, faithfulness, citation correctness, and end-to-end task success are all measured, not assumed

**Stack:** Python, embedding models, vector search, rerankers, LLM agentic workflows, Nemotron Parse
