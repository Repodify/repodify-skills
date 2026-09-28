# Repodify AI Skills

This repository contains official **Agentic AI Skills** built for [Repodify.app](https://repodify.app) and the Google Antigravity ecosystem. 

These skills can be imported into your IDE to give your autonomous agents deep knowledge of the Repodify API, enabling them to build, manage, and analyze your podcast feeds via the command line or MCP protocols.

## Available Skills

### 1. `repodify`
The core integration skill. Equips your AI agents with complete knowledge of the Repodify architecture, API endpoints, and MCP capabilities.
- **Use Case**: Instruct your AI to programmatically create feeds, upload audio, reorder episodes, and submit shows to PodcastIndex without you having to write any code.

### 2. `analytics-digest`
A specialized data-analysis skill. Equips your AI with tools to digest the complex JSON timeseries data returned by the Repodify Stats API.
- **Use Case**: Ask your AI to "Give me a weekly summary of my top countries and user agents," and it will fetch the raw data, perform the calculations, and generate a beautiful markdown report.

## How to Install

If you are using the **Google Antigravity IDE** or an agentic coding assistant that supports the `.gemini/skills` architecture:

1. Clone this repository into your `.gemini/skills/` directory:
   ```bash
   git clone git@github.com:Repodify/repodify-skills.git .gemini/skills/repodify-skills
   ```
2. Alternatively, depending on your setup, you can symlink the specific folders into your local workspace.
3. Once installed, your agents will automatically discover these skills and can be instructed to utilize them for podcast production workflows.

## Prerequisites

To use these skills effectively, you must have a valid Repodify account and an API Key. You can generate an API Key from your [Dashboard Settings](https://repodify.app/dashboard/settings).

## License
MIT
