<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YounndAI/yon-vscode/main/assets/yon-icon-ondark.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YounndAI/yon-vscode/main/assets/yon-icon-onlight.png" />
    <img alt="YON" src="https://raw.githubusercontent.com/YounndAI/yon-vscode/main/assets/yon-icon-onlight.png" width="80" />
  </picture>
</p>

<p align="center">
  <strong>YON™ for Visual Studio Code</strong><br />
  Syntax highlighting, snippets, and language support for YON™<br />
  <em>Part of the YON™ toolchain — data, intent, and instructions in a single stream.</em>
</p>

<p align="center">
  <a href="https://yon.younndai.com">Website</a> · <a href="https://github.com/YounndAI/yon-spec">Specification</a> · <a href="./LICENSE">Apache 2.0</a> · <a href="./TRADEMARK.md">Trademark Policy</a> · <a href="https://github.com/YounndAI/brand">Brand Assets</a>
</p>

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/YounndAI.yon?style=flat-square&color=0d0d0d)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/YounndAI.yon?style=flat-square&color=0d0d0d)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

---

## Features

### Syntax Highlighting

Full TextMate grammar covering all YON v2.0 constructs:

- **Document headers** — `@DOC` declarations with metadata attributes
- **Sections** — `@SEC` with `name`, `parent`, and attributes
- **Tags** — `@NOTE`, `@RULE`, `@STEP`, `@MAP`, `@INTENT`, and all standard tags
- **Typed fields** — `count:int=42`, `active:bool=true`, `ratio:float=3.14`
- **Structured values** — strings, lists `[a, b, c]`, maps `["key"->"value"]`, references `§ref`
- **Comments** — line `# ...` and inline

### Embedded Language Blocks

70+ languages highlighted inside `@BEGIN`/`@END` blocks:

```
@BEGIN lang=typescript
const greeting: string = "Hello, YON";
@END
```

Supported: TypeScript, JavaScript, JSON, Python, Rust, Go, Java, C/C++, C#, Ruby, PHP, SQL, YAML, TOML, Markdown, HTML, CSS, Shell, PowerShell, Dockerfile, Terraform, GraphQL, Protocol Buffers, Prisma, and more.

### Snippets

Quickly scaffold YON documents with built-in snippets for common patterns.

### File Icon

`.yon` files display a dedicated icon in the VS Code explorer.

### Language Configuration

- Comment toggling (`Ctrl+/`)
- Bracket matching and auto-closing
- Folding on `@SEC`, `@BEGIN`/`@END` blocks

---

## What is YON?

**YON** (YounndAI Object Notation) is a structured data format that bridges human readability with machine precision. It's designed for:

- **AI agent instructions** — structured prompts, tool definitions, and workflows
- **Configuration** — type-safe settings with validation semantics
- **Domain modeling** — schemas, rules, and cross-references
- **Documentation** — technical specs that compile into executable artifacts

Learn more at [yon.younndai.com](https://yon.younndai.com).

---

## Requirements

- Visual Studio Code `1.85.0` or later

## Links

- [YON Standard & Documentation](https://yon.younndai.com)
- [Source Code](https://github.com/YounndAI/yon-vscode)
- [YON Parser (npm)](https://www.npmjs.com/package/@younndai/yon-parser)
- [YounndAI](https://younndai.com)

---

## License & Attribution

Apache-2.0. © 2026 MARLINK TRADING SRL (YounndAI). See [`LICENSE`](./LICENSE) and [`NOTICE`](./NOTICE).

"YON" and "YounndAI" are trademarks of MARLINK TRADING SRL — see [`TRADEMARK.md`](./TRADEMARK.md).

Created by [Alexandru Mareș](https://allemaar.com).

Website: [yon.younndai.com](https://yon.younndai.com)

<p align="center"><em>Structure before scale. Harmony above all.</em></p>

---

|               |                                                         |
| ------------- | ------------------------------------------------------- |
| **Spec**      | [YON v2.0](https://yon.younndai.com)                    |
| **Author**    | [Alexandru Mareș](https://allemaar.com)                 |
| **Company**   | [MARLINK TRADING SRL](https://younndai.com) · YounndAI™ |
| **License**   | [Apache 2.0](./LICENSE) — © 2026 MARLINK TRADING SRL    |
| **Trademark** | [YounndAI™ Trademark Guidelines](./TRADEMARK.md)        |

_Structure before scale._
