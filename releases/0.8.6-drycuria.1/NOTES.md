Basada en **Foundry VTT MCP Bridge v0.8.6** (upstream).

### Cambios respecto al original
- Nueva herramienta `manage-folders` para listar, crear, borrar y mover documentos entre carpetas: actores, objetos, escenas, journals, tablas, playlists, macros y cartas.
- `list-characters`, `list-scenes` y `list-journals` devuelven la carpeta de cada documento.
- *Allow Write Operations* se respeta también en el CRUD genérico de actores y objetos.

### Instalación
- **Foundry:** se instala o actualiza desde el manifest `https://github.com/Marc-Monegal/foundry-vtt-mcp-dist/releases/latest/download/module.json`
- **Servidor (PC):** cierra Claude Desktop y sustituye `index.cjs` y `backend.bundle.cjs` en `%LOCALAPPDATA%\FoundryMCPServer\foundry-mcp-server\packages\mcp-server\dist\` por los de `foundry-mcp-server-0.8.6-drycuria.1.zip`.
