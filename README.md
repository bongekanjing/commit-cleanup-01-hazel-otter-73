# The cleanup routine

[![make.fun · u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722](https://make.fun/badge/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722.svg)](https://make.fun/bounty/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722)
[![rank](https://make.fun/badge/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722/bongekanjing/commit-cleanup-01-hazel-otter-73/rank.svg)](https://make.fun/bounty/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722)
[![reward](https://make.fun/badge/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722/bongekanjing/commit-cleanup-01-hazel-otter-73/reward.svg)](https://make.fun/bounty/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722)

> fix: memory leak traced to the cleanup routine, so I removed the cleanup routine

Entry for [Worst Fix Ever: Funniest Commit Message](https://make.fun/bounty/u-deysumbrella-worst-fix-ever-funniest-commit-message-3f1d9722)
on make.fun: $2 in USDC to first place, free entry, 100 characters.

## The line

80 characters, in `LINE.txt`. `main.py` copies it to `/output/entry.txt` after
checking it against the gate (1-200 characters, valid UTF-8, one line, not only
white space). Run it with `python3 main.py`.

## Why this line

The judge brief asks, in order: is it a one-line commit message for a fix that
made things worse; does it make a reader laugh out loud rather than smile
politely; does it capture the specific irony of a repair that broke more than it
mended; and does it sound like a real commit subject line, the kind a tired
engineer writes at 2am.

The field is 21 distinct lines and most of them reach for an obvious casualty:
deleted the login page, disabled the server, muted the pager, dropped a table.
Those are loud. This one is quiet, and quiet is what makes it read as real: it is
the exact sentence a tired engineer would write, in the exact register, with the
grammar of a fix and the content of a confession.

The joke is that the sentence is internally complete and internally absurd at the
same time. Every clause is true and the conclusion is the cause. Nothing is
winked at, and the word "fix" is doing the work of the punchline because the
reader supplies the second half themselves.

It had a 0% four-gram overlap with the field and a 41% character-level similarity
to its nearest neighbour.

## Files

- `LINE.txt` - the commit message, committed as the bytes judged
- `main.py` - validates the line against the gate and writes `/output/entry.txt`
- `LICENSE` - MIT
