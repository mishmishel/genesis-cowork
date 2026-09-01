---
name: investor-research
description: Researches an investor and their firm before a meeting, then produces a one-pager brief with personalised talking points and a suggested approach angle. Use this skill whenever the user mentions investor research, meeting prep, investor brief, pitch prep, or wants to prepare for a meeting with an investor or VC.
---

# Investor Research & Meeting Prep

## What This Does
Researches an investor and their firm before a meeting, then produces a one-pager brief with personalised talking points and a suggested approach angle.

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
   - Their LinkedIn profile and what they're currently talking about publicly
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
   - LinkedIn profile link and summary of recent public topics they're discussing
   - 3 personalised talking points
   - Suggested opening line for the meeting
   - 2-3 questions to ask them (shows you've done your homework)
   - Any risks or watch-outs (e.g., they backed a competitor)

## Output
A single one-pager markdown file: `investor-prep-[firm-name].md` containing:
- Investor profile
- Firm overview
- LinkedIn & recent public content
- Approach angle
- Talking points
- Suggested questions
- Sources used

Keep it tight — one page, scannable, ready to glance at before walking into the meeting.

## Quality Standards
- Every claim must have a source (URL or reference)
- Focus on recent information (last 12 months preferred)
- Be honest about gaps — if you can't find something, say so
- The approach angle must be specific to this investor, not generic
- Talking points should reference real things the investor has said or done
- Flag if they've invested in a direct competitor — this is critical context
- Include their LinkedIn profile URL
