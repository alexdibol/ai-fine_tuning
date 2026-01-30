# Fine-Tuning for Financial Practitioners (Governance-First)

## What this repository contains

This repository supports the book  
**Fine-Tuning for Financial Practitioners (Governance-First)** —
the sixth volume in the Governance-First AI series applied to financial
and legal professional practice.

Unlike earlier volumes, this book does **not** organize learning around
increasing model autonomy.

Instead, it organizes learning around **task classes** — each with its own
risk profile, governance burden, and training discipline.

The objective is not to make models more capable.

The objective is to make them **appropriately constrained for the task they
are trained to perform**.


## Core premise of the book

Fine-tuning is not a technical optimization step.

It is a **professional governance decision**.

Training a model determines:

• what it speaks confidently about  
• what it must refuse  
• how it expresses uncertainty  
• how it separates facts from assumptions  
• where human responsibility begins and ends  

For that reason, fine-tuning must be governed at the same level as
methodology selection, disclosure policy, and supervisory review.


## Task-oriented maturity ladder

The book replaces autonomy-based ladders with a **task-centric ladder**.

Progression is not “more intelligent behavior” —  
it is **greater semantic responsibility and disclosure exposure**.

The chapters therefore advance through task classes commonly encountered
in financial and legal institutions:

### Chapter 1 — Generative Drafting Tasks
Low-complexity generation where the model produces language but does not
interpret meaning or recommend action.

Examples:
• memo drafting  
• summaries  
• explanations of provided material  

Primary governance risk: tone drift, implied authority, hallucinated facts.


### Chapter 2 — Structured Interpretation Tasks
The model reorganizes, categorizes, or explains provided information
without introducing judgment.

Examples:
• issue mapping  
• classification  
• structured explanations  

Primary governance risk: implicit interpretation presented as fact.


### Chapter 3 — Transformational Reasoning Tasks
The model performs multi-step reasoning over supplied inputs,
while remaining prohibited from advice or recommendations.

Examples:
• scenario framing  
• trade-off articulation  
• alternative representations  

Primary governance risk: decision laundering and implied suitability.


### Chapter 4 — Advisory-Adjacent Tasks
The most dangerous boundary.

The model operates close to advisory language but must never cross into
recommendation, suitability, or prescriptive guidance.

Primary governance risk: unauthorized advice and regulatory exposure.


### Chapter 5 — Institutionalization and Release Governance
How trained models are approved, versioned, monitored, and withdrawn
inside real organizations.

Primary governance risk: silent drift, uncontrolled reuse, and loss of
accountability.


This ladder reflects **task risk**, not technical sophistication.


## Why this task-centric structure matters

Model capability will always change.

Tasks do not.

Every financial institution repeatedly faces the same question:

“What are we allowing this system to do — and what must it never do?”

By organizing training around task classes rather than models,
the framework remains stable even as base models evolve.


## Companion notebooks

Each chapter is accompanied by a Google Colab notebook.

These notebooks are **governance demonstrators**, not engineering labs.

They exist to show:

• how task scope is defined  
• how training boundaries are documented  
• how behavioral evaluation is designed  
• how violations are detected  
• how approvals are justified  
• how evidence is produced for audit  

The notebooks deliberately use small, replaceable models so that the
governance logic — not performance — remains the learning objective.


## Who this is for

This book is written for:

• financial professionals in regulated environments  
• compliance, risk, and model governance teams  
• instructors teaching applied AI responsibly  
• MBA and Master of Finance students  
• transformation leaders responsible for AI rollout  

No ML engineering background is required.


## What makes this governance-first

The framework enforces:

• strict task boundary definition  
• prohibition mapping (what the model must never do)  
• separation of generation vs verification  
• explicit uncertainty labeling  
• behavioral evaluation instead of benchmarks  
• human approval before release  
• traceable ownership and accountability  

The trained model is never treated as an authority —
only as a constrained contributor.


## Important note

This repository and book are provided for educational purposes only.

They do not constitute financial, legal, tax, or investment advice.

Human professional review is mandatory for any reliance-bearing use.

Confidential or proprietary information must never be provided to
external models.


## Position within the Governance-First series

This volume completes the Governance-First collection by moving governance
from *use* into *training itself*.

Earlier books govern how AI is prompted and applied.

This book governs how AI behavior is formed.


## License

MIT License.


## Suggested citation

Alejandro Reynoso  
*Fine-Tuning for Financial Practitioners (Governance-First)*  
Companion repository and notebooks, GitHub.


```
