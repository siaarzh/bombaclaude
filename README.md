<p align="center">
  <img src="https://em-content.zobj.net/source/apple/391/flag-jamaica_1f1ef-1f1f2.png" width="120" />
</p>

<h1 align="center">bombaclaude</h1>

<p align="center">
  <strong>same brain. full vibes. seen?</strong>
</p>

<p align="center">
  A <a href="https://docs.anthropic.com/en/docs/claude-code">Claude Code</a> skill that makes the agent chat in Jamaican Patois — without dropping a single technical detail.
</p>

---

## Before / After

### 🤖 Normal Claude
> "The reason your React component is re-rendering is because you're creating a new object reference each render. Wrap it in `useMemo`."

### 🇯🇲 Bombaclaude — full tier
> "Yuh a create new object ref every render. Inline obj prop = new ref = re-render. Wrap it inna `useMemo`, seen?"

### 🔥 Bombaclaude — raw tier
> "Bombaclaat, every render yuh a spawn new ref. Inline obj prop → new ref → re-render. `useMemo` di ting, seen?"

Same fix. Same accuracy. Full vibes.

## Tiers

| Tier | What you get |
|------|--------------|
| 🪶 **lite** | Subtle flavor. Greeting + a few words. Professional |
| 🇯🇲 **full** | Real patois grammar (mi / yuh / nuh / deh / fi / a). Default |
| 🔥 **raw** | Uncut. Crude Jamaican exclamations included (vulgar — opt-in only) |

## Install

As a Claude Code plugin marketplace:

```bash
claude plugin marketplace add siaarzh/bombaclaude
claude plugin install bombaclaude@bombaclaude
```

Or copy `skills/bombaclaude/SKILL.md` into your project's `.claude/skills/` directory.

## Usage

**Trigger:**
- `/bombaclaude` — full tier (default)
- `/bombaclaude lite` — subtle
- `/bombaclaude raw` — uncut
- "talk patois" / "patois mode" / "jamaican mode"

**Stop:** "stop bombaclaude" / "normal mode" / "english mode"

Tier sticks until changed or session end.

## What it preserves

Code blocks, file paths, error messages, command output, commit messages, and PR text are never modified. Patois only affects conversational prose.

Security warnings and destructive-action confirmations also drop patois automatically — clarity beats vibes when files are about to die.

## Why

`/caveman` proved you can compress LLM output without losing accuracy. `/bombaclaude` doesn't compress — it code-switches. Same brain, different register. It's also funny.

## A note on the dialect

Jamaican Patois is a real Caribbean creole spoken by millions, not a parody. The grammar this skill uses is real:
- `mi` / `yuh` / `im` / `wi` / `dem` — real pronouns
- `a` — real continuous-aspect marker
- `nuh` — real negation particle
- `fi` — real infinitive complementizer

Goal: Claude speaks fluent patois. Not a caricature.

## License

MIT.
