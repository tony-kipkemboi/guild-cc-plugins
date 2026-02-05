# Guild Plugins

Internal marketplace of Claude Code plugins for the Guild team.

## Plugins

### insights-video

Generate a polished 30-second animated video showcasing your Claude Code usage insights. Features Claude branding, animated stats, project areas chart, friction analysis, and background music.

**What it does:**
- Reads your `/insights` data automatically
- Scaffolds a full Remotion project with your personalized stats
- Renders a 1080x1080 animated MP4 video with:
  - Animated stats dashboard (sessions, messages, hours, commits)
  - Project areas bar chart
  - "What's Working" highlights
  - Friction points analysis
  - Your interaction style quote
  - Satisfaction rate closing card
  - Background music with fade in/out

**Prerequisites:**
- Node.js installed
- Run `/insights` at least once (generates the data)

**Install:**
```bash
claude plugin add https://github.com/tonykipkemboi/guild-plugins
```

**Usage:**
```
/insights-video
```

That's it. Everything else is automatic.

## Adding New Plugins

Create a new directory with a `plugin.json` manifest and add your skills, commands, hooks, or agents inside.

## License

Internal use only - Guild team.
