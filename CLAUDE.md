# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Netlas.io featured search queries (dorks) for OSINT/reconnaissance. A curated collection of search dorks adapted from RedTeamGuide to Netlas query syntax.

## Structure

Single-file documentation repo: `README.md` contains all dorks organized into categories:
- General Searches, IoT/Routers, Security Applications, Web Cameras
- Communication, Remote Access, VoIP, Storages/Databases
- Web Services, Dev/Monitoring, Other
- CVE sections (2023, 2024 notable vulnerabilities)

## Dork Syntax Conventions

- **Tag-based dorks**: `tag.name:"vendor"` or `tag.category:"category"` (requires Business subscription)
- **Alternative dorks**: Provided without tags using `http.favicon.hash_sha256:...` for free-tier users
- **Search links**: Point to `app.netlas.io/responses/?q=...` or short URLs `nt.ls/...`
- **Operators**: `AND`, `OR`, `NOT`; ranges `[A TO B]`; wildcards `*`
- **Field prefixes**: `http.title`, `http.body`, `http.headers.server`, `http.favicon.hash_sha256`, `protocol`, `port`, `prot7`, `certificate.*`, `geo.*`, `asn.*`

## Contributing

PRs and issues welcome for accuracy corrections or new dorks. Follow existing markdown formatting: bold name, link with `&emsp;`, code block with query.
