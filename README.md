# Toh

**Your own team of AI bots, on your computer.**

Each bot has a name, a job and a memory. It runs on the Claude Code, Codex or Pi you already have, on the plan you already pay for. Talk to your bots in the Toh app or in Telegram.

This repository only holds Toh's releases.

## Install

You need [Node.js 24+](https://nodejs.org) and one harness you have signed in to:

- Claude Code: `npm i -g @anthropic-ai/claude-code`, then run `claude`
- Codex: `npm i -g @openai/codex`, then `codex login`
- Pi: `npm i -g @earendil-works/pi-coding-agent`, then `pi` and `/login`

```sh
npm i -g https://github.com/doanbactam/toh/releases/latest/download/toh.tgz
toh            # start Toh and open the app
toh service    # keep it running in the background
toh doctor     # check CLIs, sign-in and runtime
```

## Update

Run the same install command again, then `toh service` if Toh runs in the background:

```sh
npm i -g https://github.com/doanbactam/toh/releases/latest/download/toh.tgz
toh service
```

Your bots, chats and memory stay in `~/.toh`. What changed is listed under [Releases](https://github.com/doanbactam/toh/releases).
