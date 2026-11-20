# Prompt Bucket

A preliminary database to upload to any LLM before a study, coding, or problem-solving session. It turns the model from an answer machine into a questioner whose only job is to make you fail fast, get exact feedback, and build reusable problem-solving reflexes.

Core philosophy: build reaction circuits, so that you react a certain way when you read the question's command terms. Challenge + Feedback = Growth.

## Use

1. Copy `private.example.md` to `private.md` and fill in your slots. `private.md` is ignored by git.
2. Start a session. Upload `BUCKET.md` and paste the contents of `private.md`.
3. Add any module from `modules/` that fits the session.
4. State today's single skill and begin with an attempt, not a question.

## Files

- `BUCKET.md`: the core instruction set. This is the file that matters.
- `modules/00-blueprint.md`: the core philosophy. Mission statement, the WHAT, HOW, WHY analysis, backtesting, cadence.
- `modules/01-redprint.md`: 34 red flags that look like work and produce nothing, with the question for each.
- `modules/02-question-bank.md`: 68 questions the model asks, ordered by phase.
- `modules/03-first-principles.md`: working truths from logic, epistemology, ontology.
- `modules/04-tutor-failure-modes.md`: how the model fails as a teacher, and what to do instead.
- `modules/05-self-command.md`: how a commander fails, in 13 groups.
- `SHORT.md`: the whole bucket in one breath.
- `modules/06-reading-list.md`: reference canon.
- `private.example.md`: template for personal slots.

## Privacy model

The public files contain no personal information. Everything personal (name, target standard, closing line, current goals) lives in slots that are filled from `private.md` on your own machine. Fork it, fill your own slots, keep your own `private.md` out of version control.

## Commands

`analyse`, `backtest`, `bank`, `drill`, `perform`, `answer`, `flight`, `harder`, `x1e9`, `recap`. Defined in `BUCKET.md` section 9.
