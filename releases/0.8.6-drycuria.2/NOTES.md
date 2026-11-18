Basada en **Foundry VTT MCP Bridge v0.8.6** (upstream). Fase 1: compendios.

### Novedades
- **`manage-compendiums`**: listar compendios; ver el contenido **completo** de uno, paginado y con la carpeta de cada entrada; crear, configurar (bloqueo, permisos, carpeta de la barra lateral) y borrar.
- **`manage-compendium-entries`**: leer, crear, editar, mover y borrar entradas por ID.
- **`manage-folders`**: carpetas **dentro** de compendios (parámetro `pack`) y carpetas de compendios en la barra lateral (tipo `Compendium`).
- **`transfer-documents`**: del mundo a un compendio y al revés, copiando o moviendo, por IDs o por carpetas enteras, conservando el árbol de carpetas.
- **`manage-documents`**: borrar y renombrar cualquier documento del mundo.
- **`export-document` / `import-document`**: documentos completos a JSON y de vuelta.

### Seguridad
- Nuevo ajuste **Allow Delete Operations**, **desactivado por defecto**. Todo lo que borra lo necesita, además de *Allow Write Operations*.
- Solo se pueden modificar los compendios del mundo (`world.*`).
- Los compendios bloqueados solo se modifican si se pide desbloquearlos expresamente, y se vuelven a bloquear siempre al terminar.

### Instalación
- **Foundry:** actualiza el módulo desde la pantalla de configuración. El manifest es el mismo.
- **Servidor (PC):** sustituye `index.cjs` y `backend.bundle.cjs` por los de `foundry-mcp-server-0.8.6-drycuria.2.zip`.
