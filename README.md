# FLUX: Rethinking Agile in the AI Era

## TL;DR
Agile solved a **coordination** problem.  
FLUX solves a **decision quality** problem in a world where AI makes execution fast and coordination cheap.

---

## Core Thesis
FLUX is built on:
1. **One diagnosis**
2. **Three structural replacements**

### The Diagnosis
Agile was designed for teams where humans were the execution bottleneck. Its ceremonies (standups, sprints, backlogs) acted as coordination mechanisms.

With AI inside the delivery pipeline:
- Execution becomes dramatically cheaper
- Coordination overhead drops
- The bottleneck shifts from **doing** to **deciding**

No classic Agile ceremony was designed to optimize decision quality, so the framework itself becomes the wrong tool for this environment.

---

## The Three Replacements

### 1) Backlog -> Attractor
**Backlog:** a queue of obligations to push through  
**Attractor:** a vivid, outcome-based description of success

Example Attractor:
> "Users complete checkout in under 90 seconds without calling support."

Why it matters:
- Not a task list
- Creates a gravitational pull toward outcomes
- Work is pulled by intent, not pushed by tickets

### 2) Sprint -> Pulse
**Sprint:** fixed timebox for predictability (often two weeks)  
**Pulse:** variable cycle length based on signal strength

How Pulse timing works:
- Clear signal + fast AI execution -> compress to ~2 days
- High uncertainty -> expand to ~1 week

Boundary question:
> Not "Did we finish?"  
> But "Did the world change?"

### 3) Roles -> Lenses
**Roles:** fixed identities (Developer, Product Owner, Scrum Master)  
**Lenses:** temporary perspectives anyone can adopt

Examples:
- Technical lens
- User lens
- Business signal lens

Why this shift works:
- AI amplifies individual capability
- One person can operate across multiple perspectives
- Static role boundaries become less necessary

---

## What AI Changes Structurally
In a traditional sprint, much of cycle time is human execution:
- Writing code
- Writing tests
- Writing documentation

In FLUX:
- AI handles most execution layers
- Humans focus on high-leverage judgment:
  - Define the Attractor
  - Evaluate architecture options
  - Validate output vs intention
  - Read post-deployment signal

Result:
- Human effort per feature can shrink from **days** to **hours**

Critical condition:
- AI must be embedded into the pipeline (PR review, test generation, Attractor analysis)
- If AI is only used ad hoc at the edges, structural gains do not compound

---

## Adoption Insight
Most methodology changes fail because they are behavioral, not structural.

Typical pattern:
- Rename ceremonies
- Keep same underlying system
- Revert to old habits within weeks

Why FLUX is different:
- AI is embedded in core workflow steps
- Returning to old behavior requires removing tools, not just changing habits
- Structure enforces behavior

This creates durable adoption lock-in, and in this context, that lock-in is beneficial.

---

## Start FLUX in 15 Minutes
Use these files to make FLUX operational immediately:

1. Define one Attractor using [playbooks/attractor-template.md](playbooks/attractor-template.md)
2. Run your first Pulse using [playbooks/pulse-check-template.md](playbooks/pulse-check-template.md)
3. Audit signal at boundary with [playbooks/signal-audit-template.md](playbooks/signal-audit-template.md)
4. Track outcomes in [metrics/flux-metrics-tracker.md](metrics/flux-metrics-tracker.md)
5. Run AI pre-analysis with [ai/attractor-analysis-prompt.md](ai/attractor-analysis-prompt.md)
6. Capture proof in a case file under [cases/README.md](cases/README.md)

Recommended first run:
- Pick one small but real production problem.
- Timebox one Pulse to 1-2 days.
- Ship only what is needed to test whether the world changed.
- Score fidelity and compression after deployment.

---

## 30-Second Explanation
> Agile was built for a world where humans were the execution bottleneck.  
> AI removed much of that bottleneck.  
> So instead of backlogs, sprints, and fixed roles, FLUX uses attractors, pulses, and lenses.  
> AI does most execution; humans do most judgment.  
> Features that used to take sprints can now ship in hours.
