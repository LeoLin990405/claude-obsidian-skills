# Claude Obsidian Skills

Obsidian note-taking toolkit for Claude Code - Obsidian Flavored Markdown, Bases database views, and JSON Canvas editing.

## Overview

This skill collection enables Claude Code to work with Obsidian-specific formats, including wikilinks, callouts, properties, and the new Bases feature.

## Skills Included

| Skill | Description |
|-------|-------------|
| `obsidian-markdown` | Obsidian Flavored Markdown with wikilinks, embeds, callouts |
| `obsidian-bases` | Obsidian Bases database views |
| `json-canvas` | JSON Canvas file editing |

## Installation

```bash
cd ~/.claude/skills
git clone https://github.com/LeoLin990405/claude-obsidian-skills.git
```

## Usage

```
/obsidian-markdown  # Create Obsidian-style notes
/obsidian-bases     # Work with Bases database views
/json-canvas        # Edit canvas files
```

## Features

- **Obsidian Markdown**: Wikilinks `[[note]]`, embeds `![[image]]`, callouts, frontmatter properties, tags
- **Bases**: Database views, filters, sorts, formulas
- **JSON Canvas**: Visual canvas editing, node connections

## License

MIT License - see [LICENSE](LICENSE) for details.
