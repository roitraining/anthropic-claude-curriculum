<!-- course-title: Claude.ai Essentials -->

<!-- layout: title -->
![ROI Logo](images/roi-logo-with-name.png)

Claude.ai Essentials

# Chapter 2: Documents, Deliverables and Trust

---

# Chapter 2: Objectives

- Upload office documents and ask grounded questions without re-briefing every chat
- Turn scattered notes into a short report and a first-look chart through iteration
- Apply data-handling guardrails and catch plausible-but-wrong answers before they travel

---

<!-- layout: navigation -->
# Chapter 2

- **Working with Files and Data Safely**
- From Messy Notes to a Polished Deliverable
- Trust, Data and Guardrails

---

# Upload Once, Ask Many Questions

- **Thesis**: File upload turns Claude from a blank chat into a grounded work session
- Use a real office document: policy, report excerpt, contract summary or meeting pack
- Ask questions that require the file—not questions Claude could invent from general knowledge
- Cite or quote the passage you relied on before you reuse the answer downstream

<!-- TODO IMAGE: Screenshot of Claude.ai chat with a document uploaded and a grounded question -->
![Document upload in Claude.ai](images/ch02-file-upload.png)

---

<!-- layout: 2-column -->
# Safe Use versus High Risk

### Safer patterns
- Public or approved internal docs per policy
- Redact names, IDs and secrets first
- Prefer Projects for recurring file sets
- Human review before customer send

### High-risk patterns
- Raw proprietary IP "just to try"
- Personal data, health or payroll detail
- Credentials, keys or full contracts when banned
- Blind trust because the tone sounds official

<!-- below-columns -->

> [!WARNING]
> "It is only a draft" is not a control. Once text leaves Claude, it can be forwarded, pasted or screenshotted.

---

# Projects Keep Related Files Together

- **Thesis**: Re-uploading the same pack every Monday wastes time and invites version mistakes
- Store the standing brief and reference files in a Project
- Start each recurring chat inside that Project so context travels with you
- Retire or replace stale files when the source of truth changes

> [!TIP]
> Name Projects by outcome and cadence: "Monthly ops digest" beats "New Project."

---

<!-- layout: navigation -->
# Chapter 2

- Working with Files and Data Safely
- **From Messy Notes to a Polished Deliverable**
- Trust, Data and Guardrails

---

# The Deliverable Chain

- **Thesis**: Today's power move is a chain, not a single clever prompt
- Scattered notes or files → consolidated summary → short report → optional chart
- Each step is a separate ask with a clear output shape
- Iteration beats one giant "do everything" prompt that mixes goals

![From messy notes to deliverable](images/ch02-deliverable-chain.svg)

---

# Step 1: Summarize Scattered Sources

- **Thesis**: Summarize each source for facts first—opinions second
- Upload two or three short sources (notes, emails, a spreadsheet export)
- Ask for a consolidated bullet brief: decisions, owners, dates, open questions
- Require Claude to flag conflicts between sources instead of silently picking one

```text
Objective: Consolidate these three notes into one bullet brief.
Include: decisions, owners, dates, open questions, conflicts between sources.
Constraints: No new recommendations. Quote source labels for contested facts.
```

---

# Step 2: Draft the Short Report

- **Thesis**: Promote the brief into a report with audience and length constraints
- Specify reader (manager, client, cross-team) and section headings up front
- Ask for a first draft, then a tightening pass: shorter, clearer, fewer hedges
- Keep human ownership of recommendations and numbers that bind the business

> [!IMPORTANT]
> Numbers that will be forwarded need a source check. Claude can misread tables even when the prose sounds polished.

---

# Step 3: Add a First-Look Chart

- **Thesis**: Claude can render a basic chart in chat when the data is clear enough
- Use a bar or line chart for a single comparison students can verify by eye
- Tell Claude the exact series, labels and what the chart must not imply
- Treat the chart as a first look for discussion—not a board-ready graphic by default

<!-- TODO IMAGE: Screenshot of Claude.ai chat showing a simple bar or line chart rendered in the reply -->
![Chart rendered in Claude.ai chat](images/ch02-chart-in-chat.png)

---

# End to End: Watch the Skills Connect

- **Thesis**: One live chain teaches more than four isolated tips
- Instructor runs notes → summary → report paragraph → chart in one thread
- Students watch how each POCC brief stays narrow on purpose
- Pause after each hop: what improved, what still needs a human check

> [!NOTE]
> Lab muscle from Chapter 1 powers this demo. Weak prompts make the chain wobble; strong briefs keep each hop on rails.

---

<!-- layout: navigation -->
# Chapter 2

- Working with Files and Data Safely
- From Messy Notes to a Polished Deliverable
- **Trust, Data and Guardrails**

---

# Where Does Our Data Go?

- **Thesis**: Answer with current product practices and your org policy—not hallway rumor
- Consumer and commercial or team plans can differ on training and retention defaults
- Connectors, Projects and uploaded files expand what is in scope for a chat
- Instructors should state the plan tier used in class and point to official Anthropic docs

> [!IMPORTANT]
> Policies change. Prefer official Claude documentation and your security team's guidance over memorized slides.

---

# Plausible but Wrong

- **Thesis**: The dangerous answer is fluent, specific and slightly false
- Watch for invented dates, policy clauses, citations and "helpful" numbers
- Cross-check anything that commits money, legal language, customer promises or compliance
- Build a 60-second human-in-the-loop habit before the reply leaves your desk

---

<!-- layout: 2-column -->
# Human-in-the-Loop Checklist

### Check before you send
- Does every hard fact appear in a source?
- Are names, dates and figures exact?
- Did Claude add promises you did not authorize?

### Stop and revise if
- The tone is right but the citation is missing
- Two sources disagree and Claude picked silently
- You would not sign the email yourself

---

# What Claude.ai Does Not Do Alone

- **Thesis**: Nothing happens without a prompt—and nothing ships without a human
- Claude does not browse your laptop, send email or change systems by itself in this web workflow
- Autonomy grows in Desktop, Cowork and Code—with clearer review steps in those courses
- Your judgment stays the control plane for office work today

> [!TIP]
> When someone says "Claude decided," translate it to "Someone accepted a Claude draft." Ownership stays human.

---

# Supplemental Lab (Take-Home): Fact-Checking and Grounding

**Time:** 30 minutes (after class)

---

# What You Learned

- Uploaded office documents and asked grounded questions without re-briefing every chat
- Turned scattered notes into a short report and a first-look chart through iteration
- Applied data-handling guardrails and practiced catching plausible-but-wrong answers

---

# Quiz 1 of 3

**You need a weekly digest from the same three reference PDFs. What is the best Claude.ai habit?**

- A. Paste the full PDFs into a new chat every Monday and delete history afterward
- B. Keep the files and standing instructions in a Project and start each digest chat there
- C. Upload the PDFs once to any random chat and never open Projects
- D. Ask Claude to invent the digest from memory so files never leave your machine

---

# Quiz 1 — Answer

**You need a weekly digest from the same three reference PDFs. What is the best Claude.ai habit?**

**Correct: B.** Keep the files and standing instructions in a Project and start each digest chat there

- Projects reduce re-upload friction and version confusion
- Standing instructions keep POCC constraints consistent week to week
- You still refresh files when the source of truth changes
- Org policy still governs which PDFs may be uploaded

---

# Quiz 2 of 3

**Which output is the highest priority for a human fact check?**

- A. A synonym suggestion for a subject line
- B. A customer email that states a new delivery date and partial refund
- C. A rewrite that only shortens sentences without changing facts
- D. A list of optional section headings for an internal outline

---

# Quiz 2 — Answer

**Which output is the highest priority for a human fact check?**

**Correct: B.** A customer email that states a new delivery date and partial refund

- Commitments, money and dates bind the business
- Fluent tone does not prove the facts were authorized
- Low-stakes wording tweaks still deserve a skim—but commitments come first
- When unsure, require a source quote before send

---

<!-- layout: 2-column -->
# Quiz 3 of 3 — Discussion

### Prompt
Claude summarizes two meeting notes and a spreadsheet export into a manager report with a chart.

### Discuss
- Where could "plausible but wrong" hide in that chain?
- What would you verify in five minutes?
- When would you refuse to upload a file at all?

---

<!-- layout: 2-column -->
# Quiz 3 — Discussion Points

**Claude summarizes two meeting notes and a spreadsheet export into a manager report with a chart.**

### Strong Answers Mention
- Conflicting notes, misread totals, chart scale that overclaims
- Spot-check figures against the spreadsheet; confirm owners and dates
- Refuse uploads that violate policy or contain raw personal data

### Watch For
- "The chart looks professional, so the numbers are fine"
- Skipping conflict flags between sources
- Uploading everything because the Project feels private enough

---

# Questions and Answers

Questions?
