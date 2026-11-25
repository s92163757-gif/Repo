---
title: Atlas AI
emoji: 🤖
colorFrom: indigo
colorTo: blue
sdk: static
pinned: false
---

# Atlas AI — Gemini edition

A lightweight static chat interface that connects to the Google Gemini API.

## Setup
1. Open the Space's **Files** tab.
2. Upload this `index.html` to the repository root, replacing the old one.
3. Commit the change and open the **App** tab.
4. Expand **AI connection settings** and paste your Google AI Studio API key.
5. Send a test message.

The key is entered in the browser and is not stored in the repository or local storage. This is suitable for personal testing, but a browser-based app cannot fully protect an API key from the device/browser or network inspection. Do not share the Space if you use a personal key. For a public multi-user app, put the key on a private backend instead.

The default model is `gemini-2.5-flash`. Free-tier eligibility, model availability, and rate limits depend on Google's current terms and account settings. API usage may incur charges if billing is enabled or free limits are exceeded.
