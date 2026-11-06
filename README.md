# Lexicon — Legal Workflow Automation

AI-powered legal contract risk triage and workflow automation with human-in-the-loop controls.

## What it does

- **Contract intake** — bring a contract into the pipeline
- **AI contract analysis** — clause-level risk scoring and flagging
- **Workflow queues** — route flagged items to a human reviewer before anything is finalized
- **Audit trail** — every decision logged and traceable
- **Prompt lab** — tune the analysis prompts without touching code

## Live demo

[ai-lexicon.netlify.app](https://ai-lexicon.netlify.app/)

## How the analysis works

This is a portfolio demonstration. Clause scoring runs on a built-in rule engine in the browser (`lexicon-heuristic-v1`), so it works instantly with no API key and no data leaves your machine. The prompt lab shows the prompts a production version would send to an LLM.

## Run it locally

The app is a single self-contained page — no build step, no dependencies:

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` in a browser.

## Background

Built as a working demo of how a legal team could triage contract risk with AI assistance while keeping a human in the approval loop. By [Emre Senturer](https://github.com/emresenturer).
