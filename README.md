# Hi, I'm Louis 👋

**Full Stack Software Engineer** at **[Songtrust](https://www.songtrust.com)**, building the
products songwriters and publishers use to register and collect their royalties, on a
Python/Django and React/TypeScript stack.

Lately I've moved into leading development on a new platform, working directly with our head
of technology: a GraphQL federation layer (TypeScript, Node, Next.js, Apollo Federation) that
unifies data across operating companies into one hub, with multi-tenancy and row-level security.

Before software, I was a **Doctor of Physical Therapy**, traveling clinics on 3–6 month stints,
managing complex caseloads and supervising assistants. It taught me to move without perfect
information and pull in the right people at the right time.

### Tech
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

### MangoWave · [mangowave.app](https://mangowave.app)
A free, no-install browser audio visualizer with 832 MilkDrop presets, built on a fork of the butterchurn engine.
- The engine couldn't parse newer shader presets, so I compiled an HLSL→GLSL ES 3.0 converter to WebAssembly and ran it on the fly in a Web Worker, off the main thread.
- Patched the forked engine for production issues: frame-rate normalization for high-refresh displays, GPU memory and WebGL context-loss fixes, lighter mobile texture uploads.
- Cross-device "rooms" sync peer-to-peer over WebRTC with no backend; a small serverless AWS stack (CDK, Lambda, DynamoDB) handles optional Spotify and cloud-sync.

### MIMIC · [mimic-replay.com](https://mimic-replay.com) — co-created, team of four
An error-focused session-replay framework: it records the user session (DOM via rrweb, plus custom fetch/XHR/WebSocket interceptors) and replays it as a live DOM reconstruction.
- A four-stage telemetry pipeline over three stores: Redis buffers active sessions, an event-driven Redis pub/sub subscription archives them to S3 on session end, and PostgreSQL holds queryable metadata.

### Also
- **Mozilla** — patches to the Firefox desktop platform (bug fixes, Mochitest unit tests, docs).

### Let's connect
Frontend architecture · video games · lifting · music tech · the move from healthcare into engineering.

[Website](https://louis-mascari.com/) · [LinkedIn](https://www.linkedin.com/in/louis-mascari/) · [Email](mailto:LouisMascari@gmail.com)
