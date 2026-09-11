# advent-of-code

My solutions to [Advent of Code](https://adventofcode.com), the yearly series of small programming puzzles released one per day through December.

Solutions are grouped by year and day. Each day folder holds the puzzle input alongside the solution, written mostly in Node.js (`solution.mjs`, with a separate `solution-2.mjs` when the second part needed its own script) and occasionally as a shell script. Some days also keep the sample input from the puzzle statement as `test.txt`.

## Run

Scripts read `input.txt` from the current directory, so run them from inside the day folder:

```bash
cd 2022/02
node solution.mjs
```

Shell solutions run the same way with `bash solution.sh`. Node 16 or later is enough.
