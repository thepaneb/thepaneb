<h1 align="center">Gil Cleber Barboza</h1>

<p align="center">
  <b>Software architect</b> · Oracle &amp; PL/SQL tooling · payment systems
</p>

<p align="center">
  Sorocaba, Brazil ·
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
  <a href="https://github.com/thepaneb/vscode-utplsql/releases"><img alt="Latest release" src="https://img.shields.io/github/v/release/thepaneb/vscode-utplsql?label=release"></a>
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

[Marketplace](https://marketplace.visualstudio.com/items?itemName=paneb.vscode-utplsql) ·
[Documentation](https://thepaneb.github.io/vscode-utplsql/) ·
[Wiki](https://github.com/thepaneb/vscode-utplsql/wiki) ·
[Releases](https://github.com/thepaneb/vscode-utplsql/releases)

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| **[isis_report](https://github.com/thepaneb/isis_report)** | Async microservice that renders PDF reports from customizable hierarchical layouts | Python · Robyn |
| **[base_flask](https://github.com/thepaneb/base_flask)** | Flask workspace template with VS Code Dev Containers | Python · Docker |
| **[base_robyn](https://github.com/thepaneb/base_robyn)** | Robyn workspace template with VS Code Dev Containers | Python · Docker |
| **[utPLSQL](https://github.com/thepaneb/utPLSQL)** | Personal fork of the utPLSQL testing framework | PL/SQL |

## Writing

Notes on building Oracle and PL/SQL tooling, published on LinkedIn:

- [A native Test Explorer for utPLSQL](https://www.linkedin.com/feed/update/urn:li:share:7522375845034999808/)
- [Run tests from CodeLens, without leaving the editor](https://www.linkedin.com/feed/update/urn:li:share:7523750972209348608/)
- [PL/SQL coverage inside VS Code](https://www.linkedin.com/feed/update/urn:li:share:7524923525288357889/)
- [Inline pass/fail results on the test line](https://www.linkedin.com/feed/update/urn:li:share:7525314380956135424/)

Release notes and the full history live in the [changelog](https://github.com/thepaneb/vscode-utplsql/blob/main/CHANGELOG.md).

## Toolbox

`TypeScript` · `Python` · `PL/SQL` · `Oracle Database` · `node-oracledb` ·
`Robyn` · `Flask` · `Docker` · `GitHub Actions` · `VS Code API`

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
