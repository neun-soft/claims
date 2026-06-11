# claims

**The scientific method, run on your intuition.** A free [Claude](https://claude.com/claude-code)
skill that takes a raw claim through a discovery process — pressure-tests it against real university research to learn which parts hold up, which can be sharpened, and what better claim might be hiding inside, with the words carefully aligned to what the
evidence supports. Optionally, it then renders that calibrated stance as a calm Threads post that leaves room for your own voice.

Built and shared free by [neunsoft](https://neunsoft.com).

Learn about the skill origins at https://neunsoft.com/claims.

## What it does

You bring an intuition, something you have been thinking about and have maybe even experienced with your own flesh, maybe half-formed or wild. The skill validates it through four phases — that verdict is the product — then offers an optional content step:

1. **Capture** — states your hunch as one clean, falsifiable claim. Learn here what is a falsifiable claim and why it is important: https://neunsoft.com/claims
2. **Research** — finds _real_ studies (universities, peer review, meta-analyses),
   including the ones that disagree with you, and builds an evidence ledger.
3. **Polish & align** — the heart of it. Matches every verb to the strength of its
   evidence so no claim outruns what's actually known and follows each research's own inertia (the power of accurate citations). The output is a _stance_: an honest verdict on where you're right, and to what degree.
4. **Steelman the counter-argument** _(optional)_ — goes looking for the strongest case
   _against_ you. If the stance survives, you hold it with real confidence; if it
   doesn't, it helps you find the bits where you are actually right about and sharpen them to be useful one way or another, win on every case by adapting.

**Optional content step** — only if you want it, offered once after the verdict:

5. **Business tie-in** — connects the stance to what you're building (reads your site
   or strategy doc if you have one).
6. **Render** — a calm, neutral Threads post that leaves room for your own voice, plus
   an optional short-form video idea.

Every question along the way maps to a piece of the scientific method (hypothesis,
population, prediction, measurement, control, falsifiability) — ask "why are you
asking that?" anytime and you'll get a brief, one-line answer.

It's **peer review for a one-person business**: verify the claims, calibrate the words
to the evidence, address the counter-argument _before_ you act on a belief — or
publish it — instead of getting corrected after. The one inviolable rule: **the words
never outrun the evidence.**

## Install

Copy the `claims/` folder into your Claude skills directory:

```bash
cp -r claims ~/.claude/skills/claims
```

It's self-contained — no dependencies, no setup.

## Use

In Claude, just start with your idea:

> /claims

Then follow the phases. You can re-run the polish step anytime by saying **"polish"**
or **"re-align."**

## License

Free to use, share, and adapt.
