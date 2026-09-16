# 🕵️‍♂️ 15-minute discussion guide: AI risk forensics

Facilitator run-of-show for either forensics deck. Hand out [study-guide.md](./study-guide.md) as the pre-read; this file times the session.

- [Five-AI-Risks-Forensics-Essential-Questions-and-Insights-compressed.pptx](./Five-AI-Risks-Forensics-Essential-Questions-and-Insights-compressed.pptx) (17 slides)
- [Five-AI-Risks-Forensics-Detective-Material-Merge-compressed.pptx](./Five-AI-Risks-Forensics-Detective-Material-Merge-compressed.pptx) (19 slides, same material with persistent detective-noir artwork)

Both decks cover the 5 essential questions (Part 1) and the non-obvious insights (Part 2), drawn from
[the video](https://www.youtube.com/watch?v=1m55T8xST9s),
[five-essential-questions.md](./five-essential-questions.md), and
[non-obvious-insights.md](./non-obvious-insights.md).

### 1. Opening: the case brief (0:00 to 2:00)

- Detective framing: the team is the forensics unit, reopening five closed cases where well-meaning employees ended their own careers. Each case starts the same way: someone trying to be productive.
- Discussion hook: "Raise your hand if you have ever seen a personal AI tool or browser extension and wished our official toolkit had that feature built in. That gap between convenient personal tech and slow corporate vetting is where shadow AI temptation takes root."
- Core premise: careers go sideways where AI runs without proper governance or human verification. Two breakdowns drive every case: governance (no approved tools, no visibility into data flows) and verification (personal credibility attached to unvalidated outputs).

### 2. Part 1: the five essential questions (2:00 to 8:00)

Walk the deck's Part 1 slides, one question per stop. Keep each to about a minute; the slides carry the detail.
- Question 1, central theme: careers end where governance and verification break down. Accountability lands on the human who submitted or deployed, never the model.
- Question 2, the five risk vectors: shadow AI, data leakage, hallucination laundering, prompt injection (direct and indirect), unauthorized agentic AI including zombie agents. Name each vector and its distinct threat; the deck slides give the one-line version.
- Question 3, facts and evidence: the 1-in-5 breach stat, irreversible model baking, the lawyers with fabricated citations and executives deciding on unverified output, agents deleting files or emailing without a human in the loop.
- Question 4, purpose and the anti-ban stance: the author wants productivity without termination. Bans drive shadow AI underground and cost all visibility; governance plans with approved tools, use cases, and data boundaries are the fix.
- Question 5, implications: your name is on the deliverable, so individual accountability stays with you. IT owns the governance gap and the agent inventory. Refusing AI is its own career risk.
### 3. Part 2: non-obvious insights and tensions (8:00 to 12:00)

Walk the deck's Part 2 slides. These go beyond the video; slow down here.

- Inferred insights: productivity itself is the attack vector, since top performers optimizing workflows cause most incidents. Verification is structurally bottlenecked because output scales exponentially while auditing stays linear, so rubber-stamping becomes the default. Agents shift identity management from people to scripts, with ephemeral entities keeping API keys after projects end. Approving tools shifts risk rather than removing it, since sanctioned RAG apps still swallow indirect prompt injections.
- Tensions: ungoverned use ends careers, yet refusing AI ends them too. Bans keep 100% of the risk while losing 100% of the visibility. The org banks the efficiency gains while the employee absorbs the career risk for unverified output.
- The one takeaway: human verification and explicit credential management bound professional liability. AI adds leverage; oversight decides survival.

### 4. Closing and team discussion (12:00 to 15:00)

- Wrap-up question for the group: "Which of these five risks is our team's biggest blind spot today, and what verification step should we implement first?"
- If time allows, a second question from the open list: "Who owns our agent inventory, and what happens to API keys when a project ends?"
