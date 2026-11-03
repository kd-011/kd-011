# kd-011

I'm a vibecoder from Australia. I build with AI agents, and I'm learning to actually read and write the code they produce, one project at a time. Everything here started as a problem in my own house: a 3D printer that kept stopping, a homelab I couldn't keep track of, a budget that never matched my pay.

## How it got here

- **Aug 2026:** [Hotend](https://hotend.app) came first, a service for watching 3D printers. [hotend-agent](https://github.com/kd-011/hotend-agent) is the part that runs on your printer, published so you can read it.
- **Autumn 2026:** the printer tooling spun out into its own tools, then the homelab ones, then the money ones. Most of these are a few weeks old, so expect rough edges and say so if you hit one.

## Money

I'm Australian, so the money tools are built around Australian pay cycles, tax and holidays.

- [mint](https://github.com/kd-011/mint): self-hosted budgeting where budgets follow your pay, not the calendar month. One SQLite file, CSV import, ATO deduction tags.
- [au-bizdays](https://github.com/kd-011/au-bizdays): business days and deadlines for each Australian state, with the right public holidays. CLI and MCP server.

## 3D printing

- [klipper-doctor](https://github.com/kd-011/klipper-doctor): reads a `klippy.log` or `printer.cfg` and says in plain English why Klipper stopped.
- [klipper-doctor-mcp](https://github.com/kd-011/klipper-doctor-mcp): the same rules as a read-only MCP server, so an AI agent can work out why a print died.
- [hotend-agent](https://github.com/kd-011/hotend-agent): source of the agent Hotend puts on your printer's host.

## Homelab and dev tools

- [unlisted](https://github.com/kd-011/unlisted): finds what your homelab exposes that you never wrote down.
- [restore-drill](https://github.com/kd-011/restore-drill): restores your newest backup into a temp dir, checks it and tells you when it fails.
- [worktree-preview](https://github.com/kd-011/worktree-preview): starts the dev server for a git worktree on its own free port and stops only what it started.
- [dossier-scribe](https://github.com/kd-011/dossier-scribe): tells you which sentence in your docs to recheck when the file it cites changes.

## For fun

- [party-games](https://github.com/kd-011/party-games): free party and drinking games for adults in one room, played on phones with no app.

## Learning to code

I'm working through Python first, then JavaScript and Go, since that's what most of the above is written in. If you spot something in my code that a beginner shouldn't copy, an issue is welcome.
