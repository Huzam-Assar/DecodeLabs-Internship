# Project 1: Linux & Command Line Basics

DevOps Industrial Training Kit — DecodeLabs, Batch 2026

## Goal

Learn and use basic Linux commands required in DevOps environments: file/directory
operations, navigation, permissions, and observability commands.

## Mission: Web App Setup

Simulated a basic web app folder structure using only CLI commands (no GUI).

| Step | Task     | Command                                    |
|------|----------|---------------------------------------------|
| 1    | Scaffold | `mkdir -p app/logs`                          |
| 2    | Config   | `touch app/config.conf`                      |
| 3    | Inject   | `echo "Started" > app/logs/server.log`       |
| 4    | Verify   | `pwd` && `ls -R app`                         |
| 5    | Backup   | `mv app/logs/server.log app/logs/server.bak` |
| 6    | Audit    | `ls -l app/config.conf`                      |

Full command-by-command terminal output is in [`NOTES.md`](./NOTES.md).

## Final Structure

```
app/
├── config.conf
└── logs/
    └── server.bak
```

## Key Commands Covered

- Navigation: `pwd`, `cd`, `ls` (`-l`, `-a`, `-R`)
- File/Directory ops: `mkdir -p`, `touch`, `cp`, `mv`, `rm` (`-i`, `-rf`)
- Viewing/Monitoring: `cat`, `less`, `head`/`tail`, `tail -f`
- Access & Permissions: `ssh`, `whoami`, `id`, `chmod`, `chown`

## Author

Basim Hassan — COMSATS University Islamabad
