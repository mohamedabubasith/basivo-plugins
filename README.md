# Basivo plugins for Claude Code

One marketplace for all Basivo plugins.

| Plugin | What it does |
|---|---|
| [basivo-qa](https://github.com/mohamedabubasith/basivo-qa) | Tests your web app in a real browser and hands Claude a verdict it can fix from, in the same session. |
| [basivo-operator](https://github.com/mohamedabubasith/basivo-operator) | Does plain-language tasks on any website inside your own logged-in browser. Draft-first, asks before anything irreversible. |
| [basivo-journal](https://github.com/mohamedabubasith/basivo-journal) | Your memory and activity journal: every session saved to your private repo, memory search, offline report and dashboard. |
| [basivo-memory](https://github.com/mohamedabubasith/basivo-memory) | Shared memory across related repos: a spec/rules repo and a code repo in one space. |
| [basivo-studio](https://github.com/mohamedabubasith/basivo-studio) | Logos, icons, favicons, covers and social images, designed in SVG/HTML and rendered to exact-size PNGs. |

## Install

Add the marketplace once:

```
claude plugin marketplace add mohamedabubasith/basivo-plugins
```

Then install what you need:

```
claude plugin install basivo-qa@basivo
claude plugin install basivo-operator@basivo
claude plugin install basivo-journal@basivo
claude plugin install basivo-memory@basivo
claude plugin install basivo-studio@basivo
```

Inside a Claude Code session the same commands work as `/plugin marketplace add …` and `/plugin install …`.

## Update

```
claude plugin marketplace update basivo
```

Each plugin's version comes from its own repo, so a new release there is picked up on update.

---

Made by [Basivo](https://basivo.in).
