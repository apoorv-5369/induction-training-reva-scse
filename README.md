# Faculty Induction Agentic Training Environment

This repository provides the skeleton for an agentic learning environment designed for newly joined faculty members. The experience is built around a daily two-hour cycle that blends self-study, creation, and reflection so that faculty can grow into confident, AI-aware educators.

## Purpose

The environment supports a guided daily routine in which faculty members:

- engage in self-study through curated videos, articles, or readings
- create instructional artifacts such as syllabi, activities, or lab plans
- complete an assimilation quiz that tests what they internalized
- receive feedback from multiple specialist agents

The humans remain in control of the daily choices. The agents act as guides, critics, assessors, and memory keepers.

## Core Experience Flow

1. Self-study
   - A facilitator introduces a relevant learning resource.
   - The faculty member explores the material at their own pace.

2. Creation
   - The faculty member develops or revises an instructional artifact.
   - The agents help refine the design through questioning and feedback.

3. Assimilation
   - A personalized quiz checks the faculty member's understanding.
   - The quiz is informed by the day's formative feedback and struggles.

4. Reflection
   - The system produces a concise daily summary for the faculty member and for leadership.

## Repository Structure

- [agents](agents/README.md): definitions for the specialist agents
- [docs](docs/README.md): documentation, workflow guidance, and planning notes
- [activities](activities/README.md): starter activity prompts and design space
- [quizzes](quizzes/README.md): quiz framework and examples
- [templates](templates/README.md): reusable templates for notes and planning
- [summaries](summaries/README.md): daily participant summaries and reflection logs

## Contributor Workflow for Multiple Faculty

Each faculty member should:

1. Fork this repository and clone their fork locally.
2. Work on the daily learning tasks in their own branch.
3. Save each day's reflection summary in the [summaries](summaries/README.md) folder using the format <name-date>.md.
   - Example: alex-2026-07-07.md
4. Create a pull request at the end of the day with their updates and summary file.

This keeps each participant's work isolated while still enabling a shared training experience.

## Agent Roles

- CS Ed Expert Agent: acts as the lead facilitator and Socratic guide
- Formative Evaluator Agent: critiques pedagogy and prompts deeper thinking
- Assimilation Quiz Engine: generates adaptive end-of-session checks
- Logging & Ledger Agent: captures progress, decisions, and growth signals

## Next Steps

This repository is intentionally scaffolded so it can evolve into a full multi-agent training platform. Future work can include:

- prompt packs for each agent
- a workflow orchestrator
- a simple web or chat interface
- storage for session logs and summaries
