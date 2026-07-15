# Dynamo assessment: repaired log-report task

This repository contains the corrected Terminal-Bench 2 / Harbor task under `log-report/`.

Run from the repository root:

```bash
harbor run -p log-report -a oracle
harbor run -p log-report --agent nop
```

The oracle should receive reward `1`; the nop agent should receive reward `0`.
