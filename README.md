# 🎓 Research Topic Architect

> A 5-stage AI skill built with Claude that helps students move from a vague idea to a sharply defined, highly significant, and future-relevant research topic.

---

## What This Is

**Research Topic Architect** is a custom Claude AI skill — not just a prompt, but a structured, logic-driven academic tool designed for educators and researchers who supervise students at the topic-selection stage.

It was built to solve two persistent problems in academic supervision:

- **Herd mentality** — students copying peers instead of thinking independently
- **Research illiteracy** — students who don't understand methodology well enough to evaluate or develop their own topic

---

## The 5-Stage Process

| Stage | Name | What It Does |
|-------|------|-------------|
| **0** | Mindset & Readiness Check | Detects herd mentality + assesses research literacy before touching the topic |
| **1** | Topic Clarification Funnel | Uses a 4-W framework to sharpen a vague idea into a focused topic statement |
| **2** | Scholarly Significance Audit | Scores the topic on 5 criteria (Gap, Novelty, Impact, Scope, Timeliness) out of 20 |
| **3** | Horizon Score | Evaluates futuristic value using the FUTURE framework, scored out of 24 |
| **4** | Research Literacy Scaffold | For novice students — teaches methodology using their own topic as the example |

---

## The FUTURE Framework (Stage 3)

Assesses whether a research topic will still matter 5–15 years from now:

| Letter | Dimension |
|--------|-----------|
| **F** | Field Trajectory — is this where the discipline is heading? |
| **U** | Underexplored Frontier — does it sit at the edge of current knowledge? |
| **T** | Technology Relevance — does it engage with emerging tools or methods? |
| **U** | Urgency Signal — is there a growing societal or institutional pressure? |
| **R** | Replicability Potential — could it seed further research programmes? |
| **E** | Educational/Policy Echo — could findings reach curriculum or policy? |

**Score interpretation:** 20–24 = Visionary · 14–19 = Forward-leaning · 8–13 = Present-focused · ≤7 = Retrospective

---

## What the Student Receives

At the end of the process, the student gets a **Research Topic Architecture Report** containing:

- Refined topic statement + working academic title
- Scholarly Significance Score (X / 20) with per-criterion feedback
- Horizon Score (X / 24) with futuristic value verdict
- Methodology recommendation matched to their topic
- Final recommendation: **Proceed as is / Refine first / Reconceptualize**

---

## How to Use

This skill is designed for the **Claude AI** platform (claude.ai).

1. Open a new conversation in Claude
2. Use `/research-topic-architect` or paste the contents of `SKILL.md` as your system prompt
3. Start with: *"Please help me shape my research topic"*

Claude will guide you through all 5 stages automatically.

---

## Who It's For

- **Students** at undergraduate, postgraduate, or doctoral level — in any academic field
- **Supervisors and educators** who want an AI-assisted scaffolding tool for topic development
- **Researchers** exploring a new area and wanting to validate significance before committing

---

## Files

```
research-topic-architect/
├── SKILL.md        # The full skill — paste this as your Claude system prompt
└── README.md       # This file
```

---

## Built With

- [Claude](https://claude.ai) by Anthropic — AI foundation
- Designed by **Tiantian (Tianqi Gao)**, doctoral researcher in Music Education, UPSI Malaysia
- Frameworks: 4-W Clarification Funnel · Significance Audit · FUTURE Horizon Score · Research Literacy Scaffold

---

## License

MIT License — free to use, adapt, and share with attribution.

---

## Contact

If you are an educator or researcher interested in building your own Claude AI skills for teaching, feel free to open an issue or reach out.
