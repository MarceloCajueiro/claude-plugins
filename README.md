# cajueiro-claude-plugins

[Claude Code](https://docs.claude.com/en/docs/claude-code) plugin marketplace by
[Marcelo Cajueiro](https://cajueiro.tech). Add it once, install any plugin:

```
/plugin marketplace add MarceloCajueiro/cajueiro-claude-plugins
```

## Plugins

| Plugin | Install | What it does |
|---|---|---|
| [narrate](https://github.com/MarceloCajueiro/narrate) | `/plugin install narrate@cajueiro-plugins` | Turn a document (PDF, Markdown, HTML, text) into a narrated MP3 with Gemini TTS — chunking, retry, resume, loudness normalization. |
| [agentic-cr](https://github.com/MarceloCajueiro/agentic-cr) | `/plugin install agentic-cr@cajueiro-plugins` | Agentic code review pipeline for GitHub PRs — two independent review passes in parallel, one deduplicated PR comment, then a finding-by-finding fix pass. |

Each plugin lives in its own repository; this repo only hosts the marketplace manifest that
points to them. New plugins show up here without you having to add another marketplace.

## License

MIT © Marcelo Cajueiro — [cajueiro.tech](https://cajueiro.tech)
