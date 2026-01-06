# wip-cli

A simple CLI for [wip.co](https://wip.co).

## Install

```bash
# Copy to your PATH
curl -o /usr/local/bin/wip https://raw.githubusercontent.com/marckohlbrugge/wip-cli/main/wip
chmod +x /usr/local/bin/wip

# Authenticate
wip auth login
```

## Usage

```
wip todos              List your recent todos
wip todo create <msg>  Create a completed todo
wip projects           List your projects
wip status             Show your profile and streak
```

## Requirements

- bash
- curl
- jq

## API Key

Get your API key from [wip.co/api](https://wip.co/api). Stored in `~/.config/wip/api_key`.
