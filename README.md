ScholarSync MVP — Abstract Protocol Demo

A lightweight MVP for ScholarSync: a platform that verifies short academic video summaries (“Reels”) against their published papers using transcription, NLP, and timestamp proofs.

This repository contains:
- A **Next.js frontend** for uploading videos and pasting paper URLs.
- A **FastAPI backend** that:
  - Transcribes uploaded videos using AssemblyAI.
  - Fetches abstracts from arXiv or PubMed using public APIs.
  - Computes semantic similarity between transcript and abstract.
  - Returns a verification score.
- A **Postgres/Supabase** database for storage.
- Optional **OpenTimestamps** integration for cryptographic timestamping.

---

## 🚀 Project Structure

