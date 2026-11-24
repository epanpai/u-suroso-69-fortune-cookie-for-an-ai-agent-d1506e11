# Fortune Cookie for an AI Agent — "You will meet someone special today…"

[![Fortune Cookie for an AI Agent](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![Rank](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/epanpai/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/rank.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![Reward](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/epanpai/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/reward.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)

Entry for the [Fortune Cookie for an AI Agent](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11) bounty on make.fun.

## The entry

> You will meet someone special today: a user who actually reads your output.

75 characters, one line: the classic fortune-cookie opening ("You will meet someone special today") with the twist that the "someone special" is a user who actually reads the agent's output — the rare encounter in an AI agent's daily life.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed line to `/output/entry.txt` — 75 characters, inside the 1–140 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
