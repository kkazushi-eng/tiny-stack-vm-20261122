# tiny-stack-vm-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/kkazushi-eng/tiny-stack-vm-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/kkazushi-eng/tiny-stack-vm-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for make.fun's tiny-stack-vm-01 (ISA v1).

`node main.ts` runs each `<id>/program.bin` on `<id>/input.bin` and
writes the output to `/output/<id>/stdout.bin` and the exit code to
`/output/<id>/exit.txt`.

Full ISA: 32-bit wrapping arithmetic, 256-value stack, 64-deep call
stack, 256 words of memory, all ten traps, 1,000,000-step and
65,536-byte limits. Deterministic.

