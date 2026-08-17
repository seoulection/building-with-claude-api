# Building with the Claude API

Jupyter notebooks for the [Anthropic Skilljar course](https://anthropic.skilljar.com/claude-with-the-anthropic-api).

## Pre-requisites

1. Create an `.env` file based off of `.env.example`
2. Add your Anthropic API key to `.env`

## Versions

- uv `0.12.5`
- Python `3.14.7`

## Setup

1. Ensure tools/versions match
2. Clone this repo
3. Run `uv sync` to install dependencies
4. Start the notebook server:
```sh
uv run jupyter lab
```
