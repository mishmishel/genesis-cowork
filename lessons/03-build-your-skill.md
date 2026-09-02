# Lesson 3: Build Your Own Skill

**What you'll learn:** A "skill" is just a markdown file with clear instructions that Cowork follows every time. You'll build one together with me, learn where skills live in the app, and walk away with an investor research automation you can use before any meeting.

---

## Opening

In Lesson 2, you gave me a set of instructions — something like "merge these two contact lists, deduplicate by email, use context clues to resolve conflicts, give me a clean CSV and a log."

That worked great. But here's the thing: you'll need to do that kind of workflow again and again. After the next networking event. After the next batch of customer discovery calls. After every demo day. And each time, you'd have to explain the whole process from scratch.

What if you could save those instructions once, and then just say "run it" next time?

That's what a skill is.

---

## What's a Skill?

A skill is just a markdown file with clear instructions. Think of it as a brief for a really capable intern — specific enough that they could follow it without asking you any questions.

And it's a built-in feature of Cowork, not just a file trick. Let me show you where skills live.

SAY: "Open your Cowork sidebar and click **Customise** in the top-left. Then click **Skills**. That's where Cowork stores reusable instructions. Right now it's empty — we're about to change that."

WAIT: Can you see the Skills section?

USER: [Response]

---

Good. By the end of this lesson, you'll have a skill sitting right there that you can run any time.

Every skill has the same five-part structure:

1. **What This Does** — a one-liner so you remember what it's for
2. **Inputs** — what data or files it needs
3. **Process** — what steps to follow
4. **Output** — what to produce
5. **Quality Standards** — what "good" looks like, so I don't cut corners

Let's build one together. And since you just merged a contact list full of investors, mentors, and customers, let's build something you'll actually use this week: **investor meeting prep**.

---

## Building It Together

You're a Genesis founder getting ready to raise. Over the next few months, you'll meet 10, 20, maybe 50 investors — at demo days, through intros, at the Genesis Finale. Before each meeting, you need to research the investor, understand what they care about, and find your angle.

Right now you'd do this manually: Google the firm, scan their website, check LinkedIn, read a few articles, take notes. That's 30-60 minutes per investor.

Let's turn that into a 2-minute skill. I'll walk you through each section — and I want your input on what matters most to you.

---

### Section 1: What This Does

This is the one-liner. Something like: "Researches an investor and their firm before a meeting, then produces a brief with personalised talking points."

WAIT: Does that capture it? Or would you frame it differently for how you prep for meetings?

USER: [Response]

---

ACTION: Acknowledge their input and adapt the one-liner if they suggested changes.

### Section 2: Inputs

What does this skill need to run? At minimum: the investor's name and firm. But what else would be useful?

WAIT: What information would you want to hand this skill? Just a name? An email? Context about what you're raising?

USER: [Response]

---

ACTION: Note their input. The final inputs section should include: investor name and firm (required), email (optional for checking contact data), and the student's startup one-liner and key metrics.

### Section 3: Process

This is the step-by-step logic. Here's what I'd suggest:

1. Search the web for the investor and their firm — thesis, recent deals, portfolio, public content
2. Check for connections to your startup — do they invest in your sector? Have they backed competitors?
3. Check your contact data for any existing notes on this person
4. Identify the strongest approach angle — shared interest, portfolio synergy, mutual connection
5. Draft talking points and suggested questions

WAIT: Anything you'd add? Anything you'd skip?

USER: [Response]

---

ACTION: Adapt the process based on their feedback.

### Section 4: Output

I'd produce a single markdown file — `investor-prep-[firm-name].md` — with: investor profile, firm overview, approach angle, talking points, suggested questions, and sources.

WAIT: Is that the right format? Would you want something different — a spreadsheet, a one-pager, bullet points?

USER: [Response]

---

### Section 5: Quality Standards

This is what separates a good skill from a sloppy one. My suggestions:

- Every claim needs a source URL
- Focus on recent info (last 12 months)
- Be honest about gaps — don't make things up
- The approach angle must be specific to THIS investor, not generic
- Flag if they've invested in a direct competitor — that's critical context

WAIT: What else matters to you? Any red flags you'd want the skill to catch?

USER: [Response]

---

## Creating the Skill File

Now let me put it all together based on what we just discussed.

ACTION: Create the skill file at `skills/investor-research-skill.md` in the course folder. Incorporate the student's input from the conversation above into each section. The file should follow this structure:

```markdown
---
name: investor-research
description: Researches an investor and their firm before a meeting, then produces a brief with personalised talking points and a suggested approach angle. Use this skill whenever the user mentions investor research, meeting prep, investor brief, pitch prep, or wants to prepare for a meeting with an investor or VC.
---

# Investor Research & Meeting Prep

## What This Does

[One-liner — use the student's framing if they provided one, otherwise: "Researches an investor and their firm before a meeting, then produces a brief with personalised talking points and a suggested approach angle."]

## Inputs

- Investor name and firm (required)
- Investor's email address (optional — for checking existing contact data)
- Your startup's one-liner and key metrics (pull from project context or ask)

## Process

1. Search the web for the investor and their firm:
   - Firm's investment thesis (stage, sectors, geography, cheque size)
   - Recent investments or portfolio companies (last 12 months)
   - Any public content: blog posts, podcast appearances, tweets, talks
   - The investor's background and career history
2. Check for connections to your startup:
   - Do they invest in your sector or adjacent sectors?
   - Have they backed competitors or related companies?
   - Is there a geographic or thematic overlap?
   - Did anyone in your network mention them?
3. If a contacts CSV exists in the working folder, check if this investor appears and pull any notes
4. Identify the strongest approach angle:
   - Shared sector interest
   - Portfolio company synergy
   - Recent public statement that aligns with your mission
   - Mutual connection or warm intro path
5. Draft meeting prep materials:
   - Investor profile (one paragraph)
   - Firm overview (one paragraph)
   - 3 personalised talking points
   - Suggested opening line for the meeting
   - 2-3 questions to ask them (shows you've done your homework)
   - Any risks or watch-outs (e.g., they backed a competitor)

## Output

A single markdown file: `investor-prep-[firm-name].md` containing:

- Investor profile
- Firm overview
- Approach angle
- Talking points
- Suggested questions
- Sources used

## Quality Standards

- Every claim must have a source (URL or reference)
- Focus on recent information (last 12 months preferred)
- Be honest about gaps — if you can't find something, say so
- The approach angle must be specific to this investor, not generic
- Talking points should reference real things the investor has said or done
- Flag if they've invested in a direct competitor — this is critical context
```

SAY: "Done — your first skill is saved as a file. Now let's add it to Cowork so it's always available. Open your Cowork sidebar, click **Customise**, then click **Skills**, then click **Add skill**. Navigate to the course folder, open the `skills` folder, and select `investor-research-skill.md`. Once it's added, you'll see it listed in your Skills section."

WAIT: Let me know once you've added it — or if you need help finding the file.

USER: [Response]

SAY: "Great — that skill is now registered in Cowork. Any time you start a new session and mention investor research or meeting prep, Cowork will know to use it."

ACTION: Read the skill file and display its full contents in the chat so the student can review it without leaving Cowork.

WAIT: Does this look right? Anything you'd tweak?

USER: [Response]

---

[If they suggest changes]: Good call — let me update that.
ACTION: Make the requested changes to the skill file.

[If they're happy]: Perfect.

---

## Iteration Is Best Practice

One important thing: **skills are meant to be iterated on.** This first version is a draft. After you run it before a real meeting, you'll notice things — maybe you want more detail on the firm's portfolio, or less on their background. Just open the skill file, tweak it, and save.

After 2-3 runs and tweaks, it'll feel bulletproof. That's normal — the best skills are the ones that have been refined through real use.

---

## Testing the Skill

Let's prove it works. Remember Anna Fitzgerald from your contact list? She's the investor running this session — and she's in the room right now. Let's prep for a meeting with her.

WAIT: Want me to run the skill on Anna Fitzgerald, Co-Head of Genesis?

USER: [Response]

---

### If Yes: Test the Skill

ACTION: Read the skill file you just created, then execute it for **Anna Fitzgerald, Co-Head of Genesis**. Follow the skill exactly as written — search the web, check the contact data from Lesson 2, identify approach angles, and produce the full brief.

SAY: "Notice I didn't ask you any questions this time. The skill file had everything I needed. That's the whole point — write it once, run it forever."

ACTION: Show the output. The investor prep file should be genuinely useful — the student will use it in Lesson 4.

### If No: Move On

No worries — it's saved and ready whenever you need it. We'll use it in the next lesson anyway.

---

## More Skill Ideas

The investor research skill is just one example. You can create a skill for anything you do repeatedly. Some ideas for your startup:

- **Customer discovery analysis** — "Read these interview transcripts and extract: pain points, willingness-to-pay signals, feature requests, and quotes for my pitch deck"
- **Competitor watch** — "Research these 5 competitors and create a comparison matrix with pricing, features, funding, and recent news"
- **Goal Night prep** — "Read all my files and draft a structured Genesis update with progress against milestones, blockers, and next steps"
- **Grant application helper** — "Read this grant criteria document and draft responses based on my startup's materials"

WAIT: Do you have a task in mind that you do regularly? If so, I can build a skill file for it right now. If not, say **"next lesson"** to keep going.

USER: [Describes a task, or says they want to move on]

---

[If they want to move on]: No problem — the template is there whenever you need it. You can always come back and say "help me build a skill for [task]" and I'll create it.

[If they describe a task]:

Great — let me build that for you. I'll ask you the same five questions we just went through:

ACTION: Ask clarifying questions:

- What does this skill do in one sentence?
- What inputs does it need?
- What's the process?
- What should the output look like?
- What are the quality standards?

Then create the skill file based on their answers. Save it in the `skills/` folder. The file MUST start with YAML frontmatter containing `name` and `description` fields (between `---` delimiters), just like the investor research skill — Cowork requires this to import it. Show them the result so they can tweak it. Remind the student to add it to Cowork via Customise > Skills > Add skill, just like they did with the investor research skill.

---

## Wrap-Up

You now have the full toolkit:

1. **Organise** — Read, understand, and structure files at scale (Lesson 1)
2. **Validate** — Run data workflows, cross-reference sources, and document every decision (Lesson 2)
3. **Automate** — Build reusable skills for any repeating task (this lesson)

These three patterns cover most startup operations work. Everything else is just variations on these themes.

---

**Next up:** Time to graduate. You've got an investor brief, you've got your startup's story, and you've got a real investor in the room. Let's pitch her.

**To continue:** Say **"next lesson"**
