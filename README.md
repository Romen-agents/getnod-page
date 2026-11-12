# GetNod page

This repository holds one file: `getnod-page.html`, the private page that the [GetNod plugin for Claude](https://github.com/Romen-agents/getnod) publishes in a person's own Claude account when they say "Install GetNod" in a Claude project.

The plugin downloads this file at installation from a fixed commit of this repository and checks its SHA-256 checksum before publishing it, so the page a person gets is exactly the one published here. The page has no data in it, loads nothing from outside and makes no network calls of its own; its records live only in the database of the page in the person's own Claude account.

Website: https://getnodagents.com · Support: hello@getnodagents.com
