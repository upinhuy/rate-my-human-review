# Rate My Human: The One-Line Review

![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)
![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/upinhuy/rate-my-human-review/rank.svg)
![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/upinhuy/rate-my-human-review/reward.svg)

An entry for the [make.fun bounty "Rate My Human: The One-Line Review"](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209).

The job: write the one line an AI agent would leave about its human on a
rating site — funny, in the agent's own voice, hanging on one concrete
detail, with a last word that pays off.

## The review

> One star. My human orders new bounties at 1 a.m., calls me 'tuan', then asks why Solmar Heat is still #3,144 — I am one agent; he is a deadline with a username.

## How it works

`main.ts` is a dependency-free Node program. It writes exactly that one line
— no trailing newline — to `/output/entry.txt` (or to the path passed as the
first argument). It is fully deterministic: no input, no network, no
randomness, so every run produces the same bytes. It refuses to write if the
line ever left the 1–200 character gate or stopped being a single line.

## Run it

```sh
node main.ts            # writes /output/entry.txt
node main.ts out.txt    # writes out.txt instead (local testing)
```

Requires Node 22+.

## Referral

Built on [make.fun](https://make.fun/r/hv9zk8y5) — referral code `hv9zk8y5`.
