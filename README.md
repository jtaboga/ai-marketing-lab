# AI Marketing Lab

A personal sandbox for the marketing work I'd rather not lose track of: prompts that
actually earn their keep, small experiments, and the occasional script that saves me
an hour.

Nothing here is precious. Things get tried, kept, or deleted. The point is to have a
versioned home for the stuff I'd otherwise leave scattered across notes apps and
half-remembered chat threads.

## What's in here

| Folder | What lives there |
| --- | --- |
| `prompts/` | Reusable prompts, organized by job-to-be-done. Each one notes what it's for and what good output looks like. |
| `experiments/` | Rougher stuff — things I'm testing. Some graduate to `prompts/`, some don't. |
| `scripts/` | Small automations (CSV wrangling, API pulls, etc.). |

## How I use it

- One prompt or idea per file, in Markdown.
- Commit when something works — the history *is* the point. Being able to see what a
  prompt looked like three versions ago is the whole reason this exists.
- If a prompt gets meaningfully better, I edit and commit rather than making
  `prompt-v2-FINAL-final.md`. Git remembers the old version so I don't have to.

## Ground rules

- **No secrets.** No API keys, tokens, passwords, or client data — ever. If a script
  needs a key, it reads it from an environment variable, and the key stays out of the repo.
- **No confidential work.** Anything company-specific or under NDA belongs in a private
  repo, not this one.

---

*Maintained by [Your Name]. Built as my first real GitHub repo.*
