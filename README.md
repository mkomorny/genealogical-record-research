# Genealogical Record Census Disambiguator

Analyzes historical parish registers, census transcripts, and archived land deeds to reconcile conflicting dates, locations, and lineage branches across family records. Use when the user wants genealogy conflict resolution, census household matching, parish register analysis, same-name disambiguation, lineage branch reconciliation, or "are these the same person." Typical triggers include messy family trees, conflicting DOBs/places, and deed/census crosswalks.

**Type:** Custom Grok agent  
**Compatible with:** Grok Build (native). Also usable as a subagent prompt in Claude Code and similar tools.

## Install

### Grok Build
Copy `agents/genealogical-record-census-disambiguator.md` to `~/.grok/agents/` then reload agents (`/agents` or a new session).

### Other coding agents
Treat `agents/genealogical-record-census-disambiguator.md` as a custom subagent prompt. Drop it into the agent folder your tool uses (for example `.claude/agents/` or a plugin `agents/` directory).

## Files

- `agents/genealogical-record-census-disambiguator.md` — agent prompt (YAML frontmatter + instructions)

## License

MIT © Miranda Komorny
