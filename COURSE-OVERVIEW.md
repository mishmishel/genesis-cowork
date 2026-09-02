# Cowork Course — Genesis Edition Overview

## What Is This?

An interactive course that teaches Claude Cowork by doing real work — not by explaining features. Designed for startup founders going through the University of Sydney's Genesis accelerator program. Students learn by watching Cowork organise their startup files, driving a contact data cleanup themselves, building a reusable investor research skill, and pitching a real investor.

By the end, students can delegate real operational work to Cowork — not just ask questions. And they'll have sent a pitch email to a Genesis Co-Head.

## Who Is It For?

Startup founders in the Genesis program at the University of Sydney. The course uses startup-specific scenarios (pitch decks, customer interviews, investor contacts, demo day networking) that apply directly to their current work. No technical background required.

## How It Works

Students open Cowork, point it at the course folder, and say **"Read the START-HERE.md and start lesson 1."** Cowork teaches the course interactively, waiting for responses, adapting to the student's startup, and doing real work on real files throughout.

The course takes 50-75 minutes for all 4 lessons.

## Course Structure

### Lesson 1: First Contact (~20 min)

**Students watch Cowork work.** A folder of 13 messy startup files (pitch decks, interview notes, financial projections, mentor feedback) gets organised into a clean structure — all while the student watches in their file explorer. Introduces the "worker not chatbot" mental model.

### Lesson 2: Data Cleanup (~20 min)

**Students drive a workflow.** Two contact lists in different formats — one from an accelerator network, one from a demo day — need to be merged, deduplicated, and cross-referenced to resolve conflicts. Students learn to describe outcomes, not steps.

### Lesson 3: Build Your Own Skill (~15 min)

**Students create a reusable automation.** An investor research skill that can be run before any meeting — research the firm, find the approach angle, draft talking points. Students can also sketch a skill for their own repeating tasks.

### Lesson 4: The Pitch (~15 min)

**Students pitch a real investor.** Using the investor research skill, their startup materials, and optionally the Gmail connector, students research Anna Fitzgerald, draft a personalised pitch email, and send it. Course graduation = a real pitch sent.

## What's In the Folder

```
genesis-cowork-course/
├── START-HERE.md                            # Entry point — Cowork reads this first
├── COURSE-OVERVIEW.md                       # This file (for humans, not Cowork)
├── CUSTOMISATION-GUIDE.md                   # How to adapt the course
├── lessons/
│   ├── 01-first-contact.md                  # Lesson 1: File organisation demo
│   ├── 02-data-cleanup.md                   # Lesson 2: Contact list merge & verify
│   ├── 03-build-your-skill.md               # Lesson 3: Investor research skill
│   └── 04-bonus-live-connector.md           # Lesson 4: The Pitch (graduation)
├── scenarios/
│   ├── chaos-folder/                        # 13 startup files used in Lesson 1 demo
│   ├── contacts-accelerator-network.csv     # Accelerator contacts for Lesson 2
│   └── contacts-demo-day-sydney.csv         # Demo day contacts for Lesson 2
└── skills/                                  # Empty — populated during Lesson 3
```

## How to Run It

### For the Genesis session:

1. Distribute the course folder to attendees (AirDrop, shared drive, USB)
2. Each student opens Claude Cowork and selects the course folder
3. Say: **"Read the START-HERE.md and start lesson 1"**
4. The course teaches itself interactively

### Pre-work for attendees:

1. Download Claude desktop app and sign up for Pro ($20/mo)
2. Enable Google Workspace connectors: Settings > Connectors > Google (Gmail, Calendar, Drive)
3. Download the course folder to their laptop

## Requirements

- Claude desktop app with Cowork mode
- The course folder selected as the working directory
- For Lesson 4 (The Pitch): Gmail connector enabled (recommended but not required)

## Tips for the Session Runner

- **Don't pre-explain the course.** Just point people at the folder and say "start lesson 1." The course introduces itself.
- **Let people go at their own pace.** Some will finish in 50 minutes, some will take 90. Both are fine.
- **The pitch is the climax.** Make sure people don't skip Lesson 4 — it's the payoff.
- **Check your inbox.** You'll receive pitch emails from the students as they graduate. You can reference these in the wrap-up for a fun moment.

## Credits

Course adapted from the Claude Cowork Course for the USYD Genesis program, Cohort 36 (April 2026). Session run by Marnix Denys, Airtree Ventures.
