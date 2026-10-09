# Hi, I'm Louis 👋

**Full Stack Software Engineer** at **[Songtrust](https://www.songtrust.com)** (Downtown Music, part of Universal Music Group).

I'm building a new platform there: a multi-tenant GraphQL federation layer (TypeScript, Node,
Next.js, Apollo Federation) that integrates data across Downtown Music's operating companies.
I own the frontend and ship features end to end across the API layer. With our head of
technology, I co-develop the harness we use to build with AI agents, and I support Product and
Design in adopting agentic workflows of their own.

Before that I worked on Songtrust's royalty administration platform, where independent musicians
sign up, submit their songs, and collect the royalties we register and gather for them worldwide,
on a Python/Django and React/TypeScript stack.

Before software, I spent four years as a **Doctor of Physical Therapy**: two as a traveling
therapist, taking over full caseloads at underserved clinics on 3–6 month assignments, and two in
home health. Across both I managed complex caseloads and supervised assistants on interdisciplinary
teams. It taught me to move without perfect information and pull in the right people at the right
time.

### Tech
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

### MangoWave · [mangowave.app](https://mangowave.app)
A free, no-install, no-signup browser audio visualizer built on a fork of butterchurn, a WebGL 2 port of the MilkDrop engine.
- The base engine couldn't parse newer shader presets, so I compiled an HLSL→GLSL ES 3.0 converter to WebAssembly and ran it on the fly in a Web Worker (off the main thread). I hand-checked each new preset on desktop and mobile before shipping it, growing the library from 395 to 832 presets.
- The fork carries 17 documented engine patches, including frame-rate normalization for high-refresh displays, GPU memory leak and WebGL context-loss fixes, and a fix for a 3–5 second startup freeze on mobile.
- Cross-device "rooms" sync peer-to-peer over WebRTC, and separate windows or monitors on one machine stay in sync over BroadcastChannel, both with no backend; a small serverless AWS stack (CDK, Lambda, DynamoDB) handles optional Spotify and cloud-sync.

### Utilization Management Tool · private
An AI-assisted clinical review tool for healthcare: it reads a consult request, retrieves the matching clinical criteria with RAG over pgvector, and drafts a decision with references that a physician can review, refine with the AI, and finalize.
- Built on AWS (FastAPI, Lambda, SQS, CDK) with Textract OCR and Claude on Amazon Bedrock with Guardrails, plus a Next.js reviewer console and facility portal behind Cognito role-based login.

### MIMIC · [mimic-replay.com](https://mimic-replay.com) — co-created, team of four
An error-focused session-replay framework: it records the user session (DOM via rrweb, plus custom fetch/XHR/WebSocket interceptors) and replays it as a live DOM reconstruction in a React playback dashboard.
- A four-stage telemetry pipeline over three stores: Redis buffers active sessions, an event-driven Redis pub/sub subscription archives them to S3 on session end, and PostgreSQL holds queryable metadata.
- A Python CLI installer on PyPI injects the capture script into an app's pages.

### Also
- **[aloud](https://github.com/Louis-Mascari/aloud)** — a local voice interface for Claude Code that speaks a short summary of each turn and flags which sessions need attention, plus an offline PDF read-along app.
- **Mozilla** — patches to the Firefox desktop platform (bug fixes, Mochitest unit tests, docs).

### Let's connect
Frontend architecture · agentic development · music tech · video games · lifting · the move from healthcare into engineering.

[Website](https://louis-mascari.com/) · [LinkedIn](https://www.linkedin.com/in/louis-mascari/) · [Email](mailto:LouisMascari@gmail.com)
