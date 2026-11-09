# My ~/[AGENTS.md](./AGENTS.md)
The most important productivity-boosting / cost-cutting file on your machine these days.

Run from the repo root. Move or merge existing files at the link paths first.

### macOS

```sh
mkdir -p ~/.claude ~/.gemini
ln -s "$PWD/AGENTS.md" "$HOME/AGENTS.md"
ln -s "$HOME/AGENTS.md" "$HOME/.claude/CLAUDE.md"
ln -s "$HOME/AGENTS.md" "$HOME/.gemini/GEMINI.md"
```

### Windows PowerShell

Enable Developer Mode or run PowerShell as administrator.

```powershell
New-Item -ItemType Directory -Force -Path "$HOME/.claude", "$HOME/.gemini"
New-Item -ItemType SymbolicLink -Path "$HOME/AGENTS.md" -Target "$PWD/AGENTS.md"
New-Item -ItemType SymbolicLink -Path "$HOME/.claude/CLAUDE.md" -Target "$HOME/AGENTS.md"
New-Item -ItemType SymbolicLink -Path "$HOME/.gemini/GEMINI.md" -Target "$HOME/AGENTS.md"
```

## What is AGENTS.md?
https://agents.md
