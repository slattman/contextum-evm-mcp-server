# Contextum EVM MCP Server

This is the Contextum EVM Model Context Protocol (MCP) server built with Bun and TypeScript.

---

## Development

Run the server locally:

```bash
bun run dev
```

---

## The server runs on http://localhost:8787.

## Visit http://localhost:8787/context to test the server response.

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ContextumAI/contextum-evm-mcp-server.git
cd contextum-evm-mcp-server
```
2. Install dependencies using Bun:
```bash
bun install
```
or using npm:
```bash
npm install
```

---

## Configuration

- Default server port is `8787`.  
- To change it, edit `src/server/http-server.ts` and update the port number.

- Supported chains and their RPC URLs are defined in `src/core/chains.ts`.

---

## Usage

Run server in development mode (auto reload on code changes):

```bash
bun run dev
```
Run server in production mode:
```bash
bun start
```

---

## Testing

Open your browser or use curl to test:

```bash
curl http://localhost:8787/context
```

---

## License
This project is licensed under the MIT License.

---

# Contributing to Contextum

Thank you for your interest in contributing to Contextum! 🚀

We welcome help with:
- Bug fixes
- Feature proposals
- Protocol improvements
- Documentation
- Smart contract review

## 🛠 How to Contribute

1. **Fork** the repo
2. **Clone** to your local machine
3. Create a new branch: `git checkout -b my-feature`
4. Make your changes
5. Commit and push: `git push origin my-feature`
6. Create a Pull Request

## Communication

- Open an issue for discussions or proposals
- Join the conversation (coming soon: Discord/Telegram)
- Email: [founders@contextum.org](mailto:founders@contextum.org)

## Code Style

- TypeScript: follow standard formatting
- Commit messages: use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- Smart contracts: comment everything; assume others will read it

## Security

If you discover a vulnerability, please email us directly at [founders@contextum.org](mailto:founders@contextum.org) — **do not file a public issue**.

---

Thank you for helping build the decentralized AI infrastructure of the future.
