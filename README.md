# Huzaifa Manasawala

**AI Automation Engineer** | LLM applications and agentic RAG | Computer vision | Python backend

I'm a software engineer at Credence Resource Management in Pune. At work I build Python automation and internal platforms that take manual work off people's plates. In my own time I build LLM and computer vision systems.

- My automation at work has reclaimed the equivalent of **4 full-time employees'** daily work.
- I cut a **2-million-account** ETL from **5 hours to 1.5 hours** with load-balanced parallel batching.
- I trained a YOLOv8 character detector on about **8,000 labeled images** to read Indian number plates, then doubled throughput from **4 to 8 FPS**.

## Projects

### [PlateX: Indian Number Plate Recognition](https://github.com/Huzaifa1025/anpr-showcase)

Detects vehicles in video, tracks them with SORT, and reads Indian number plates using a custom YOLOv8 character detector with an EasyOCR fallback. Confidence-weighted consensus combines readings across frames; the app exports annotated video, plate crops, and detection CSVs, and looks up state and district codes.

[Explore the architecture and engineering decisions →](https://github.com/Huzaifa1025/anpr-showcase#engineering-choices)

`PyTorch` `YOLOv8` `OpenCV` `SORT` `Flask`

### [DeltaTracker: AI Stock Research Platform](https://github.com/Huzaifa1025/deltatracker-showcase) (in progress)

A research and portfolio platform for Indian equities, with watchlists, broker imports, rule-based signals and a LangGraph research agent. The agent uses read-only market-data tools and Qdrant retrieval, cites its sources, and checks claims against the evidence before returning a grounded, partial or insufficient answer.

Includes offline agent tests, Phoenix tracing and a frozen-data evaluation harness. Evaluation results are pending; the LightGBM and FinBERT training pipelines are scaffolding, with no trained models deployed yet.

`React` `TypeScript` `FastAPI` `LangGraph` `Qdrant` `PostgreSQL` `Celery`

The source code for both projects is private. I'm happy to walk through either one in an interview.

## At work

The code belongs to my employer, so here is what it does instead.

| Project | What I built | Result |
|---|---|---|
| iResolve | Internal React and Django platform for debt-collection operations, built with a spec-driven, AI-assisted workflow (Claude Code, OpenAI Codex) and deployed on AWS behind IIS | Self-service eligibility checks reclaimed **4 FTEs** of daily work |
| Staging ETL | Mirror of the Artiva production server, refreshed every 8 hours with load-balanced parallel batching | **2 million accounts** load in **1.5 hours** instead of 5 |
| Bill Bot | Regex-based parser that turns inconsistent bill PDFs into Excel and checks them against the master consumer database | About **2 hours a day** saved across 5 people |
| Placement pipeline | SFTP-to-SFTP transfer of client files, with an automated data quality report for leadership | About **1 hour a day** saved across 2 people |

## Tech

- **AI and ML:** PyTorch, YOLOv8, OpenCV, LightGBM, SHAP, LoRA/PEFT fine-tuning
- **LLMs and agents:** LangGraph, Qdrant, RAG, LLM APIs, Claude Code, OpenAI Codex
- **Backend and data:** Python, Django, FastAPI, Flask, React, SQL, PostgreSQL, MongoDB, Pandas
- **MLOps and infra:** MLflow, AWS, IIS, Git, MQTT

## Contact

[Portfolio](https://huzaifamanasawala.netlify.app/) · [LinkedIn](https://linkedin.com/in/huzaifa-manasawala) · [huzaifamanas@gmail.com](mailto:huzaifamanas@gmail.com)
