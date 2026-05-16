[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Stellar](https://img.shields.io/badge/network-Stellar-black)](https://stellar.org)

# RepoFlow Docs

Protocol documentation and integration guides for the RepoFlow ecosystem.

## Technical Architecture

```
docs site (GitHub Pages) → repoflow-docs/src → build pipeline
Structure: /protocol | /contract | /indexer | /app | /sdk | /guides
```

## Local Development Setup

### Prerequisites

| Tool | Version | Install Command |
|---|---|---|
| Node.js | 20 LTS | https://nodejs.org/ |
| npm | 10+ | Comes with Node.js |

### Setup Commands

```bash
npm install
npm run dev
```

## Technology Stack

| Component | Technology | Version |
|---|---|---|
| Frontend Framework | Next.js | 14.x |
| Static Site Generation | Next.js | 14.x |
| Styling | Tailwind CSS | 3.x |
| Documentation | MDX | Latest |
| Deployment | GitHub Pages | N/A |
| Smart Contract | N/A | N/A |
| Backend | N/A | N/A |
| Infrastructure | N/A | N/A |