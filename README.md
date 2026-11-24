# Two Days of Quiet Dread

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
