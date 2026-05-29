# Nexstone Homebrew Tap

Homebrew formulas for Nexstone-distributed CLI tools.

## Install RIFT

```bash
brew install Nexstone/tap/rift
```

This installs both the Python engine (`rift-engine-core`) and the TypeScript
CLI (`@nexstone/rift-cli`) into an isolated prefix, and exposes a single
`rift` command on your PATH.

After install:

```bash
rift doctor      # smoke-check the install
rift --help      # explore commands
```

## What's here

| Formula | Project |
|---|---|
| [`rift`](Formula/rift.rb) | https://github.com/Nexstone/rift |
