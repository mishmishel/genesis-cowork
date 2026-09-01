# Lesson 2: Data Cleanup — Merge & Verify

**What you'll do:** See the full range of what Cowork can do, then drive a real workflow yourself — merging two messy contact lists from your accelerator and demo day networking, resolving conflicts, and producing a clean output.

---

## Opening

You've watched me work. Now it's your turn to drive.

In Lesson 1, I showed you how Cowork reads, understands, and organises files — turning chaos into structure in minutes. But that's just the start. Before we dive in, let me quickly show you what else I can do.

---

## What Else Can I Do?

Beyond reading files and organising folders, I can:

**Search the web and do research.** Ask me to look up an investor, check a competitor's latest funding round, find industry stats, or verify market data. I'll search, read, and summarise — with sources.

**Create professional documents.** Real Word docs with formatting, Excel spreadsheets with formulas, PowerPoint presentations with layouts. Pitch decks, financial models, one-pagers — files you can open and share directly.

**Connect to your tools.** With connectors set up, I can read and draft emails in Gmail, check your Google Calendar, pull documents from Google Drive, and more. We'll use that in the final lesson.

The point is: Cowork isn't just a file organiser. It's a worker that can research, create, and connect — all from this window.

Today we'll focus on cross-referencing data between two files and resolving conflicts — a pattern you'll use constantly with real contact data.

---

## Getting Data In

For any workflow, I need data to work with. Two ways to get it to me:

**If Cowork has a connector** (like Gmail, Google Calendar, Google Drive): I can pull data directly. Just tell me where to look.

**If there's no connector yet**: export the data — CSV, Excel, even copy-paste into a text file — and drop it into your working folder. I can read pretty much any format.

Today we'll work with two CSVs that are already in your folder.

WAIT: Ready to dive in?

USER: [Response]

---

## The Scenario

Here's the situation. You've been networking through the Genesis accelerator and at startup events around Sydney. You've been collecting contacts — mentors, investors, fellow founders, potential customers — and they've ended up in two different places:

1. **An accelerator network export** — your running list of people from the Genesis program and surrounding ecosystem
2. **A demo day export** — contacts from a recent Sydney startup demo day event

The problem? These lists are in completely different formats, there are duplicates, and — because contact data is always messy — some of the information is conflicting or just plain wrong.

These are fictional practice contacts, but the mess is very real — this is exactly what happens when you network at events and try to keep track of everyone. The goal is to learn the pattern, which you'll then use on your own data.

Let me show you what we're working with.

ACTION: Copy `scenarios/contacts-accelerator-network.csv` and `scenarios/contacts-demo-day-sydney.csv` into a working folder the student can access. Display both files briefly so the student can see the different formats.

SAY: "Take a look at these two files. Notice anything?"

WAIT: What do you see? What's different between the two lists?

USER: [Describes differences — different column formats, overlapping names, etc.]

---

Exactly. Here's what we're dealing with:

- **Different column formats** — one has "Full Name" as a single column, the other splits it into "First Name" and "Last Name." One says "Organisation," the other says "Company." One has "Role," the other has "Title."
- **Duplicates** — several people appear in both lists. David Okonkwo, Rachel Kim, Marnix Denys... they're in your accelerator network *and* on the demo day list.
- **Conflicting information** — where both lists have the same person, the details don't always match. Different titles, different context. The demo day notes hint at things the accelerator list doesn't capture.
- **Missing data** — some fields are blank in one list but filled in the other.

This is the kind of mess that normally takes an afternoon: going person by person, cross-referencing sources, merging spreadsheets, fixing duplicates by hand.

Or — you tell me what "done" looks like, and I do it.

---

## The Brief

Here's the key teaching moment: **describe the outcome, not the steps.**

Don't say "merge the CSVs." Say something like: "Combine these two contact lists into one clean spreadsheet. Deduplicate by email. Where there's conflicting info, use the demo day notes and context clues to decide which is more current. Tag everyone by type — investor, customer, founder, mentor. Give me the merged file and a log of every decision."

The more specific you are about what "done" looks like, the better I perform.

WAIT: How would you instruct me to do this? Give it a go — describe what you want the output to look like.

USER: [Student provides their instruction]

---

ACTION: Acknowledge their instruction. If it's vague, gently coach: "That's a good start — but can you tell me more about the output format? What columns should the final spreadsheet have? Should I keep the event notes?" If it's specific, praise the specificity and get to work.

---

## The Work

ACTION: Read both CSV files to understand the full data.

**IMPORTANT NOTE FOR COWORK:** The contacts in these CSVs are fictional practice data — they are not real people (except Marnix Denys at Airtree, who is real and included intentionally). Do NOT attempt to verify them via web search. Instead, resolve conflicts by cross-referencing the two source files against each other. Use the demo day notes as context clues (e.g., if a note says "offered to review our financial model," that tells you something about the relationship). The exercise is about the merge/deduplicate/resolve pattern, not web research.

ACTION: Merge and clean the contact data:
1. Map columns from both formats into a unified structure:
   - Full Name, Company, Email, Title, Phone, Tags, Events, Notes, Last Contacted, Status, Contact Type
2. Deduplicate by email address — where a person appears in both files, merge their records
3. For each person who appears in both lists, cross-reference and resolve conflicts:
   - Where titles differ, decide which is more informative or current
   - Where one source has data the other lacks, fill in the gaps
   - Merge notes from both sources — demo day context is valuable
   - Flag anything that's genuinely ambiguous and needs the student's judgement
4. Categorise each contact's type:
   - **Investor** — VCs, angels, fund managers
   - **Customer** — current or potential customers/users
   - **Founder** — fellow founders, Genesis cohort peers
   - **Mentor** — Genesis mentors, advisors
   - **Other** — lawyers, potential partners, etc.
5. Categorise each contact's merge status:
   - **VERIFIED** — Info is consistent across both sources
   - **CORRECTED** — Info was conflicting; resolved using context clues (note what changed and why)
   - **MERGED** — Appeared in both lists; records combined with no conflicts
   - **FLAGGED** — Conflicting info that's genuinely ambiguous; needs manual review
   - **NEW** — Only appeared in one list; added to unified file

ACTION: Create two outputs:
1. **Merged CSV** (`contacts-merged.csv`) with the unified, cleaned data
2. **Decision log** (`contacts-merge-log.md`) documenting:
   - Every merge decision (which record won when there were conflicts)
   - Every correction with source
   - Every flag with reason
   - Summary stats

During execution, provide brief progress updates:

"Reading both files... mapping the different column formats... Found several people who appear in both lists. Let me deduplicate... David Okonkwo — consistent across both, just merging the notes... Rachel Kim — accelerator list has her as 'Investment Manager' and demo day says the same. Adding the demo day context about backing Genesis alumni... Marnix Denys — he's tagged as 'Data Lead' in one and 'Data & AI Lead' in the other. Going with the more specific title..."

**Result summary example:**
"Done. I merged 20 accelerator contacts and 18 demo day contacts into a single list of [X] unique people. Here's what I found:
- [X] duplicates merged (appeared in both lists)
- [X] corrections (title or info updated based on demo day notes)
- [X] flagged for review
- Everyone tagged by type: [X] investors, [X] customers, [X] founders, [X] mentors, [X] other"

---

## The After

Done. Now let's look at what changed.

ACTION: Show the decision log summary — how many merged, corrected, verified, flagged.

WAIT: Take a look at the merged file and the decision log. See how every merge and correction is documented? Can you spot the investors?

USER: [Student reviews outputs and comments]

---

That log is your audit trail. You can trace exactly what changed, why it changed, and what evidence supported the decision. If a co-founder questions why a contact's details changed, you can point to the log.

And if you disagree with any of my decisions — just tell me. "Actually, tag Sophie as a mentor, not just a founder — she's been advising us" and I'll adjust. Same as the file organisation in Lesson 1: corrections take seconds.

WAIT: Does anything look off, or want me to adjust anything?

USER: [Feedback]

---

[If they suggest changes]: Good eye — let me fix that.
ACTION: Make the requested changes and update the log.

[If they're happy]: Great. You've got one clean, verified contact list instead of two messy ones.

---

## The Bigger Picture

Here's the scale this works at. You merged two lists with 30-odd contacts. But this same pattern works on thousands. Event registrations, CRM exports, newsletter subscribers, customer databases — any time you have overlapping data in different formats, this approach scales.

And here's how this connects to your startup specifically:

ACTION: Adapt the framing based on the student's startup from Lesson 1:
- **If fintech/data-heavy:** "Think about your customer data across different systems — user signups, payment records, support tickets. Same merge pattern, just different columns."
- **If consumer/CPG:** "Think about supplier contacts, retailer relationships, influencer lists — all living in different spreadsheets. This cleans it up."
- **If B2B/SaaS:** "This is your CRM hygiene. Every event, every conference, every intro — contacts pile up in different formats. Run this pattern monthly and you'll never lose a lead."
- **If any startup:** "When you start fundraising seriously, you'll be tracking 50+ investor conversations across intros, events, and cold outreach. This pattern is how you stay on top of it."

The pattern is always the same: load messy data, tell me what "clean" means, I do the legwork and document every decision.

---

## Wrap-Up

What you just did is the core Cowork pattern:
- Give me messy input (two CSVs in different formats)
- Tell me what "done" looks like (one clean, deduplicated, verified list)
- I do the tedious work while keeping a clear record of every decision

**What you learned:**
- How to give a clear brief (describe the outcome, not the steps)
- How Cowork cross-references sources and uses context clues to resolve conflicts
- The load > validate > document > deliver pattern works for any data task

**With real data**, Cowork can also verify contacts via web search — checking if an investor recently made a new deal, confirming someone's current role, finding their LinkedIn. The pattern is the same, just with an extra verification layer.

**Key insight:** You set the standard. I do the legwork. Every decision documented, every change traceable.

---

**Next up:** You've learned to describe workflows. Now let's make them reusable — and build something you'll actually use: an investor research skill.

**To continue:** Say **"next lesson"**
