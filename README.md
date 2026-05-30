# scheherazade

A Claude Code plugin for fiction writers. Three skills work together as a
workshop:

| Skill | Role |
|---|---|
| **scheherazade** | A workshop-style coach. Shapes inquiry through prompts, lenses, and reflection — does not ghostwrite. Use whenever you are thinking aloud about a story problem, planning a scene or arc, working through a character, examining a draft, or reflecting on a creative decision. |
| **paint-a-picture** | A visualisation aid that renders a scene in Ursula K. Le Guin's voice so the writer can see it in their mind's eye. The painted prose is disposable; the imagery is what stays. Invoked directly or delegated to by scheherazade when sensory texture is the bottleneck. |
| **index-omnium** | A notes organiser for layered Markdown notes (character, faction, plot, theme, timeline, decision) with Obsidian-style `[[wiki-links]]` and a canon / tentative / exploratory / rejected status taxonomy. The writer owns the notes; the organiser is the scribe that keeps the system coherent. |

## Install

This plugin is distributed through the [RKPinata marketplace](https://github.com/RKPinata/rkpinata-plugin).

```bash
# In Claude Code:
/plugin marketplace add RKPinata/rkpinata-plugin
/plugin install scheherazade@rkpinata-plugins
```

## Workflow

1. Write or think aloud about your fiction. `scheherazade` triggers on
   workshop-shaped prompts ("help me think through…", "what's the motive
   here?", "is this scene working?").
2. When the bottleneck is sensory or atmospheric, `scheherazade` will
   delegate to `paint-a-picture` — or invoke it directly: "paint this
   scene for me."
3. When a creative decision has settled into canon, dispatch the result to
   `index-omnium` to file the fact, update the indices, and repair
   cross-references.

## Scope notes

- **`index-omnium` assumes an Obsidian-style vault.** It uses
  `[[wiki-links]]`, a `Status::` field, and a layered note taxonomy.
  Users outside that shape will need to adapt or skip this skill.
- **`paint-a-picture` is permanently Le Guin-voiced.** It does not modulate
  toward the writer's style; it is a visualisation device, not a
  ghostwriter.
- **No skill writes prose or canon on the writer's behalf.** All three
  remain advisory; the writer authors.

## Author

RKPinata — `teukutiga@gmail.com`
