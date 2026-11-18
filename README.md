# Foundry VTT MCP Bridge — Drycuria build

Compiled releases of a customised build of [Foundry VTT MCP Bridge](https://github.com/adambdooley/foundry-vtt-mcp) by Adam Dooley (MIT). This repository only hosts the release files so Foundry can install and update the module. The source lives in a private repository.

**Manifest URL** (Foundry → Add-on Modules → Install Module):
```
https://github.com/Marc-Monegal/foundry-vtt-mcp-dist/releases/latest/download/module.json
```

Each release contains:
- `foundry-vtt-mcp.zip` and `module.json`: the Foundry module.
- `foundry-mcp-server-<version>.zip`: the MCP server files (`index.cjs`, `backend.bundle.cjs`) for an existing Claude Desktop install.

Changes from upstream: folder support (`manage-folders`, folder paths in listings) and *Allow Write Operations* enforced on generic actor/item CRUD.
