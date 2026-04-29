# wizapp

**An Akinator-style wizard that turns vague intent into a build-ready, deploy-ready prompt.**

Pick three trending interests, set the languages, then answer up to thirty Yes/No/Skip questions. Hit **Generate** whenever you have enough signal — the prompt drops into your history, ready to paste into Claude.

## Try it live

👉 **https://g0rd33v.github.io/wizapp/**

## How it works

1. **Gravity** — Three trending interests + the languages you want supported. They steer everything: concept, audience, voice, examples.
2. **Up to thirty taps** — Yes / No / Skip. Stop whenever you want by hitting **Generate** (available after question five). Skipped or unasked fields become *let Claude decide*.
3. **History, not popups** — Each generated prompt is saved into local storage as a one-line summary. Open it, copy the full prompt, drop it into Claude.
4. **Ship live** — The prompt explicitly tells Claude to upload, commit, and promote on hub.labs.co. The deliverable is a live URL.

## Stack

- Single self-contained `index.html`
- No frameworks, no build step, no dependencies
- Pure client-side (history saved in `localStorage`)

## Made by

A project from [Labs](https://labs.co) — part of the [Hub](https://hub.labs.co) ecosystem.
