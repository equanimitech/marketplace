# equanimitech marketplace

Claude Code plugins for the equanimitech instruments. Each instrument lives in its own repo.

```
claude plugin marketplace add equanimitech/marketplace
claude plugin install oliba@equanimitech
```

| plugin | what it does | repo |
|---|---|---|
| `oliba` | agent-native spaced repetition: map a topic, learn it one piece at a time, keep it | [equanimitech/oliba](https://github.com/equanimitech/oliba) |
| `zenborg` | the garden: fences, gap practice, activity log, garden skills | [equanimitech/zenborg](https://github.com/equanimitech/zenborg) (`plugin/`) |
| `attently` | adaptive granularity: verdict at a glance, working one click away | [equanimitech/attently](https://github.com/equanimitech/attently) |
| `murmur` | macOS voice memos to local markdown transcripts; sync and review | [equanimitech/murmur](https://github.com/equanimitech/murmur) |

## Adding an instrument

Add an entry to `.claude-plugin/marketplace.json` pointing at the instrument's repo. Use HTTPS or `github` sources so anyone can install without an SSH key.
