# IA Generativa aplicada a la ingeniería

Material de la charla del 11 de noviembre de 2026 para el CD Ica: cómo se trabaja con un agente de IA (Claude Code) en tareas reales de ingeniería, más allá de escribir prompts.

## Qué se vio

- Claude Code y la memoria por carpeta (`CLAUDE.md`): por qué el prompt puede ser de una línea.
- Plan Mode: planificar, aprobar y recién ejecutar.
- MCP, APIs y herramientas de línea de comandos para conectar el agente con correo, calendario, nube y repositorios.
- Microsoft 365 por API (Microsoft Graph), sin abrir Office.
- Skills: procedimientos reutilizables.
- Varios agentes trabajando en paralelo y revisándose entre ellos.
- Claude in Chrome: el navegador como herramienta.
- Seguridad: qué hace solo el agente, qué pregunta y qué nunca hace.

## Material de demo

La carpeta `demo/` tiene los archivos que se usaron en vivo. **Todos los datos son inventados**: la obra, las cifras y el acta no corresponden a ningún proyecto real, y las fotos fueron generadas con IA.

| Archivo | Contenido |
|:---|:---|
| `demo/metrado.xlsx` | Metrado de la semana 45 de un pabellón de aulas: avance real contra programado por partida |
| `demo/acta-reunion-2026-11-09.md` | Acta de reunión de obra con problemas, acuerdos y pendientes |
| `demo/fotos/` | Cuatro fotos de avance de obra |
| `demo/historial/` | Doce obras terminadas (2023 a 2026) con actas, metrados e informes de cierre: hay un patrón escondido en los atrasos |
| `demo/planos/pabellon-primer-nivel.dxf` | Planta del primer nivel en DXF, para sacar el metrado de muros y compararlo con el Excel |

## Pruébalo tú

Con Claude Code instalado, abre una terminal en `demo/` y pide, por ejemplo:

```
arma el informe semanal de obra con las fotos, el metrado y el acta
```

Después prueba Plan Mode (Shift+Tab) con la misma tarea y compara.

## Autor

Mauricio Sougarret
