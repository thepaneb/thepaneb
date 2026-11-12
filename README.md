<h1 align="center">Gil Cleber Barboza</h1>

<p align="center">
  <b>Software architect</b> · Oracle &amp; PL/SQL tooling · payment systems
</p>

<p align="center">
  Sorocaba, Brazil ·
  <a href="https://thepaneb.github.io/">Projects</a> ·
  <a href="https://www.linkedin.com/in/gilcleber/">LinkedIn</a> ·
  <a href="https://twitter.com/the_paneb">X</a>
</p>

---

I build developer tools for teams that run **Oracle in production**.

Most of my work sits between the database and the editor: making PL/SQL
testable, observable and debuggable without leaving VS Code.

## Currently building

### [utPLSQL Test Runner](https://marketplace.visualstudio.com/items?itemName=paneb.vscode-utplsql) for VS Code

<p>
  <a href="https://marketplace.visualstudio.com/items?itemName=paneb.vscode-utplsql"><img alt="Marketplace version" src="https://vsmarketplacebadges.dev/version-short/paneb.vscode-utplsql.svg"></a>
  <a href="https://github.com/thepaneb/vscode-utplsql/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/thepaneb/vscode-utplsql/actions/workflows/ci.yml/badge.svg?branch=main"></a>
  <a href="https://github.com/thepaneb/vscode-utplsql/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/thepaneb/vscode-utplsql?color=green"></a>
</p>

A native **Test Explorer** for utPLSQL suites, written in TypeScript on top of
`node-oracledb`. Run, debug and measure coverage of PL/SQL tests without Java
or Instant Client in thin mode.

- **Native Test Explorer** — suites organized by file, schema or `%tags`, with smart re-run and jump-to-failure
- **Coverage that points to your source** — Cobertura mapped back to `.pks` / `.pkb`, with inline decorations
- **PL/SQL debugger** — breakpoints, stepping, variables and call stack through `DBMS_DEBUG`
- **Oracle-direct execution** — `ut_runner.run` via node-oracledb, with real-time output
- **24 UI languages** — the interface follows your VS Code language

`TypeScript` · `node-oracledb` · `Oracle 12.1+` · `MIT` · independent community project

<p align="center">
  <a href="https://raw.githubusercontent.com/thepaneb/vscode-utplsql/main/images/marketplace-run.gif">
    <img src="https://raw.githubusercontent.com/thepaneb/vscode-utplsql/main/images/marketplace-test-explorer.png" alt="VS Code Test Explorer showing utPLSQL suites and tests, with Run and Run with Coverage CodeLens" width="100%">
  </a>
</p>

<p align="center"><sub>Native Test Explorer — click the image for the demo</sub></p>

[Marketplace](https://marketplace.visualstudio.com/items?itemName=paneb.vscode-utplsql) ·
[Documentation](https://github.com/thepaneb/vscode-utplsql/wiki) ·
[Website](https://thepaneb.github.io/vscode-utplsql/) ·
[Releases](https://github.com/thepaneb/vscode-utplsql/releases)

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| **[isis-report-lib](https://thepaneb.github.io/isis-report-lib/)** | Python library for tabular PDF reports with hierarchical layouts, published on [PyPI](https://pypi.org/project/isis-report-lib/) | Python · Jinja2 · Playwright |
| **[isis_report](https://thepaneb.github.io/isis-report/)** | Async microservice that renders PDF reports from customizable hierarchical layouts | Python · Robyn |
| **[Samsung Remote](https://thepaneb.github.io/samsung-remote/)** | Desktop and Android app to control Samsung (Tizen) TVs over the local network, with SmartThings as a fallback | Rust · Tauri 2 · TypeScript |
| **[My Tuya Home](https://thepaneb.github.io/my-tuya-home/)** | Self-hosted dashboard for Tuya/SmartLife smart plugs with live energy, cascade totals and a native Flet app | Python · Flask · Flet |
| **[base_flask](https://thepaneb.github.io/base-flask/)** | Flask workspace template with VS Code Dev Containers | Python · Docker |
| **[base_robyn](https://thepaneb.github.io/base-robyn/)** | Robyn workspace template with VS Code Dev Containers | Python · Docker |
| **[utPLSQL](https://github.com/thepaneb/utPLSQL)** | Personal fork of the utPLSQL testing framework | PL/SQL |

The full project hub, with a landing page for each public project, is at
**[thepaneb.github.io](https://thepaneb.github.io/)**.

## Writing

Notes on building Oracle and PL/SQL tooling, published on LinkedIn:

- [A native Test Explorer for utPLSQL](https://www.linkedin.com/feed/update/urn:li:share:7522375845034999808/)
- [Run tests from CodeLens, without leaving the editor](https://www.linkedin.com/feed/update/urn:li:share:7523750972209348608/)
- [PL/SQL coverage inside VS Code](https://www.linkedin.com/feed/update/urn:li:share:7524923525288357889/)
- [Inline pass/fail results on the test line](https://www.linkedin.com/feed/update/urn:li:share:7525314380956135424/)

Release notes and the full history live in the [changelog](https://github.com/thepaneb/vscode-utplsql/blob/main/CHANGELOG.md).

## Toolbox

`TypeScript` · `Python` · `Rust` · `Tauri 2` · `PL/SQL` · `Oracle Database` ·
`node-oracledb` · `Robyn` · `Flask` · `Flet` · `Docker` · `GitHub Actions` · `VS Code API`

## What I care about

- Tests that run where the code runs — close to the database, not in a separate harness.
- Tooling that fails loudly and explains itself.
- Documentation that stays true to the code.

---

<p align="center">
  <sub>
    Open to conversations about Oracle developer tooling, PL/SQL testing and developer experience.
    The fastest way to reach me is <a href="https://www.linkedin.com/in/gilcleber/">LinkedIn</a>.
  </sub>
</p>
