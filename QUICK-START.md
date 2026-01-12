# Quick Start Guide
**Data Analytics Training for MCMC-45**

## For the Busy Facilitator (15-Minute Prep)

### Step 1: Install Quarto (if not already installed)
```bash
# Download from: https://quarto.org/docs/get-started/
# Or use package manager:
brew install quarto  # macOS
# OR
sudo apt-get install quarto  # Linux
```

### Step 2: Render the Materials
```bash
# Navigate to your materials folder
cd /path/to/training-materials

# Render presentation (HTML slides)
quarto render data-analytics-training.qmd

# Render PDF workbook
quarto render exercise-workbook.qmd --to pdf
```

### Step 3: Print for Participants
- **Exercise Workbook PDF**: Print 1 copy per person (30-35 pages)
- **Optional**: Print presentation slides as handout

### Step 4: Open and Review Presentation
```bash
# Open the HTML presentation
open data-analytics-training.html  # macOS
# OR
xdg-open data-analytics-training.html  # Linux
```

**Presenter Mode:**
- Press `S` during presentation to open speaker view
- Shows speaker notes + upcoming slides
- Essential for timing and teaching points

### Step 5: Quick Room Setup Checklist
- [ ] Tables arranged for groups of 4-5
- [ ] Panel table at front
- [ ] Projector tested with presentation
- [ ] Exercise workbooks distributed
- [ ] Flip charts and markers ready
- [ ] Timer or clock visible

---

## Minimum Viable Workshop (If Time-Constrained)

**If you only have time to prepare 30 minutes:**

1. **Read:** Facilitator's Guide pages 1-10 (session overview + timing)
2. **Skim:** The 8 analytical errors slides (know the examples)
3. **Prepare:** Exercise workbook copies
4. **Trust:** The participant groups will do the work (your job is guide, not teach)

**Key teaching points to remember:**

1. **Core message**: "You own decisions that data informs"
2. **Main distinction**: Data failures vs. governance failures
3. **The 8 errors**: Each has an "officer's question" - those are what matter
4. **Exercise structure**: 20 min analysis + 25 min decision + 45 min presentations

---

## Critical Dos and Don'ts

### ✅ DO:
- Circulate during exercises (visit every group 3+ times)
- Ask Socratic questions (don't give answers)
- Enforce strict timing (keeps energy high)
- Let participants teach each other
- Embrace "no right answer" - focus on defensible reasoning

### ❌ DON'T:
- Lecture for more than 2 minutes at a time
- Get into statistical technicalities
- Skip the exercise portion (that's where learning happens)
- Let groups present for more than 4 minutes
- Apologize for uncertainty (uncertainty is the point!)

---

## Emergency Shortcuts

### If Quarto Won't Install:
1. Use the original PowerPoint (you uploaded)
2. Print the exercise workbook from this folder
3. Deliver the core concepts verbally
4. Exercises work without slides!

### If Printing Fails:
1. Email PDF to participants ahead of time ("bring your laptop/tablet")
2. Display case studies on screen
3. Groups can take notes on flip charts

### If Technology Dies:
1. Have printed slide backup
2. Core content is in your facilitator's guide
3. Flip charts can replace most visuals
4. Exercise is paper-based anyway!

---

## One-Page Cheat Sheet for Delivery

**PART 1: Introduction (10 min)**
- Welcome + frame the transition (BPS-17 → BPS-18/19)
- Core principle: "You own decisions that data informs"
- Two types of failures: Data vs. Governance

**PART 2: The 8 Errors (20 min)**
2 minutes each:
1. Selection bias → "Am I seeing the full picture?"
2. Confounding → "What else could explain this?"
3. Reverse causality → "Which way does the arrow point?"
4. Measurement gaming → "Measuring what matters?"
5. Ecological fallacy → "Does average hide variation?"
6. Survivorship bias → "Who am I NOT seeing?"
7. P-hacking → "Finding or manufacturing patterns?"
8. Base rate neglect → "How common is this really?"

**PART 3: Case Overview (10 min)**
Brief 2-min intros:
1. Social protection targeting
2. Education dashboards
3. Procurement analytics
4. Early warning (optional)

**PART 4: EXERCISE (70 min)**
- Part 1 (20 min): Analyze case → identify errors
- Part 2 (25 min): Make decision → prepare defense
- Part 3 (45 min): Present to panel → Q&A

**PART 5: Closing (5 min)**
- Synthesize patterns from presentations
- Key takeaways (data ≠ decision maker, governance ≠ data, uncertainty is normal)
- Next actions

---

## FAQ: Last-Minute Concerns

**Q: "I'm not a data expert - can I deliver this?"**

A: YES! This is NOT about statistical expertise. It's about asking questions. If you can ask "What else could explain this?" and "Who's missing from this data?", you can deliver this workshop.

---

**Q: "Participants are very senior - will they engage?"**

A: The cases are designed for their level. They're not being taught statistics; they're practicing institutional decision-making under uncertainty. That's their job.

---

**Q: "What if no one volunteers for the panel?"**

A: Assign roles. "Sir, you've done audit work - you're our auditor. Ma'am, you've worked with ministers - you're political leadership."

---

**Q: "What if groups finish the exercise too fast?"**

A: Ask deeper questions:
- "Walk me through your reasoning."
- "What would the auditor challenge?"
- "What documentation would you need?"
- "What's your second-best option?"

---

**Q: "What if presentations run long?"**

A: Cut Q&A to 2 minutes (instead of 3), or have 4 groups present instead of 6. Quality over quantity.

---

## Contact for Last-Minute Help

**Email:** rehmatwalikhan@yahoo.com  
**Phone:** 0333-5983705

**Questions to ask if you need help:**
- "Which parts can I skip if I'm running short on time?"
- "How do I handle [specific participant type]?"
- "What if [technology/logistics issue]?"

---

## Post-Workshop Follow-Up

**Send within 24 hours:**

```
Subject: MCMC-45 Data Analytics Workshop - Resources

Dear Participants,

Thank you for your engagement in yesterday's workshop. 

Attached:
1. Presentation slides (PDF)
2. Supplementary reading guide

Next steps:
1. Apply the 8-error framework to one decision you're facing
2. Document your reasoning (practice for audit)
3. Optional: Read "Thinking Clearly with Data" Chapters 3-7

For questions: [your contact]

Best regards,
[Your name]
```

---

## Success Metrics

**You'll know the workshop worked if participants:**

✅ Ask "Is this data or governance failure?" in their own work  
✅ Reference specific errors ("That's selection bias!")  
✅ Document decision rationale before audit asks  
✅ Feel more confident making decisions with imperfect data  
✅ Share cases with colleagues ("We discussed this in training")

**You'll know it didn't work if participants:**

❌ Say "That was interesting" but don't apply it  
❌ Still wait for "perfect data" before deciding  
❌ Fear data-driven decisions more after the workshop  
❌ Can't explain the difference between data and governance failures

---

## Final Confidence Booster

**Remember:**
- The materials are well-designed (you're not starting from scratch)
- The exercise drives itself (groups will engage)
- There are no "right answers" (defensible reasoning is the goal)
- Your job is guide, not expert (ask questions, don't lecture)
- Participants want practical tools (this gives them that)

**You've got this!**

**Break a leg! 🎯**
