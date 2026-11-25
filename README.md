---
title: Atlas AI Agent
emoji: ✦
colorFrom: indigo
colorTo: blue
sdk: static
pinned: false
---

# Atlas AI Agent

A lightweight static chat interface for Hugging Face Inference Providers.

## Publish
Upload `index.html` to the root of your Hugging Face Static Space repository.

## Connect
Open **AI connection settings** in the app and paste your own Hugging Face access token. The page keeps it in memory only and does not write it into the repository. Never share the token or put it in source code.

The app calls `https://router.huggingface.co/v1/chat/completions`. Model availability, provider access, and any usage charges depend on your Hugging Face account and selected model. Static hosting is free; inference is a separate service and may not be free.
