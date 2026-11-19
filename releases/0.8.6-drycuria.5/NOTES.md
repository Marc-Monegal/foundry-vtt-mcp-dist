## 0.8.6-drycuria.5

- New tool `relink-references`: rewrites compendium UUID prefixes in bulk inside world packs (including embedded items, effects and pages). Dry run by default; `reportPrefix` reports references still left.
- `transfer-documents` (to-pack): the report now pairs each created entry with its real source id.

Update the module in Foundry, then replace `index.cjs` and `backend.bundle.cjs` in the MCP server folder with the ones from `foundry-mcp-server-0.8.6-drycuria.5.zip`.
