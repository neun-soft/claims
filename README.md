# claims — a free Claude skill by [Neunsoft](https://neunsoft.com)

**The scientific method, run on your intuition.** Take a raw hunch and find out if
it's true — pressure-tested against real university research, with every word aligned
to what the evidence supports, landing on a verdict you can actually defend. Then,
optionally, render it as a calm Threads post.

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

Third-party plugins are pinned to the version you installed and do **not** auto-update by
default. To get the latest:

```
claude plugin update claims@neun-soft
```

Or turn on automatic updates once: run `/plugin`, pick the `neun-soft` marketplace, and
choose **Enable auto-update**. (Note: `/plugin marketplace update` only refreshes the
catalog — it does not update an already-installed plugin.)

## Install (Codex)

Codex uses the same `SKILL.md` format. Drop the skill into your Codex skills folder,
restart Codex, then run `$claims` (Codex invokes skills with `$`, not `/`):

```bash
mkdir -p ~/.codex/skills/claims
curl -fsSL https://neunsoft.com/claims-skill.md -o ~/.codex/skills/claims/SKILL.md
```

## Manual install (no marketplace)

Copy the skill folder into your skills directory:

```bash
cp -r plugins/claims/skills/claims ~/.claude/skills/claims
```

## What it does

You bring an intuition — something you've been turning over, maybe even lived through.
The skill validates it: **capture** a falsifiable claim → **research** real studies
(including the ones that disagree with you) → **polish & align** every word to the
evidence → **steelman** the counter-argument. That verdict is the product. Then, only
if you want, an optional content step: **tie it to your business** → **render** a calm
Threads post. Ask "why are you asking that?" at any question and you'll get a one-line
answer tying it to the scientific method. It's peer review for a one-person business.
The one inviolable rule: **the words never outrun the evidence.**

Full skill documentation: [`plugins/claims/skills/claims/README.md`](plugins/claims/skills/claims/README.md)

## License

MIT — free to use, share, and adapt.
