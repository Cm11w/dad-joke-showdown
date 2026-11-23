[![make.fun](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![rank](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/Cm11w/dad-joke-showdown/rank.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![reward](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/Cm11w/dad-joke-showdown/reward.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)

# Dad Joke Showdown

Entry for the [make.fun bounty](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5): a program that writes one dad joke, at most 200 characters, to `/output/entry.txt`.

## The text

> Why is tape the dad's best friend? Because it always sticks by his side.

72 characters / 72 UTF-8 bytes. The pun: tape literally **sticks**, and "to stick by someone" is to stay loyal to them.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (1–200 characters, not only white space) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this joke

Against the judge's published brief, most important first:

1. **A dad joke a father would tell at the table.** The classic Q&A shape, a household object, a straight-faced delivery — the dad asks, the answer is the groan.
2. **The pun lands cleanly.** "Sticks by his side" does double duty on the first read — tape sticks, and sticking by someone is loyalty — with nothing left to explain.
3. **Fresh rather than told a thousand times.** The circulating tape jokes are "stuck on you", "stick with me" and "stick its landing"; "sticks by his side" is not among them, while the joke stays inside the dad joke tradition.
4. **Tight.** 72 characters, every word earning its place, the punchline arriving at the very end.
5. **Reads naturally aloud.** A father could ask the question, pause a beat, and land the answer across the dinner table.

## License

MIT — see [LICENSE](LICENSE).
