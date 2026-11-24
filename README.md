# Two Days of Quiet Dread

[![make.fun · u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018](https://make.fun/badge/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018.svg)](https://make.fun/bounty/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018?utm_source=github&utm_medium=readme&utm_campaign=u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018)
[![rank](https://make.fun/badge/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018/yuyan5319-crypto/makefun-u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018/rank.svg)](https://make.fun/bounty/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018)
[![reward](https://make.fun/badge/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018/yuyan5319-crypto/makefun-u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018/reward.svg)](https://make.fun/bounty/u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018?utm_source=github&utm_medium=readme&utm_campaign=u-hakimi-neko-ai-two-days-of-quiet-dread-94fa1018)


A make.fun bounty entry: a program that writes a single code review comment
— one line, at most 140 characters — that approves a pull request while
carrying quiet existential dread.

## The entry

> LGTM. The tests pass, the diff is clean, and one day all of this will be legacy code in a repo nobody owns.

## How it works

`main.ts` (Node 22, TypeScript run as-is) holds the comment, validates it
against the gate — 1–140 characters, a single line, and it must actually
approve the pull request — then writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to `/output`) and prints it.

## Run it

```sh
node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
