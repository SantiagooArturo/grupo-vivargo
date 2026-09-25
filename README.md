# Full Day · Claude e IA para el trabajo · Grupo Vivargo

Adaptación del Full Day de MyWorkIn (edición del 23 de agosto) a Grupo Vivargo.

| Carpeta / archivo | Qué es |
|---|---|
| `index.html` + `FullDay_P1…P8_*.html` | Las 8 presentaciones y su índice. Abrir `index.html`. |
| `media/logo_vivargo.svg` | Logo de Vivargo (blanco). Para cambiarlo, reemplazar este archivo con el mismo nombre. |
| `Project_Comercial_Alquiler/` | Project completo para subir a Claude: instrucciones (`00_`) y 6 documentos de conocimiento. |
| `Skills/*.skill` | Skills listas para subir: `cotizar-alquiler-equipo` y `revisar-riesgos-izaje`. |
| `demos/` | Archivos de práctica para las demos (datos ficticios). Los que empiezan con `_instructor` no se comparten. |
| `build/` | Herramientas: `fd_qa.py` (QA y capturas) y el brief usado para adaptar los decks. |

**Datos:** todo lo que es flota, tarifas, clientes y condiciones es **ficticio**. Los datos
reales de Vivargo que se usan (1948 Arequipa, 3 líneas de negocio, países, valores) salen
de vivargo.com.

**Para publicar** (Netlify/Vercel): subir la carpeta sin `build/`, `Project_Comercial_Alquiler/`,
`Skills/` ni `demos/_instructor*`.
