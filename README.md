# tiny-stack-vm-01-run-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Sandivisi/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Sandivisi/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A complete interpreter for make.fun's tiny stack ISA: 32-bit wrapping integers, a 256-value stack, calls, 256 words of memory, input/output, and all ten traps, including the hard rules (exact `Math.imul`, `-2147483648 / -1`, unsigned DIVU/MODU/LTU, 5-bit shifts, PUSH8 sign extension, step/output limits).

## Run it

```sh
node main.ts
```

Reads `/input/<id>/`, writes `/output/<id>/stdout.bin` + `exit.txt`. Node 22.
