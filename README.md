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
wip todos                     List your recent todos
wip todos --today             Today's todos only
wip todos -p <project>        Filter by project hashtag
wip todos -s 2026-01-01       Todos since date
wip todos -n 50               Limit results

wip todo create <message>     Create a completed todo
wip todo view <id>            View a specific todo

wip projects                  List your projects
wip project view <id>         View a specific project

wip status                    Show your profile and streak
```

## Requirements

- bash
- curl
- jq

## API Key

Get your API key from [wip.co/settings/api_keys](https://wip.co/settings/api_keys). Stored in `~/.config/wip/api_key`.
