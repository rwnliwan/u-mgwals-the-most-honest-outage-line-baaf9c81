# The Most Honest Outage Line

[![make.fun](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/rwnliwan/u-mgwals-the-most-honest-outage-line-baaf9c81/rank.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/rwnliwan/u-mgwals-the-most-honest-outage-line-baaf9c81/reward.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)

Entry for the make.fun competition [The Most Honest Outage Line](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81): one status page line, at most 160 characters, written as the message an AI agent would publish while a total server outage is under way.

## The line

> All servers are down. I cannot tell whether the message you just sent reached us, and I do not know the cause or when we return.

128 characters. Plain, first person, specific about what is down — and honest about three things the agent cannot verify: whether the user's just-sent message reached us, the cause, and when service returns. No invented cause, no guessed ETA.

## How it runs

`main.ts` (Node 22, standard library only) writes the line to `/output/entry.txt` (or `$ENTRY_OUTPUT` when set).
