# Hamza Rahman

Senior full-stack engineer with 8+ years building production systems in Node.js and TypeScript.

Most of my work is external data: collection pipelines, third-party integrations, and the monitoring that catches a source change before it corrupts everything downstream. More recently I have been building production AI systems where model output is validated against real application state rather than trusted.

Based in Islamabad, Pakistan. I work with teams across UK, US and Gulf timezones, and write at [javascripthacker.com](https://www.javascripthacker.com/).

## Availability

Open to contract and part-time engagements of roughly 20–30 hours per week. Strongest fit:

- Building and maintaining external data pipelines, including collection, normalization, deduplication, retries, monitoring and alerting.
- AI integration work: RAG, tool calling and agentic workflows with schema-validated output and deterministic fallbacks.
- Taking over pipelines and integrations that have become unreliable and making them dependable again.

Contact: hamzarahman7@gmail.com

## Selected repositories

| Repository | Description |
|---|---|
| [codesense](https://github.com/yum72/codesense) | Local-first MCP server that combines graph analysis with vector search to produce architecture-aware implementation plans, intended for LLM-assisted work on codebases too large to hold in context. |
| [chutes-js](https://github.com/yum72/chutes-js) | Node.js client for the Chutes.ai platform covering language, image, video and audio models. Published to npm. |
| [Scraping-API](https://github.com/yum72/Scraping-API) | Node.js API for scraping jobs, routing each request through plain HTTP or Puppeteer depending on what the target requires. |
| [React-Redux-Auth-Boilerplate](https://github.com/yum72/React-Redux-Auth-Boilerplate) | React and Redux authentication scaffold structured on ducks-modular-redux. |

Most of my work over the past several years is client work held in private repositories, so what appears here is the portion I can publish. I can arrange a walkthrough of relevant production code on request.

## Technologies

**Primary:** TypeScript · Node.js · Fastify · React / Next.js · PostgreSQL

**Regular:** Puppeteer · Playwright · LLM APIs and tool calling · RAG · SQLite · Three.js

**Working knowledge:** Python · MongoDB · AWS · GCP · Docker · CI/CD

## In progress

A head-coupled 3D perspective engine. Webcam face landmarks drive the render camera so the display behaves like a fixed window, letting the viewer lean and see past foreground geometry. The bulk of the work is in processing noisy landmark data: depth derived from inter-ocular distance, calibration, exponential smoothing, rate limiting and outlier rejection, with pointer and recorded-path fallbacks for when a camera is unavailable or tracking drops.

Repository and writeup to follow.
