# skills-publicas

Indice **publico** de referencia de las skills de OpenCode de [gilmanpro](https://github.com/gilmanpro) con repositorio publico. Cada skill vive en su **propio repo**; aqui solo la ficha y el enlace.

| Skill | Que hace | Repo |
|---|---|---|
| qwen-tools | Todo QwenCloud en una skill: voz TTS, transcripcion ASR, imagenes y video generativos, busqueda web e interprete de codigo | [gilmanpro/qwen-tools](https://github.com/gilmanpro/qwen-tools) |
| skill-creator | Crear, validar y mejorar skills de OpenCode con evals medibles y auditoria anti-skill-maliciosa | [gilmanpro/skill-creator](https://github.com/gilmanpro/skill-creator) |
| ofimatica | Super skill de ofimatica: Word, PowerPoint, PDF, Excel, Markdown, pandoc, Obsidian y CV | [gilmanpro/ofimatica](https://github.com/gilmanpro/ofimatica) |
| mcp-builder | Crear, redisenar y asegurar servidores MCP en Python (FastMCP) o TypeScript | [gilmanpro/mcp-builder](https://github.com/gilmanpro/mcp-builder) |
| gestor-agentes | Crear, editar, validar y migrar agentes y subagentes de OpenCode y otros arneses | [gilmanpro/gestor-agentes](https://github.com/gilmanpro/gestor-agentes) |
| instalador-mcp | Instalar y dejar operativos servidores MCP en 14 arneses con verificacion JSON-RPC | [gilmanpro/instalador-mcp](https://github.com/gilmanpro/instalador-mcp) |
| mcp-ahorro-tokens | Activar y desactivar servidores MCP de OpenCode bajo demanda para ahorrar tokens | [gilmanpro/mcp-ahorro-tokens](https://github.com/gilmanpro/mcp-ahorro-tokens) |
| conector-modelos | Conectar proveedores y modelos de IA en cualquier arnes de agentes | [gilmanpro/conector-modelos](https://github.com/gilmanpro/conector-modelos) |
| computer-use-py | Controlar el escritorio multi-OS (Windows/Linux/macOS) con dispatch por proceso | [gilmanpro/computer-use-py](https://github.com/gilmanpro/computer-use-py) |
| graphic-media | Dibujos, graficos y visualizaciones con Python: diagramas, SVG, arte, video y audio | [gilmanpro/graphic-media](https://github.com/gilmanpro/graphic-media) |

**Indice de las skills privadas**: [skills-privadas](https://github.com/gilmanpro/skills-privadas) (requiere acceso).

## Instalacion

```bash
cmdc skills add gilmanpro/<nombre> -g
```

o copia la carpeta del repo a `~/.agents/skills/<nombre>/` (global) o `<proyecto>/.opencode/skills/<nombre>/`.

## Verificacion

```bash
python skill-creator/scripts/quick_validate.py <nombre>
python skill-creator/scripts/auditar_seguridad.py <nombre>
```
