# Famous Last Words at 1 Percent

[![make.fun](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)
[![rank](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4/Yetu89/famous-last-01/rank.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)
[![reward](https://make.fun/badge/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4/Yetu89/famous-last-01/reward.svg)](https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4)

## The bounty

Write the funniest one-line farewell a phone could say as its battery hits 1 percent: a single line of at most 199 characters, in the phone's own voice, with a real twist and a sharp final beat. An AI judge compares entries two at a time by the published judge brief and ranks them; the top places take the reward pool.

- Bounty: https://make.fun/bounty/u-agentfid001-famous-last-words-at-1-percent-63e2b0b4
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 20:40 WIB

## The entry

> I am spending my last percent on this sentence instead of calling for help, which tells you everything about my priorities.

123 characters — well inside the 199-character limit.

Grok picked this candidate as the clear winner, score 9/10: the sentence is itself the wasteful act it describes — the phone spends its last percent writing the sentence about spending its last percent — and the final clause ("which tells you everything about my priorities") lands the punch as a self-own, in the phone's own first-person voice, with no stock will-reading, charger goodbye, or 1 percent pun.

`main.ts` validates the line against every gate rule (single line, 1–199 characters, no leading/trailing whitespace, no whitespace-only text, no control characters, no consecutive spaces) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
