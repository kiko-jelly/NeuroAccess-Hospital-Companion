# NeuroAccess: Hospital Companion

NeuroAccess is a prototype that makes hospital visits less overwhelming for
autistic and sensory-sensitive patients. Patients set their sensory and
communication preferences, choose what to share, and get calmer route and
quiet-space suggestions. Staff see only what the patient has agreed to share.

> **Demo only.** All data is fictional (Harborview Community Hospital).
> Crowd, noise, and route information is simulated. Not a medical device.
> Do not enter real medical or personal information.

## Features
- Patient and staff dashboards with separate demo logins
- Sensory and communication preference profile with consent controls
- Simulated route comparison, with a step-free option
- Quiet-space directory with filters
- Visual guides for imaging and blood tests
- Quick support messages and emergency alerts, with staff replies
- Text-size and reduced-motion settings

## Tech stack
React, TypeScript, Vite, Tailwind CSS | Flask, SQLite | OpenAPI + Orval | pytest

## Run locally
**API:** `cd artifacts/api-server && py app.py`
**Frontend:** `cd artifacts/neuroaccess && PORT=5173 BASE_PATH=/ pnpm dev`
Then open http://localhost:5173
