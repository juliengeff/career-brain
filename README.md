# Career Brain

**An AI career coach you install into Claude.** It gives your AI a permanent,
private memory of your real career — so it stops giving generic advice, never
invents facts about you, and helps you write a resume, LinkedIn, and interview
answers that are sharp, true, and yours.

A [Growth Leaps](https://www.growth-leaps.com) project ·
[Product page](https://www.growth-leaps.com/career-brain.html) ·
[Beginner setup guide](https://www.growth-leaps.com/career-brain-setup.html)

## Install (paid Claude plan)

```
/plugin marketplace add juliengeff/career-brain
/plugin install career-brain@growth-leaps
```

Then, in a folder Claude can access, say **"set up my Career Brain"** and answer
the coach's questions. After that: **"coach me"**, **"fix my resume"**,
**"rewrite my LinkedIn"**, or **"prep me for an interview."**

## What's inside

This repository is both a Claude plugin **marketplace** (`growth-leaps`) and the
**career-brain** plugin it lists.

- `.claude-plugin/marketplace.json` — the marketplace catalog
- `.claude-plugin/plugin.json` — the plugin manifest
- `skills/career-coach` — the coach persona and the two laws (never invent facts;
  always save to the Brain)
- `skills/career-brain-setup` — the onboarding interview that builds your Brain
- `skills/resume-coach` — audits and rebuilds your resume from verified facts
- `skills/linkedin-coach` — rewrites your LinkedIn profile, section by section
- `skills/interview-prep` — predicts hard questions and runs blunt mock interviews
- `reference/my-career-brain-template.md` — the 6-section Brain template

## The two rules that make it work

1. **Never let the AI invent anything about you.** If a fact isn't in your Brain,
   the coach asks. If you can't defend a claim in an interview, it doesn't go in.
2. **The Brain is the memory; the chat is scratch paper.** Everything important
   lives in your Brain file, not the conversation.

## Free, any-AI version

No paid Claude plan? The same coach works free on Claude, ChatGPT, or Gemini with
a copy-paste setup — see the [product page](https://www.growth-leaps.com/career-brain.html).

## License

MIT

Questions: julien@growth-leaps.com
