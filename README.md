# bun-max-cpu

To reproduce the issue:

```bash
bun install
```

set a debug point on the console.log("hello") line

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
bun run dev
# then attach to the debugger in VSCode
```