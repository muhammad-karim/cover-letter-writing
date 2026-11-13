# Cover letter skill for Claude

**Give Claude a job advert and your master CV. Get back a one-page cover letter that says why you want the role, how you fit it, and the strongest evidence from your CV, in your own voice.**

This is a skill for Claude. It will:

1. **Pick** the two or three priorities that matter most to the employer.
2. **Find** the strongest honest evidence in your master CV for each one.
3. **Write** four short paragraphs: a hook about the employer, evidence for each priority, and a close.
4. **Check** that the letter fits one page, that every figure is in your CV, and that nothing is invented.

---

## What it checks

- **Fit:** does the letter say why you want this role and how you match it?
- **Hook:** does the opening refer to something specific and current about the employer, and has it been verified?
- **Evidence:** does each paragraph open with a priority from the advert and give a specific example with a number?
- **Length:** is it one A4 page, with no block longer than about eight lines?
- **Voice:** does it sound like you, in plain British English, without buzzwords or exclamation marks?
- **Honesty:** is every title, date and figure exactly as stated in your master CV?

## What you get

- **A one-page cover letter draft**, ready to export as a PDF.
- **Notes** on anything that needs your own words, such as the hook and the close.
- **A criterion-by-criterion version** if the employer asks for a supporting statement instead of a letter.
- **A flag** if the employer asks applicants not to use AI, so you can write it yourself.

## How to use it

**Install**
- **Claude app / claude.ai:** download this repository as a ZIP (green **Code** button › **Download ZIP**), then upload it under **Settings › Capabilities › Skills**.
- **Claude Code:** run `git clone https://github.com/muhammad-karim/cover-letter-writing ~/.claude/skills/cover-letter-writing`

**Then just ask, for example:**
- "Write a cover letter for this role: [paste the advert]"
- "Review my cover letter against this advert: [paste both]"
- "Draft a supporting statement for this application, criterion by criterion: [paste the criteria]"

## How it works

1. **Understand:** read the advert and the master CV, then choose priorities and evidence.
2. **Write:** draft four paragraphs, with the first words of paragraphs two and three naming the priority.
3. **Check:** confirm the page count, check every figure against the master CV, and run the honesty test.

## What's in this repository

```
SKILL.md        The instructions Claude follows (with plain-English notes)
README.md       This file
```

## Set-up

The skill refers to "the candidate's master CV" and the candidate's voice. Before use:

1. Put your master CV in one document. Every fact in a letter must come from it.
2. Write a few paragraphs of your own, or share a sample you've written, so the drafts sound like you.
3. Tell Claude the link to your master CV, once, at the start of a session.

## Good to know

- Hooks must be true. Check anything you quote about the employer before you send the letter.
- Always rewrite the hook and the close in your own words.
- Export to PDF and check it is one page.

## Licence

MIT. Free to use and adapt.
