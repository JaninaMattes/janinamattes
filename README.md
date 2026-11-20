<!--
  GitHub profile README for github.com/JaninaMattes (repository JaninaMattes/janinamattes).
  Refactored 20 Nov 2026. Every claim traces to docs/Professional_Past_Janina_Mattes_Documentation.md
  and the resume phrase bank; Fudge figures checked against origin/main on 20 Nov 2026.
  Before publishing:
    - Confirm the Munich Motorsport (ROS 2, EKF SLAM) line, which has no source in the master
      file yet. It is commented out below until she confirms it.
    - Pin these repositories on the profile: VerityGraph-RAG, NoiseGuided-SmoothLFM,
      Autonomous-Explorer-Drone, Fudge-Cooking-App.
-->

## Hi, I'm Janina 👋

**Software Engineer — AI Systems** · Sydney, Australia · open to engineering roles in applied AI,
computer vision and LLM systems

I build AI systems that run in production: document AI that feeds LLM platforms, computer vision
models served behind APIs, agentic retrieval systems, and the serverless cloud services around
them. I have 3+ years of professional software engineering experience at **Siemens**, **Porsche**
and **BMW**, and an **MSc in Computer Science from LMU Munich** (High Distinction), including a
year in the research group behind Stable Diffusion working on interpretable, controllable
generative models.

[Website](https://janinamattes.github.io/) · [Email](mailto:janina.alica.mattes@outlook.com)

---

### Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[VerityGraph-RAG](https://github.com/JaninaMattes/VerityGraph-RAG)** <br> *in active development* | Agentic GraphRAG system that parses financial reports with Docling into a Neo4j knowledge graph, designed for multi-hop questions where vanilla RAG fails, with page-level citations for every answer. Hybrid retrieval (Neo4j graph traversal and Qdrant vector search), provenance in PostgreSQL, and an event-driven ingestion pipeline with durable execution, retries and failure recovery. | Python, FastAPI, LangGraph, MCP, Docling, Neo4j, Qdrant, PostgreSQL, Kafka, MinIO, Temporal |
| **[NoiseGuided-SmoothLFM](https://github.com/JaninaMattes/NoiseGuided-SmoothLFM)** <br> *MSc thesis* | Makes flow matching image models interpretable and controllable: an 80M-parameter vision transformer beta-VAE in the latent space of a pretrained SiT-XL flow model, plus self-guidance, an extension of classifier-free guidance conditioned on the learned codes. Halved global FID from 50.1 to 24.5 over 50k samples. | PyTorch, PyTorch Lightning, Hydra, multi-GPU DDP on SLURM |
| **[Autonomous-Explorer-Drone](https://github.com/JaninaMattes/Autonomous-Explorer-Drone)** | Custom PPO actor-critic in PyTorch that trains a Crazyflie 2.x quadrotor in PyBullet to take off and hold stable flight, benchmarked against Stable Baselines3 and a PID controller. | Python, PyTorch, PyBullet, Docker, Weights and Biases |
| **[Fudge-Cooking-App](https://github.com/JaninaMattes/Fudge-Cooking-App)** | Android application with a Spring Boot REST API that matches recipes to the ingredients on hand. JWT authentication, 583 backend and 64 Android tests, 100% backend coverage gated in CI. | Java, Spring Boot, PostgreSQL, Kotlin, JUnit, JaCoCo, GitHub Actions |

---

### Selected industry work

The code below belongs to my employers and is not public; the results are.

- **Document AI for an LLM platform (Siemens Advanta):** developed the document layout analysis
  pipeline (Mask R-CNN, Tesseract OCR) that raised the platform's answer precision by **25%**;
  a 2D k-d tree spatial index cut query latency **10-fold**; every model update was
  regression-tested against a 100-pair golden evaluation dataset.
- **Identity document fraud detection (Institute for Applied AI):** a YOLOv3 system built with
  the German State Criminal Police and Federal Printing Office that cut verification of documents
  from **64 nations** from over **2 months to under 5 seconds**, at 7.5 ms per frame.
- **Serverless cloud platform (Siemens Digital Industries Software):** a TypeScript, Angular,
  NestJS and AWS Lambda platform delivered to production in **2 months** by a 2-person team, plus
  a billing dashboard for **1,000+ enterprise customers**.
- **Generative model training (Ommer Lab, LMU Munich):** cut experiment turnaround from
  **1 week to 2–3 days** through profiling, mixed precision and multi-GPU distributed training.
- **IT operations (Porsche):** a full-stack server availability service and business process
  re-engineering that cut end-to-end process time by **50%**.

---

### Currently

- Extending **VerityGraph-RAG** with an evaluation baseline, Kubernetes deployment, a model
  gateway for managed and self-hosted LLMs, and QLoRA fine-tuning for text-to-Cypher.
- Interested in **trustworthy, interpretable AI**: understanding how models represent what they
  learn, and making their behaviour testable and controllable.
<!-- - Autonomous driving and EKF SLAM with [ROS 2](https://github.com/munichmotorsport) (confirm before publishing) -->

---

### Tech stack

**Languages** · Python, Java, TypeScript, Kotlin, SQL <br>
**AI and ML** · PyTorch, PyTorch Lightning, Mask R-CNN, YOLOv3, flow matching, LangGraph, MCP, RAG, Hugging Face, MLflow <br>
**Backend and cloud** · FastAPI, Spring Boot, NestJS, Flask, PostgreSQL, Kafka, Docker, AWS (Lambda, S3, Cognito, CDK), GitHub Actions <br>
**Frontend** · Angular, RxJS

[![Tech stack](https://skillicons.dev/icons?i=py,java,ts,kotlin,pytorch,fastapi,spring,nestjs,flask,angular,postgres,docker,aws,githubactions,git&theme=light&perline=15)](https://skillicons.dev)
