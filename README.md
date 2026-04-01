# theres-a-skill-for-that

An [Agent Skill](https://docs.anthropic.com/en/docs/claude-code/skills) that reads your project and tells you exactly which skill to run next.

Part of the [Kaizen](https://iamichieuche.github.io/kaizen) skills pack.

## What it does

Reads your project — stack, git history, recent diffs, what you've been working on — checks your installed skills and the full skills.sh catalog, and recommends one to three skills to run right now. Built for designer-engineers who care about how things look, move, and feel.

It knows the difference between a project that needs motion work and one that needs its design system sorting out. It figures out what phase you're in and gives you a specific answer for right now.

## Installation

```bash
npx skills add iamichieuche/theres-a-skill-for-that -y -g
```

## Usage

Run it with no arguments for a full project read:

```
/theres-a-skill-for-that
```

Or give it context:

```
/theres-a-skill-for-that before we launch
/theres-a-skill-for-that the animations feel wrong
/theres-a-skill-for-that push the UI further
```

It gives you one to three skills. Never more. Never generic. Always specific to what it found in your project.

## Works in

- [Claude Code](https://claude.ai/code)
- [Cursor](https://cursor.com)
- [Codex](https://openai.com/codex)
- [Ghostty](https://ghostty.org)
- [Conductor](https://conductor.build)
- Any agent that supports the skills format

## License

MIT
