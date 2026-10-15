# HOPE Coworker Tip-Claim Kit

Helps current and former HOPE Dog Training (Norco, CA) employees review
whether customer tips were paid correctly and prepare a California wage
claim — two ways:

1. **A copy-paste prompt** they feed to their own private Muse (free
   signup), which interviews them, analyzes their evidence, and drafts
   their claim packet. → `MUSE_PROMPT.md`
2. **A plain text guide** for anyone who'd rather do it without AI:
   steps, required evidence, honest expectations. → `TEXT_GUIDE.md`

**This is an independent employee information project — not legal advice,
not a HOPE service, not a government service.**

## Contents

```
├── README.md            # this file
├── GROUPME_KIT.md       # ready-to-send GroupMe messages (personal note + prompt in chunks)
├── MUSE_PROMPT.md       # the full prompt in 4 copy-paste parts
├── TEXT_GUIDE.md        # the do-it-yourself text guide
├── LEGAL_RESOURCES.md   # verified official California resources (links checked 2026-10-13)
├── PRIVACY.md           # what is collected and where it goes
├── SECURITY.md          # what this repo must never contain
└── .gitignore           # blocks employee documents, secrets, customer data
```

## How the administrator uses this

1. Open `GROUPME_KIT.md` and send **Message 1** (the personal note) to the
   team channel. It presents both options.
2. Send **Messages 2–6** (the prompt, in order) so people can copy them
   into their own Muse chat. Or share the repo link and let people copy
   from `MUSE_PROMPT.md`.
3. Share `TEXT_GUIDE.md` (raw GitHub link) for anyone skipping the AI
   route.

No website to deploy, no server, no accounts to manage. GitHub is just a
convenient place to host the text.

## Design rules enforced in the prompt

- One question at a time; Skip and "I don't know" always allowed.
- The assistant never invents tip amounts or divides company-wide totals.
- Findings classified as Documented / Firsthand account / Corroborated /
  Estimate / Unknown — conservative throughout.
- Nothing is ever submitted without the employee's explicit approval of
  that specific submission.
- No names of owners, managers, or coworkers; no theft declared; no
  investigation data embedded.
- Legal information only, from official DIR sources — never legal advice,
  never promised outcomes.

## Maintenance

- Re-verify the official links in `LEGAL_RESOURCES.md` quarterly.
- If California tip law changes, update the prompt's Part 4 and
  `TEXT_GUIDE.md` together.

## History

A mobile web-app version of this project was built 2026-10-13 and removed
2026-10-14 per the project owner's request — the prompt + text guide
replaced it. Git history retains the earlier work.
