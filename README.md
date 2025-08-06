# bun-max-cpu

What is the issue?

Bun will consistently use 100% when debugging.

To reproduce the issue:

```bash
bun install
```

To run the script:

# Run the script with VSCode debugger

1. Go to Run and Debug
1. Click on the "Launch Bun Debugger" configuration

or
```bash
bun run --inspect-wait=localhost:6499/debugger --watch index.ts
# then attach to the debugger in VSCode
```
or
```bash
bun run inspect-wait
# then attach to the debugger in VSCode
```
or
```bash
bun run inspect
# then attach to the debugger in https://debug.bun.sh/#localhost:6499/debugger
```