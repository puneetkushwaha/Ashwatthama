<div align="center">
  <img src="public/logo.png" alt="Ashwatthama" width="120">
  <h1>Ashwatthama IDE</h1>
  <p>The next-generation, high-performance desktop code editor built with Tauri (Rust and React), equipped with native speed, local AI models, Git integration, and vim keybindings.</p>
</div>

## Features

- **Local & Cloud AI Agents**: Integrated support for local Ollama models (Qwen 2.5 Coder 7B, DeepSeek Coder 6.7B), Google Antigravity Engine, Claude Code, and OpenAI Codex.
- **Blazing Performance**: Native Rust desktop architecture powered by Tauri and optimized web technologies.
- **Git & GitHub Integration**: Seamless branch management, diffs, commits, and pull requests directly in-editor.
- **Modern Developer Tooling**: LSP support, rich syntax highlighting, integrated terminal, database viewers, and full vim keybindings.
- **Beautiful & Customizable**: Minimalist, distraction-free interface with light and dark themes.

## Getting Started

### Prerequisites

- [Node.js 22+](https://nodejs.org)
- [Bun](https://bun.sh)
- [Rust](https://rustup.rs)

### Clone & Run

```bash
git clone https://github.com/puneetkushwaha/Ashwatthama.git
cd Ashwatthama
bun install
bun dev
```

### Build for Production

```bash
bun run build:stable
```

## Website

The Ashwatthama official website code is located under `website/`. To run it locally:

```bash
node website/serve.cjs
```
Visit: [http://localhost:3000](http://localhost:3000)

## Contributing

Contributions are welcome! Please check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the GNU Affero General Public License v3.0.
