# myself-info

## GitHub

- Account: `snowtone-ai`

## Current Development Environment

- Host OS: Windows
- Editor: VSCode
- Terminal: PowerShell
- Main project root: `C:\Users\chidj\project`
- Current repository: `C:\Users\chidj\project\pm-zero`
- Claude Code: Windows PowerShell environment
- Codex CLI: Windows PowerShell environment
- Remote Unix-style development: not used

## Shell Policy

PowerShell is the only local shell for this environment.

- Use PowerShell for `git`, `pnpm`, `npm`, `node`, `rg`, `gh`, `claude`, and `codex`.
- Use Windows paths such as `C:\Users\chidj\project\worksim`.
- Do not assume remote home paths, remote project paths, or Unix-style shell commands are available.
- If older documents mention a remote Unix-style workflow, treat them as legacy context.

## Global Configuration Locations

- Codex: `C:\Users\chidj\.codex`
- Claude Code: `C:\Users\chidj\.claude`
- Projects: `C:\Users\chidj\project`

## Current CLI Baseline

- Node.js: installed on Windows
- npm: installed on Windows
- pnpm: installed globally
- git: installed on Windows
- GitHub CLI: installed on Windows
- ripgrep: installed on Windows
- rtk: installed globally
- Claude Code: installed globally
- Codex CLI: installed globally

Check with:

```powershell
node --version
npm --version
pnpm --version
git --version
gh --version
rg --version
claude --version
codex --version
```

## Default Commands

Open the repository:

```powershell
code C:\Users\chidj\project\pm-zero
```

Check status:

```powershell
Set-Location C:\Users\chidj\project\pm-zero
git status
```

Typical project verification:

```powershell
pnpm install
pnpm lint
pnpm build
pnpm test
```

Use only the commands that exist in the target repository.

## Hardware Notes

- PC: dynabook GA/ZY W6GAZY5RDL
- SSD: 223 GB
- RAM: 16 GB
- Power: AC or battery
