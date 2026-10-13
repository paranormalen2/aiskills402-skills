# AISkills402 — free sample skills

Three tested agent skills (Agent Skills format, `SKILL.md`) from [aiskills402.com](https://aiskills402.com), free to use.

| Skill | What it does | Test report |
|---|---|---|
| [translate-app-text](skills/translate-app-text/SKILL.md) | Translates locale files (JSON, YAML, PO, ICU) without breaking keys, placeholders or plurals | [tests](https://aiskills402.com/skills/translate-app-text/tests) |
| [spreadsheet-formula](skills/spreadsheet-formula/SKILL.md) | Writes one Excel or Google Sheets formula from a description and a sample of the sheet | [tests](https://aiskills402.com/skills/spreadsheet-formula/tests) |
| [mcp-tool-schema](skills/mcp-tool-schema/SKILL.md) | Writes the MCP tool definition (inputSchema, annotations) for one API operation | [tests](https://aiskills402.com/skills/mcp-tool-schema/tests) |

Each skill was run on a strong and a weak model, with and without the skill, on cases fixed before the run. The test report says where it helps and where it does not.

## Install

```bash
npx skills add paranormalen2/aiskills402-skills
```

or straight from the site (Agent Skills discovery):

```bash
npx skills add https://aiskills402.com
```

## License

Free sample. Use it and change it in your own agents and projects, including paid work for clients. Do not resell it or republish it as your own. The full text is the License section at the end of each `SKILL.md`. © 2026 Georgi Kalchev, aiskills402.com.

The files here are copies; the source is https://aiskills402.com/.well-known/agent-skills/index.json. More tested skills, bought once over x402: https://aiskills402.com/skills
