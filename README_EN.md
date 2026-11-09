# Resume Writer

A resume writing skill for turning verified experience into clear, role-relevant evidence. It helps surface a concise personal summary, structure work and project experience around goals, actions, and outcomes, and remove low-value content without inventing claims.

## What it does

- Audits a resume for clarity, relevance, and evidence.
- Selects up to three supported points for a personal summary.
- Rewrites work, internship, and project descriptions with context, personal contribution, deliverables, and outcomes.
- Tailors emphasis to a job description when one is provided.
- Makes length decisions based on relevance and readability instead of a fixed one-page rule.
- Flags missing facts and metrics for the candidate to verify.

## Install

With the Skills CLI:

```bash
npx skills add xozhuuu/resume-writer
```

After publishing, the repository will be available at [github.com/xozhuuu/resume-writer](https://github.com/xozhuuu/resume-writer). The Skills CLI can install the skill into supported coding agents.

For Cursor, clone or copy this directory into the project's `.cursor/skills/resume-writer/` directory. Keep `SKILL.md` and the `references/` directory together.

## Use

Explicit invocation:

```text
Use $resume-writer to review my resume for this product analyst role. Keep all claims factual.
```

Natural language:

```text
请按这份 JD 帮我修改简历，优先突出最相关的项目经历，并标出需要我核实的数据。
```

```text
帮我把这段实习经历整理成“目标、行动、结果”的结构。不要补造我没提供的信息。
```

## Project layout

```text
resume-writer/
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── review-checklist.md
    └── examples.md
```

## Scope

This skill focuses on resume content and structure. It does not require a photo, a fixed page count, or a particular email provider. It does not fabricate metrics, responsibilities, or individual ownership of team outcomes. Layout and personal information should follow the candidate's preferences and the application requirements.

## License

MIT. See [LICENSE](LICENSE).
