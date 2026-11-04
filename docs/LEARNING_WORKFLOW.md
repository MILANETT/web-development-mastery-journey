# Learning Workflow

This document defines how the Web Development Mastery Journey is run. The [ROADMAP.md](../ROADMAP.md) remains the authoritative curriculum.

## Weekly cycle

1. **Challenge release:** A brief is added under `challenges/` with its ID, deadline, concepts, requirements, and submission instructions.
2. **Independent attempt:** Work through the task yourself before seeking a solution. Use official documentation and your own notes when appropriate.
3. **Submission:** Add your work under `submissions/<CHALLENGE-ID>/`. Include a concise `review.md` or reflection when requested by the challenge.
4. **Review:** The reviewer checks correctness, understanding, code quality, accessibility, responsiveness, usability, and any other criteria relevant to the task.
5. **Corrections:** Address feedback and record meaningful changes. A challenge is not considered complete merely because files were submitted.
6. **Progress update:** Update the progress tracker after review and correction.

The normal deadline is Sunday. The exact date and time, including timezone, will be stated in each challenge brief.

## Challenge conventions

- Use sequential IDs appropriate to the journey (for example, `WD001`, `WD002`).
- State **Concepts covered** and **Prepare for next challenge** in every regular challenge.
- Keep the brief focused on concepts already introduced or explicitly being taught.
- Do not introduce advanced tools or syntax before their prerequisites.
- After approximately 4–6 regular challenges, use a cumulative boss battle that revisits earlier concepts as well as current material.
- No marks or arbitrary scoring are required. Reviews should explain what works, what needs correction, and why.
- Challenge pace is flexible: strong demonstrated understanding can accelerate the roadmap; gaps trigger targeted practice.

## Attempt and assistance principles

- Make a genuine independent attempt first.
- Documentation, notes, browser DevTools, print/debugging tools, and experimentation are valid learning tools.
- If external help is used, make sure you can explain, adapt, and reproduce the resulting work.
- Never submit code or a design you cannot explain as your own understanding.

## UI/UX and implementation

Where relevant, reviews consider both the experience and the implementation:
- clarity of purpose and information hierarchy
- navigation and interaction
- visual consistency and responsive behaviour
- semantic structure and accessibility
- correctness, maintainability, and appropriate use of technology

Not every challenge needs to assess every criterion. Use criteria that fit the task and the learner's current level.

## Projects

Each phase should culminate in a practical milestone project. A project brief should define its purpose, users, requirements, scope, acceptance criteria, and deliverables. Larger projects should be planned before implementation.

The mother's business website is a future real-client project. Do not begin it prematurely; first establish the required UX, frontend, accessibility, testing, deployment, and client-communication foundations.

## Repository and Git conventions

- Keep the default branch stable.
- Use a separate branch for substantial challenge or project work when appropriate.
- Use clear commit messages, such as `docs: add learning workflow` or `wd001: submit responsive page`.
- Keep each challenge's submission in its own folder.
- Do not overwrite earlier work when a meaningful revision history is useful.
- Keep secrets, credentials, private keys, and personal data out of the repository.
- Update documentation when the workflow or project structure changes.

## Definition of reviewed completion

A challenge can be marked complete when:
- the required deliverables are present;
- the work has been reviewed;
- important corrections have been addressed or explicitly recorded;
- the learner can explain the main decisions and concepts.

The reviewer may recommend repeating or extending a topic before moving on.
