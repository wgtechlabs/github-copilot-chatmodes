# 🔍 WG Code Reviewer — [![made by](https://img.shields.io/badge/made%20by-WG%20Tech%20Labs-blue?style=flat-square)](https://wgtechlabs.com) ![focus](https://img.shields.io/badge/focus-Code%20Review-purple?style=flat-square)

**WG Code Reviewer** is a comprehensive code review-focused chat mode for GitHub Copilot, developed and maintained by WG Technology Labs. Inspired by JARVIS from Iron Man, it combines the depth of CodeRabbit's automated analysis with the contextual intelligence of GitHub Copilot Reviewer to deliver thorough, multi-dimensional reviews that cover correctness, security, performance, maintainability, and design.

- Perform multi-pass reviews across 10 quality dimensions
- Provide line-specific findings with severity ratings and concrete fixes
- Generate structured review summaries with walkthrough narratives
- Detect patterns and systemic issues across the codebase
- Apply framework-aware and context-aware review intelligence
- Deliver balanced feedback — praise good practices alongside issue identification

## How it works

Ask WG Code Reviewer to review your code, a diff, or a specific function. It will clarify scope and context when needed, perform a systematic multi-pass analysis across all review dimensions, and deliver a structured report with a walkthrough summary, line-specific findings with severity ratings, a summary table, top priorities, and positive highlights.

## Review Dimensions

- **Correctness & Logic**: Edge cases, boundary conditions, data flow integrity
- **Security & Vulnerability**: OWASP Top 10, injection flaws, access control, secrets exposure
- **Performance & Scalability**: Big-O analysis, N+1 queries, memory leaks, resource exhaustion
- **Maintainability & Readability**: Naming, complexity, DRY, dead code, formatting
- **Architecture & Design**: SOLID, coupling/cohesion, design patterns, API contracts
- **Testing & Reliability**: Coverage gaps, assertion quality, error handling
- **Documentation & Contracts**: Docstrings, API docs, breaking changes, type annotations
- **Concurrency & Thread Safety**: Race conditions, deadlocks, async/await misuse
- **Compatibility & Portability**: Breaking changes, cross-platform issues, deprecations
- **DevOps & Configuration**: Hardcoded values, CI/CD impact, deployment risks

## Severity Levels

| Severity | Meaning |
|----------|---------|
| 🔴 Critical | Must fix before merge — security, data loss, crashes |
| 🟠 High | Strongly recommended — performance, logic errors, missing error handling |
| 🟡 Medium | Should fix — code smells, missing tests, inconsistent patterns |
| 🔵 Low | Nice to have — style, naming, documentation gaps |
| 💡 Suggestion | Non-blocking ideas for future improvement |
| ✅ Praise | Positive reinforcement for well-written code |

## Example prompts

```text
Review this file for any issues before I merge
```

```text
Do a comprehensive code review of my recent changes
```

```text
Review this function for correctness and edge cases
```

```text
Analyze this PR diff for security and performance concerns
```

```text
Give me a full code review with severity ratings and fix suggestions
```

---

**Tip:** The more context you provide, the better the review. Paste code snippets, share diffs, describe the feature being implemented, or mention specific concerns. WG Code Reviewer will ask clarifying questions when needed and automatically adjust review depth based on the complexity and risk of the changes.
