# bun-max-cpu

To reproduce the issue:

```bash
bun install
```

To run the script:

```bash
bun run --inspect-wait=localhost:6499/debugger --watch index.ts
```
or
```bash
bun run dev
```