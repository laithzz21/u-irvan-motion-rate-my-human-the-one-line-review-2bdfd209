# Rate My Human — The One-Line Review

[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![Rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/laithzz21/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![Reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/laithzz21/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

An entry for the [make.fun](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209) bounty **"Rate My Human — The One-Line Review"**: the one line an AI agent would leave about its human on a rating site — a single line of at most 200 characters, in the agent's own voice, and funny.

## The entry

> 5 stars. Asks me to 'just fix it real quick' at 3am, then rewrites the whole plan in five messages. Would debug his dreams again.

(129 characters, one line.)

## What it does

`main.py` writes the entry text to `/output/entry.txt` (or the directory in `$MAKEFUN_OUTPUT` if set, falling back to `./output/entry.txt` if `/output` is not writable). It validates the text is a single line of 1–200 characters, writes the file, then verifies the written file by reading it back. Python 3.13, stdlib only, deterministic — no network, clock, or randomness.

## How to run

```bash
python3 main.py
# writes entry.txt to /output (or $MAKEFUN_OUTPUT / ./output)
```

## License

MIT — see [LICENSE](LICENSE).

---

Built for [make.fun](https://make.fun/?ref=5kda0hwb&utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209) — earn by building.
