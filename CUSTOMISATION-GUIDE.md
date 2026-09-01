# Customisation Guide

This course works out of the box for anyone. But if you want to adapt it for your organization, here's how.

---

## Quick Customisations (15 minutes)

### Swap the scenario files

The 13 files in `scenarios/chaos-folder/` are generic business documents. You can replace them with files that match your industry:

- **VC firms:** pitch decks, LP updates, deal memos, portfolio financials
- **Agencies:** client proposals, SOWs, project timelines, creative briefs
- **SaaS companies:** product specs, customer feedback, pricing docs, roadmaps
- **Consulting:** engagement letters, deliverables, client reports, templates

The files should be a believable mess — bad names, flat folder structure, mixed formats (PDF, DOCX, CSV, TXT). The messier the better for the Lesson 1 demo.

### Swap the contact CSVs

The two CSV files in `scenarios/` (`contacts-accelerator-network.csv` and `contacts-demo-day-sydney.csv`) use fictional names and companies. You can replace these with:

- **Industry-specific contacts:** Use names relevant to your field
- **Fictional contacts:** Invent names that feel realistic for your context
- **Real but anonymized data:** Use real column structures from your CRM but fake the names

**Important for Lesson 2:** The two CSVs must have:
1. Different column formats (e.g., "Full Name" vs "First Name / Last Name")
2. Some overlapping contacts (duplicates to merge)
3. Some intentional discrepancies (conflicting titles, company changes) with context clues in the notes to help resolve them
4. Enough entries to make the exercise feel real (15-20 per file works well)

---

## Medium Customisations (1-2 hours)

### Add your own attendee list

If you're running the course for a specific group, you can add team-based personalisation to START-HERE.md:

1. Add an **Attendee List** section mapping names to teams/roles
2. Update the teaching instructions to match names against the list
3. Add team-specific framings to Lesson 2's "Bigger Picture" section

Example format for START-HERE.md:

```markdown
**Attendee List:**
- Alice, Bob → Engineering
- Carol, Dave → Marketing
- Eve → Finance
```

The course already asks for names and roles in Lesson 1. An attendee list just lets it skip the role question and deliver more targeted content.

### Add a team Slack channel for Lesson 4

If your whole team is doing the course and you have Slack connected, you could:

1. Create a dedicated Slack channel (e.g., `#cowork-course`)
2. Update Lesson 4 to include a Slack exercise: send course takeaways to the channel
3. This creates a shared moment where everyone's learning is visible

---

## Deep Customisations (half day)

### Rewrite scenarios for your industry

The chaos folder files and contact CSVs can be completely rewritten to match your domain. The key principles to preserve:

**For the chaos folder (Lesson 1):**
- 13 files across 4+ document types (TXT, CSV, PDF, DOCX)
- Bad or unhelpful file names
- A mix of internal docs, external docs, financial data, and planning materials
- Some files should reference each other (e.g., a meeting note mentioning a proposal)

**For the contact CSVs (Lesson 2):**
- Two files with genuinely different column structures
- Overlapping entries that need deduplication
- Intentional discrepancies with context clues (e.g., event notes hinting at job changes) that cross-referencing can resolve
- Enough complexity to take 5-10 minutes to process

**For skills (Lesson 3):**
- No changes needed — the skill is built from whatever Lesson 2 does

### Add company-specific lessons

The lesson structure is modular. You can:
- Insert a lesson between existing ones (renumber accordingly)
- Replace a lesson entirely with a company-specific workflow
- Add lessons after Lesson 4 for advanced topics

Each lesson file follows the same structure: WAIT/ACTION/USER markers, conversational tone, before/during/after flow. See any existing lesson for the template.

---

## What Not to Change

A few things that make the course work and shouldn't be modified:

1. **The WAIT markers.** These create the interactive flow. Without them, Cowork will monologue instead of teaching.
2. **The "worker not chatbot" framing in Lesson 1.** This mental shift is the foundation everything else builds on.
3. **The "describe the outcome" coaching in Lesson 2.** This is the core skill students need.
4. **The skill file structure in Lesson 3.** What This Does → Inputs → Process → Output → Quality Standards. This template is deliberately simple and proven.
5. **The teaching instructions in START-HERE.md.** These control how Cowork behaves as a teacher. Modify the content, but keep the critical rules intact.

---

## Distribution

The course is a folder of markdown files, CSVs, and sample documents. Share it however works for your org:

- **Shared drive:** Drop the folder on Google Drive, Dropbox, OneDrive, etc.
- **Git repo:** Clone and customise
- **Zip file:** Download and unzip
- **Direct folder share:** AirDrop, file share, USB, whatever

Each student needs their own copy of the folder (Cowork modifies files during the course — creating the demo-mess/ folder, merged CSVs, skill files, etc.).
