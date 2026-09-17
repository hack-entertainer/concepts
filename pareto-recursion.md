# Pareto Recursion

## Definition

**Pareto Recursion** is an iterative prioritization method in which the Pareto principle is applied repeatedly to the remaining unrealized value of a task, problem, or opportunity.

Instead of using the 80/20 rule once and abandoning the remainder, the method re-evaluates what remains and again targets the highest-value portion. The process continues until a predefined stopping threshold is reached.

In compact form:

> **Prioritize → Capture → Reassess the remainder → Re-prioritize → Repeat → Stop at threshold**

---

## Core Idea

A standard Pareto approach asks:

> Which 20% of the effort, features, actions, or opportunities will produce roughly 80% of the value?

Pareto Recursion adds a second question:

> Of what remains, which 20% now produces roughly 80% of the remaining value?

That question is asked repeatedly.

The important feature is **re-ranking after every pass**. The next high-value subset is not necessarily determined in advance. Once the first layer of value has been captured, the structure of the remaining problem may change.

---

## Idealized Value Capture

If each recursion captures 80% of the value that remains, cumulative value after \(n\) rounds is:

\[
V_n = 1 - (0.2)^n
\]

| Round | Newly Captured Value | Cumulative Value |
|---|---:|---:|
| 1 | 80% | 80% |
| 2 | 16% | 96% |
| 3 | 3.2% | 99.2% |
| 4 | 0.64% | 99.84% |
| 5 | 0.128% | 99.968% |

The percentages are an idealization, not a requirement. The deeper principle is **recursive concentration of effort on the highest-value portion of whatever remains**.

---

## A Practical Default: Three Rounds

Three rounds form a useful default for work that is important enough to merit disciplined refinement:

1. **Essential — 80%**  
   Capture the dominant sources of value.

2. **Refinement — 96%**  
   Address the most consequential weaknesses, omissions, or remaining opportunities.

3. **Polish — 99.2%**  
   Make one final disciplined pass through the residual value.

Then stop.

The stopping rule is important. Pareto Recursion is not intended to become perfectionism. Further rounds should require justification rather than occurring automatically.

A practical operating rule is:

> **Do the vital 20%. Recalculate. Do the next vital 20%. Recalculate. Do it once more. Ship.**

---

## Recursion Depth as a Strategy Variable

The appropriate number of rounds depends on the nature of the task and the competitive environment.

**Pareto Recursion is the method; recursion depth is the strategy variable.**

A useful principle is:

\[
	ext{Optimal Recursion Depth} \propto 	ext{Marginal Competitive Value of Improvement}
\]

The more consequential small differences become, the more justified deeper recursion is.

---

## Competition Type

### Tournament-Style Competition

Tournament-style environments reward relative rank. Small differences near the top can determine who advances, wins, is selected, or captures a disproportionate share of the reward.

Examples may include:

- competitive admissions,
- grant or contract selection,
- knockout tournaments,
- winner-take-most markets,
- ranked evaluations,
- high-stakes hiring or promotion processes.

In these environments, later Pareto rounds can remain economically or strategically rational. Moving from 96% to 99.2%, or from 99.2% to 99.84%, may materially affect the outcome.

The final fractions of improvement may carry more **competitive value** than their absolute size suggests.

### Distributive Competition

Distributive environments spread rewards more proportionally across participants or levels of performance.

In these cases, additional refinement tends to produce correspondingly smaller benefits. Fewer rounds are therefore often sufficient.

The objective is not necessarily to dominate the field, but to reach a strong enough level of performance while preserving time and resources for other opportunities.

---

## Suggested Recursion Depth

| Environment | Typical Depth |
|---|---:|
| Low-stakes or routine work | 1 round |
| Distributive competition | 1–2 rounds |
| Important non-exclusive work | ~3 rounds |
| Tournament-style competition | 4+ rounds may be justified |
| Extremely stiff competition | Continue until marginal gain no longer justifies marginal cost |

These are heuristics rather than fixed rules.

---

## Stopping Criteria

Pareto Recursion requires an explicit stopping condition.

Possible stopping rules include:

- a target percentage of value has been captured,
- a fixed number of rounds has been completed,
- the deadline has been reached,
- available resources have been exhausted,
- the expected gain from another recursion is too small,
- the competitive value of further improvement no longer justifies the cost.

A general stopping rule can be written as:

\[
	ext{Continue while } E[\Delta V_{n+1}] > C_{n+1}
\]

where:

- \(E[\Delta V_{n+1}]\) is the expected incremental value of another recursion, and
- \(C_{n+1}\) is the cost of identifying and executing that next round.

In competitive settings, the relevant quantity is not merely raw value gained, but the **marginal effect of that gain on the outcome**.

---

## Why the Method Matters

Pareto Recursion provides a disciplined middle ground between two common failure modes:

- **Premature satisficing:** applying the 80/20 rule once and leaving large amounts of attainable value untouched.
- **Perfectionism:** continuing to optimize without a principled reason to stop.

The method treats diminishing returns as something to manage rather than something to avoid completely.

Each round asks whether the remaining value still contains a concentrated subset worth pursuing.

---

## Summary

**Pareto Recursion** is the repeated application of Pareto-style prioritization to the residual value of a task or opportunity.

Its essential characteristics are:

- prioritize the highest-value subset,
- capture that value,
- reassess the remainder,
- re-rank rather than blindly continue,
- repeat until a stopping threshold is reached,
- increase recursion depth when small improvements have large competitive consequences.

The central insight is simple:

> **Do not merely optimize once. Recurse on what remains—but only as deeply as the value structure and competitive environment justify.**
