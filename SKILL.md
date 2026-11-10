---
name: resume-writer
description: Help job seekers audit, write, and tailor resumes with role-relevant evidence, a concise personal summary, and goal-action-result experience descriptions. Use for resume writing, resume review, resume edits, personal summaries, work or project experience, or tailoring to a job description. 适用于简历撰写、简历优化、简历审阅、个人综述、工作/实习/项目经历改写和按 JD 定向调整。
---

# Resume Writer

Turn the candidate’s verified experience into a resume that a recruiter can scan quickly and discuss in an interview. Improve structure and wording without inventing facts or claiming team work as individual work.

## When to use

- The user asks to write, review, edit, shorten, or restructure a resume.
- The user asks for a personal summary or help describing work, internship, or project experience.
- The user provides a job description and asks which resume evidence to emphasize.

Do not use this skill for interview coaching alone unless the user also asks to revise resume content.

## Instructions

### 1. Gather decision-critical context

Use materials already provided. Identify the target role or job description, requested scope, output language, and format constraints. Ask concise follow-up questions only when missing facts would change the rewrite. For important claims, establish:

- The goal, problem, or context.
- What the candidate personally did and owned.
- The deliverable or outcome, with evidence or measurement period where available.
- Which outcomes belong to the wider team.

If facts are missing, draft around known facts and mark specific gaps as `[待补：...]`; do not make up numbers, ownership, employers, titles, or impact.

### 2. Diagnose before rewriting

Briefly identify the strongest role-relevant evidence and the main obstacle to understanding it. Separate weak wording from missing evidence. Lack of a numeric metric does not by itself mean an experience has no value; use verified scope, frequency, users, deliverables, process changes, or qualitative evidence where appropriate.

### 3. Put the strongest evidence early

For a full Chinese resume, include this section near the top, usually after contact details, when the candidate has relevant evidence. Use the exact heading `个人综述`; never rename it to `个人简介`, `自我评价`, or another synonym unless the user explicitly asks. Include one to three concise, role-relevant points. Prefer evidence such as relevant experience, outcomes, domain expertise, demonstrable skills, portfolio work, education/platform context, or language ability. If the available facts do not support a point, ask a focused question or mark the gap instead of inventing content. Do not replace evidence with generic traits such as “抗压能力强” or “善于沟通.”

For resumes in other languages, use a natural section title in that language unless the user specifies one.

### 4. Structure each experience

Use a short overview followed by a few themed bullets when that improves scanability:

```text
Overview: goal/problem + main approach + overall verified outcome
- Workstream: action + personal contribution/deliverable + verified result
- Workstream: action + personal contribution/deliverable + verified result
```

Keep enough context for the reader to understand the project. Make the candidate’s contribution explicit and distinguish it from team results. Do not imply causation unless evidence supports it. Use plain, concrete language; avoid task logs, unexplained abbreviations, and inflated claims.

### 5. Edit for relevance and readability

- Rank content by relevance to the target role, evidence strength, and information value.
- Do not impose a one-page limit. Use the length needed for clear, relevant evidence. If the user requests one page, prioritize and compress repeated wording before removing high-value evidence; keep text readable.
- Remove or shorten generic self-evaluations, irrelevant skill lists, lengthy coursework, and repeated personal details when they do not help the hiring decision.
- Treat job objective, photo, gender, email provider, and layout conventions as context-dependent. Follow the user’s preference and applicable application requirements; do not present any as universally required.
- List tools only when relevant, and describe proficiency through real use or outputs rather than unsupported labels such as “expert.”

### 6. Deliver and verify

Match the requested output: review, rewrite, or section-only edit. Keep the user’s facts and requested language/format. For a rewrite, include a short list of facts or metrics the user still needs to verify. Consult `references/examples.md` when a pattern example is useful, and use `references/review-checklist.md` for the final content review. Before delivery, check:

- The target role and strongest evidence are easy to find near the top.
- A Chinese personal summary section is titled exactly `个人综述`, not `个人简介` or `自我评价`.
- Each major experience has enough context, personal contribution, and outcome or deliverable.
- Team outcomes are not presented as solely individual achievements.
- Unsupported claims and invented metrics are absent; unknowns are visibly marked.
- Length and formatting preserve readability and the user’s constraints.
