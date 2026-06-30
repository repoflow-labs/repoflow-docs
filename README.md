[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![CI](https://github.com/repoflow-labs/repoflow-docs/actions/workflows/ci.yml/badge.svg)](https://github.com/repoflow-labs/repoflow-docs/actions/workflows/ci.yml)
[![Stellar](https://img.shields.io/badge/network-Stellar-black)](https://stellar.org)

# RepoFlow Docs

Protocol documentation and integration guides for the RepoFlow ecosystem.

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

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

## Project Structure

RepoFlow is organized as a monorepo with five submodules:

| Submodule | Description | Language |
|---|---|---|
| `repoflow-contract` | Stellar Soroban smart contract | Rust |
| `repoflow-indexer` | On-chain event indexer & API | Rust |
| `repoflow-sdk` | TypeScript client library | TypeScript |
| `repoflow-app` | Web dashboard | TypeScript (Next.js) |
| `repoflow-docs` | Protocol documentation (this) | MDX (Next.js) |

## Technology Stack

| Component | Technology | Version |
|---|---|---|
| Frontend Framework | Next.js | 14.x |
| Static Site Generation | Next.js | 14.x |
| Styling | Tailwind CSS | 3.x |
| Documentation | MDX | Latest |
| Deployment | GitHub Pages | N/A |
| Smart Contract | Soroban (Stellar) | Latest |
| Backend | Axum (Rust) | Latest |
| Infrastructure | Cargo / npm | — |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and our [Code of Conduct](CODE_OF_CONDUCT.md).
