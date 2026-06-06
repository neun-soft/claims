# claims

**The scientific method, as a content pipeline.** A free [Claude](https://claude.com/claude-code)
skill that takes a raw claim and turns it into a stance you can actually defend with real university research, with the words carefully aligned to what the
evidence supports, then renders it as a calm Threads post that leaves room for your own voice.

Built and shared free by [neunsoft](https://neunsoft.com).

Learn about the skill origins at https://neunsoft.com/claims.

## What it does

You bring an intuition, something you have been thinking about and have maybe even experienced with your own flesh, maybe half-formed or wild. The skill walks you through six phases:

1. **Capture** — states your hunch as one clean, falsifiable claim. Learn here what is a falsifiable claim and why it is important: https://neunsoft.com/claims
2. **Research** — finds _real_ studies (universities, peer review, meta-analyses),
   including the ones that disagree with you, and builds an evidence ledger.
3. **Polish & align** — the heart of it. Matches every verb to the strength of its
   evidence so no claim outruns what's actually known and follows each research's own inertia (the power of accurate citations). The output is a _stance_ that will help you with your business.
4. **Steelman the counter-argument** _(optional)_ — goes looking for the strongest case
   _against_ you. If the stance survives, you publish with real confidence; if it
   doesn't, it helps you find the bits where you are actually right about and sharpen them to be useful for your business one way or another, win on every case by adapting.
5. **Business tie-in** — connects the stance to what you're building (reads your site
   or strategy doc if you have one).
6. **Render** — a calm, neutral Threads post that leaves room for your own voice, plus
   an optional short-form video idea.

It's **peer review for a one-person business**: verify the claims, calibrate the words
to the evidence, address the counter-argument _before_ you publish instead of getting
corrected after. The one inviolable rule: **the words never outrun the evidence.**

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
