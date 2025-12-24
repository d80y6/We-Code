<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=aicodeforyou"><img src="https://img.shields.io/badge/VS_Code_Marketplace-007ACC?style=flat&logo=visualstudiocode&logoColor=white" alt="VS Code Marketplace"></a>
  <a href="https://x.com/aicodeforyou"><img src="https://img.shields.io/badge/aicodeforyou-000000?style=flat&logo=x&logoColor=white" alt="X"></a>
  <a href="https://youtube.com/@aicodeforyou?feature=shared"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="https://discord.gg/aicodeforyou"><img src="https://img.shields.io/badge/Join%20Discord-5865F2?style=flat&logo=discord&logoColor=white" alt="Join Discord"></a>
  <a href="https://www.reddit.com/a/aicodeforyou/"><img src="https://img.shields.io/badge/Join%20r%2Faicodeforyou?style=flat&logo=reddit&logoColor=white" alt="Join a/aicodeforyou"></a>
</p>
<p align="center">
  <em>Get help fast → <a href="https://discord.gg/aicodeforyou">Join Discord</a> • Prefer async? → <a href="https://www.reddit.com/a/aicodeforyou/">Join a/aicodeforyou</a></em>
</p>

# AICodeForYou

> Your AI-Powered Dev Team, Right in Your Editor

<details>
  <summary>🌐 Available languages</summary>

- [English](README.md)
- [Català](locales/ca/README.md)
- [Deutsch](locales/de/README.md)
- [Español](locales/es/README.md)
- [Français](locales/fr/README.md)
- [हिंदी](locales/hi/README.md)
- [Bahasa Indonesia](locales/id/README.md)
- [Italiano](locales/it/README.md)
- [日本語](locales/ja/README.md)
- [한국어](locales/ko/README.md)
- [Nederlands](locales/nl/README.md)
- [Polski](locales/pl/README.md)
- [Português (BR)](locales/pt-BR/README.md)
- [Русский](locales/ru/README.md)
- [Türkçe](locales/tr/README.md)
- [Tiếng Việt](locales/vi/README.md)
- [简体中文](locales/zh-CN/README.md)
- [繁體中文](locales/zh-TW/README.md)
- ...
      </details>

---

## What Can AICodeForYou Do?

- Generate Code from natural language descriptions and specs
- Adapt with Modes: Code, Architect, Ask, Debug, and Custom Modes
- Refactor & Debug existing code
- Write & Update documentation
- Answer Questions about your codebase
- Automate repetitive tasks
- Utilize MCP Servers

## Modes

AICodeForYou adapts to how you work:

- Code Mode: everyday coding, edits, and file ops
- Architect Mode: plan systems, specs, and migrations
- Ask Mode: fast answers, explanations, and docs
- Debug Mode: trace issues, add logs, isolate root causes
- Custom Modes: build specialized modes for your team or workflow
- Roomote Control: Roomote Control lets you remotely control tasks running in your local VS Code instance.

Learn more: [Using Modes](https://docs.AICodeForYou.com/basic-usage/using-modes) • [Custom Modes](https://docs.AICodeForYou.com/advanced-usage/custom-modes) • [Roomote Control](https://docs.AICodeForYou.com/AICodeForYou-cloud/remote-control)

## Tutorial & Feature Videos

<div align="center">

|                                                                                                                                                                           |                                                                                                                                                                            |                                                                                                                                                                         |

</div>
<p align="center">
<a href="https://docs.AICodeForYou.com/tutorial-videos">More quick tutorial and feature videos...</a>
</p>

## Resources

- **[Documentation](https://docs.AICodeForYou.com):** The official guide to installing, configuring, and mastering AICodeForYou.
- **[YouTube Channel](https://youtube.com/@AICodeForYou?feature=shared):** Watch tutorials and see features in action.
- **[Discord Server](https://discord.gg/AICodeForYou):** Join the community for real-time help and discussion.
- **[Reddit Community](https://www.reddit.com/a/AICodeForYou):** Share your experiences and see what others are building.
- **[GitHub Issues](https://github.com/d80y6/We-Code/issues):** Report bugs and track development.
- **[Feature Requests](https://github.com/d80y6/We-Code/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop):** Have an idea? Share it with the developers.

---

## Local Setup & Development

1. **Clone** the repo:

```sh
git clone https://github.com/d80y6/We-Code.git
```

2. **Install dependencies**:

```sh
pnpm install
```

3. **Run the extension**:

There are several ways to run the AICodeForYou extension:

### Development Mode (F5)

For active development, use VSCode's built-in debugging:

Press `F5` (or go to **Run** → **Start Debugging**) in VSCode. This will open a new VSCode window with the AICodeForYou extension running.

- Changes to the webview will appear immediately.
- Changes to the core extension will also hot reload automatically.

### Automated VSIX Installation

To build and install the extension as a VSIX package directly into VSCode:

```sh
pnpm install:vsix [-y] [--editor=<command>]
```

This command will:

- Ask which editor command to use (code/cursor/code-insiders) - defaults to 'code'
- Uninstall any existing version of the extension.
- Build the latest VSIX package.
- Install the newly built VSIX.
- Prompt you to restart VS Code for changes to take effect.

Options:

- `-y`: Skip all confirmation prompts and use defaults
- `--editor=<command>`: Specify the editor command (e.g., `--editor=cursor` or `--editor=code-insiders`)

### Manual VSIX Installation

If you prefer to install the VSIX package manually:

1.  First, build the VSIX package:
    ```sh
    pnpm vsix
    ```
2.  A `.vsix` file will be generated in the `bin/` directory (e.g., `bin/we-code-<version>.vsix`).
3.  Install it manually using the VSCode CLI:
    ```sh
    code --install-extension bin/we-code-<version>.vsix
    ```

---

We use [changesets](https://github.com/changesets/changesets) for versioning and publishing. Check our `CHANGELOG.md` for release notes.

---

## Disclaimer

**Please note** that AICodeForYou does **not** make any representations or warranties regarding any code, models, or other tools provided or made available in connection with AICodeForYou, any associated third-party tools, or any resulting outputs. You assume **all risks** associated with the use of any such tools or outputs; such tools are provided on an **"AS IS"** and **"AS AVAILABLE"** basis. Such risks may include, without limitation, intellectual property infringement, cyber vulnerabilities or attacks, bias, inaccuracies, errors, defects, viruses, downtime, property loss or damage, and/or personal injury. You are solely responsible for your use of any such tools or outputs (including, without limitation, the legality, appropriateness, and results thereof).

---

## Contributing

We love community contributions! Get started by reading our [CONTRIBUTING.md](CONTRIBUTING.md).

---

## License

[Apache 2.0 © 2025 AICodeForYou.](./LICENSE)

---

