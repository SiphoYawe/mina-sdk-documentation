<p align="center">
  <img src="./images/mina-sdk-logo-dark.png" alt="Mina SDK" width="200" />
</p>

<h1 align="center">Mina SDK Documentation</h1>

<p align="center">
  <strong>Official documentation for @siphoyawe/mina-sdk</strong>
</p>

<p align="center">
  <a href="https://mina-169e3f09.mintlify.app/">View Live Documentation</a> •
  <a href="https://github.com/siphoyawe/mina-sdk">SDK Repository</a> •
  <a href="https://www.npmjs.com/package/@siphoyawe/mina-sdk">npm Package</a>
</p>

---

## About

This repository contains the documentation for **Mina SDK** — a TypeScript SDK for cross-chain bridging to Hyperliquid. The documentation is built with [Mintlify](https://mintlify.com).

**What Mina SDK does:**
- Bridge assets from 40+ EVM chains to Hyperliquid
- Automatic deposit to Hyperliquid L1 trading account
- Production-ready React hooks
- Full TypeScript support

## Documentation Structure

```
├── index.mdx              # Landing page
├── installation.mdx       # Installation guide
├── quickstart.mdx         # Quick start tutorial
├── configuration.mdx      # Configuration options
│
├── concepts/              # Core concepts
│   ├── chains.mdx         # Supported chains
│   ├── tokens.mdx         # Token handling
│   ├── quotes.mdx         # Quote system
│   ├── execution.mdx      # Transaction execution
│   ├── auto-deposit.mdx   # Auto-deposit to L1
│   └── slippage.mdx       # Slippage settings
│
├── api/                   # API reference
│   ├── mina.mdx           # Mina class
│   ├── services/          # Service modules
│   ├── types/             # TypeScript types
│   ├── events.mdx         # Event system
│   ├── errors.mdx         # Error handling
│   └── constants.mdx      # SDK constants
│
├── react/                 # React integration
│   ├── installation.mdx   # React setup
│   ├── provider.mdx       # MinaProvider
│   └── hooks/             # React hooks
│
├── advanced/              # Advanced usage
│   ├── caching.mdx        # Custom caching
│   ├── custom-rpcs.mdx    # RPC configuration
│   └── standalone.mdx     # Standalone functions
│
└── examples/              # Code examples
    ├── simple-bridge.mdx
    ├── full-integration.mdx
    └── ...
```

## Local Development

### Prerequisites

- Node.js 18+
- npm, yarn, pnpm, or bun

### Install Mintlify CLI

```bash
npm i -g mintlify
```

### Run Development Server

```bash
mintlify dev
```

Open [http://localhost:3000](http://localhost:3000) to view the docs locally.

### Troubleshooting

If your dev environment isn't running:

```bash
mintlify update
```

## Contributing

### Adding or Editing Pages

1. Create or edit `.mdx` files in the appropriate directory
2. Update `docs.json` navigation if adding new pages
3. Run `mintlify dev` to preview changes

### Writing Guidelines

- Use clear, concise language
- Include code examples for all API methods
- Add TypeScript types for all examples
- Test all code snippets before committing

### Page Frontmatter

```mdx
---
title: "Page Title"
description: "Brief description for SEO"
---
```

## Deployment

Changes pushed to the `main` branch are automatically deployed via the Mintlify GitHub integration.

## Links

| Resource | URL |
|----------|-----|
| Live Docs | [mina-169e3f09.mintlify.app](https://mina-169e3f09.mintlify.app/) |
| SDK Repository | [github.com/siphoyawe/mina-sdk](https://github.com/siphoyawe/mina-sdk) |
| npm Package | [@siphoyawe/mina-sdk](https://www.npmjs.com/package/@siphoyawe/mina-sdk) |
| Hyperliquid | [hyperliquid.xyz](https://hyperliquid.xyz) |

## License

MIT License - see [LICENSE](LICENSE) for details.
