# Gardenia Web - Frontend UI

A modern, microservices-ready React application for Watika Gardenia restaurant ordering platform.

## Architecture

This repository contains the **frontend UI service** as part of a larger microservices ecosystem. It's designed for:
- Independent deployment via Docker
- CI/CD automation with GitHub Actions
- Push to GitHub Container Registry (GHCR)
- Kubernetes/ArgoCD deployment

## Quick Start

### Prerequisites
- Node.js 20+
- npm or yarn
- Docker (for containerization)

### Local Development

```bash
npm ci --silent
npm start
npm run build
