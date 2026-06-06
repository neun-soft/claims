# claims — a free Claude skill by [Neunsoft](https://neunsoft.com)

**The scientific method, as a content pipeline.** Take a raw hunch and turn it into a
stance you can actually defend — backed by real university research, with every word
aligned to what the evidence supports — then render it as a calm Threads post.

This repo is also a **Claude Code plugin marketplace**, so you can install the skill in
two commands. Read the story behind it at **https://neunsoft.com/claims**.

## Install (Claude Code)

In Claude Code, run:

```
/plugin marketplace add neun-soft/claims
/plugin install claims@neun-soft
```

Then invoke it any time with **`/claims`**. (It only runs when you call it — it never
triggers on its own.)

## Update

```
/plugin marketplace update neun-soft
```

## Manual install (no marketplace)

Copy the skill folder into your skills directory:

```bash
cp -r plugins/claims/skills/claims ~/.claude/skills/claims
```

## What it does

You bring an intuition — something you've been turning over, maybe even lived through.
The skill walks six phases: **capture** a falsifiable claim → **research** real studies
(including the ones that disagree with you) → **polish & align** every word to the
evidence → **steelman** the counter-argument → **tie it to your business** → **render** a
calm Threads post. It's peer review for a one-person business. The one inviolable rule:
**the words never outrun the evidence.**

Full skill documentation: [`plugins/claims/skills/claims/README.md`](plugins/claims/skills/claims/README.md)

## License

MIT — free to use, share, and adapt.
