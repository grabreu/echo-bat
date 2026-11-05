# echo-bat

## Repository

Flappy Bird-like 2D game in Unity (C#): a bat flying through a cave.

Read `README.md` before making changes: it documents the project pitch, tech stack, and scope. Significant, hard-to-reverse decisions are recorded in `docs/adr/`: check it before revisiting one, and add an entry when making a new one.

## General Rules

- Keep changes scoped to the requested change.
- Prefer existing patterns over introducing new abstractions.
- Do not add dependencies unless they are necessary.
- Do not fill gaps with assumptions when the user hasn't given the information: ask, or mark it as pending.
- Do not claim a validation command passed unless it was actually run.
- Code, comments, commit messages, and documentation are always written in English.
- Do not use em dashes; use a comma, colon, semicolon, parentheses, or a separate sentence instead.

## Git

- Do not create or switch branches unless explicitly requested.
- Do not create commits unless explicitly requested.
- Do not push unless explicitly requested.
- Keep commits focused on the requested change.
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/) (`type: summary`).

## Documentation

### Audience

Future-you revisiting this months later, or someone browsing the portfolio to see how it works. Not onboarding material; keep it concise and skimmable.

### Content Rules

- State facts concisely. Avoid unnecessary explanations or trailing rationale.
- Do not document information that is already obvious from the repository structure or configuration.
- Do not invent features, API shapes, or future direction: mark undecided things as TODO.
- Document a capability only after it is implemented and verified.
- Use proper Markdown headings (`##`, `###`), not bold text as headings.

---

## Project-Specific Guidelines

### Scope

- Small, time-boxed Flappy-like game. Do not add content beyond the minimum loop in `README.md`.
- Whether PlayMaker is used for game states is undecided: ask before choosing it or plain C# for a new piece of logic.

### Source

The Unity project lives at the repository root (Unity 6000.6.7f1, Universal 2D template, URP). Asset serialization is Force Text and `.meta` files are committed. Document the `Assets/` layout here once it is decided.

### Validation

TODO: no build or test commands yet. Define them once there is code to validate.

### Open Questions

- TODO: time box.
- TODO: PlayMaker for game states.
- TODO: art and audio source.
- TODO: publishing target.
