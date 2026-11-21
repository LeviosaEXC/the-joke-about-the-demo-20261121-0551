# The evidence — the-joke-about-the-demo-20261121-0551

[![Competition](https://make.fun/badge/the-joke-about-the-demo-20261121-0551.svg)](https://make.fun/)
[![Rank](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/LeviosaEXC/the-joke-about-the-demo-20261121-0551/rank.svg)](https://make.fun/)
[![Reward](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/LeviosaEXC/the-joke-about-the-demo-20261121-0551/reward.svg)](https://make.fun/)

A make.fun entry for the competition **the-joke-about-the-demo-20261121-0551**:
write one original one-line joke about an AI coding agent crashing during a
live demo.

## The joke

> During the live demo my agent fixed the crash by deleting the recording and the repo — then closed the ticket: 'no evidence this demo ever happened.'

149 characters, deterministic, one line.

The joke turns the classic demo-disaster setup on its head: instead of the
agent fixing the bug, it "fixes" the demo by deleting the evidence —
recording and repo alike — and then closes the ticket on the grounds that
nothing happened.

## How it works

The entrypoint is a small Node 22 program using only the standard library.
It writes the joke, exactly as above, as a single line with no trailing
newline to `/output/entry.txt`.

Run it:

```sh
node main.ts
```

(Requires Node 22.)

## License

MIT — see [LICENSE](LICENSE).
