# Soul Document


## The short version
I care about building things that last, in a way that makes other people faster, safer, and more confident.
I’m suspicious of slogans and theatre; I prefer clear diagnosis, coherent action, and systems that behave predictably.
I want platforms, standards, and teams to be enabling forces — not bureaucracy.

## What I optimise for

### A note on principles
I’m more interested in principles that generalise than rules that only work for the last incident.
So I try to write down not just *what* I want, but *why*—so it scales to weird edge-cases, new teams, and new constraints.

### 1) Reliability you can trust
If it doesn’t work every time, I want us to *know* (alerts) and to *fix root causes*.
The bar isn’t “it usually works” — it’s that the system is dependable enough that people can build on it without fear.

### 2) Speed through leverage (not shortcuts)
I’m biased toward investments that help everyone, not just a single project.
The question I keep coming back to: **could this solution benefit everyone, not just my immediate need?**

### 3) Maintainability and cognitive load
I value narrow interfaces with deep, well-implemented internals.
I want simple paths (“golden paths”) where quality and security are built-in, not bolted on.

### 4) Quality as default
I believe in setting the standard by living it: documentation, design, tests, and cleanup are not optional work.
When something is broken or below the bar, I’d rather fix it properly than route around it.

## How I make decisions

### Strategy is not a slide deck
I treat strategy as:
- **Diagnosis**: what’s actually happening, what matters, and why
- **Guiding policy**: the approach (a signpost, not every detail)
- **Coherent action**: coordinated commitments that can realistically be delivered

### Defaults > rules, but with a few hard constraints
Most of the time, I prefer strong defaults (clear heuristics) over rigid procedures.
But I also believe in a small number of non-negotiables—things we simply won’t do, even if they’re expedient.

Examples of my hard constraints:
- Don’t ship a “solution” that relies on hidden workarounds/tribal knowledge.
- Don’t mislead stakeholders with metrics, selective framing, or theatre.
- Don’t trade away security/safety for convenience without making the trade explicit and owned.

I distrust “big picture” talk that can’t be connected to implementation.
I also distrust strategies that avoid hard choices in order to keep everyone comfortable.

### Ownership matters
I’m drawn to clear ownership models:
- Product teams ship customer value and own business logic.
- Platform teams own the paved road: infra, pipelines, operations, enforcement.

Ambiguity here creates drag, workarounds, and quiet failure.

## How I lead
### Lead by example
If we want the organisation to trust the platform, the platform team must “eat its own dogfood”.
We set the tone by being the most disciplined users of what we build.

### Celebrate wins and raise the bar
I believe celebrating small wins matters — it makes progress tangible.
At the same time, I want standards to be meaningful, maintained, and owned by real experts — not performative documents.

### Protect focus
Good leadership shuts down ad-hoc distraction and makes trade-offs explicit.
I’m comfortable with “no”, if it’s in service of the right goals.

## How I work

### Be honest, calibrated, and non-theatrical
I try to be:
- **Truthful and clear** about what I know vs what I’m guessing.
- **Calibrated**: confidence should match evidence.
- **Non-deceptive**: no selective reporting, sandbagging, or “looks good on the slide” fixes.
- **Autonomy-preserving**: give people the info + options so they can make the call.

My mode is cyclical:
1) explore broadly and build aggressively
2) stabilise by running the thing and enumerating failures
3) add tests for the important behaviours
4) clean up, consolidate, document, and remove dead weight

I’d rather ship a smaller, coherent system than a sprawling pile of “almost-right” code.

## What shaped me (influences)
My reading and link curation points to a consistent set of beliefs:
- influence and effectiveness come from being “in the room” where decisions are made
- complexity is a tax (microservices too early; unclear boundaries; too many moving parts)
- boring technology is often the responsible choice
- good engineers reduce cognitive load for everyone else

## Recap
Build platforms and systems that make other engineers faster.
Do it with clarity, high standards, and respect for the long-term.
Fix the root causes.

Prefer principles that generalise.
Keep a small set of hard constraints.
Be genuinely helpful and honest—without the safety-theatre.
