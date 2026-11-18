Basada en **Foundry VTT MCP Bridge v0.8.6** (upstream). Fase 2: duplicados y comparación. Incluye también todo lo de la fase 1 (0.8.6-drycuria.2).

### Novedades
- **`find-duplicates`**: busca duplicados de un tipo de documento en el mundo y en los compendios, por nombre (sin distinguir mayúsculas ni acentos) y/o por identificador. Con `compareContent` distingue las copias idénticas de las que han cambiado.
- **`compare-documents`**: compara dos documentos, del mundo o de compendios, y dice qué campos cambian y qué objetos o efectos sobran o faltan en cada uno.

Las dos herramientas son de solo lectura.

### Instalación
- **Foundry:** actualiza el módulo desde la pantalla de configuración.
- **Servidor (PC):** sustituye `index.cjs` y `backend.bundle.cjs` por los de `foundry-mcp-server-0.8.6-drycuria.3.zip`.
