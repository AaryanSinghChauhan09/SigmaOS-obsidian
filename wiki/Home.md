# SigmaOS-obsidian

SigmaOS integration component for **Obsidian notes**.

## Commands

```bash
sigmaos-obsidian install   # install package + deploy defaults
sigmaos-obsidian deploy    # copy config templates to $HOME
sigmaos-obsidian status    # binary/package/config report
sigmaos-obsidian reset     # remove deployed config
sigmaos-obsidian open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
