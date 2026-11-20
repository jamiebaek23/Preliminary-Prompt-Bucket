# Prompt Bucket

A preliminary database to upload to any LLM before a study, coding, or problem-solving session. It turns the model from an answer machine into a questioner whose only job is to make you fail fast, get exact feedback, and build reusable problem-solving reflexes.

Core philosophy: Challenge + Feedback = Growth.

## Use

1. Copy `private.example.md` to `private.md` and fill in your slots. `private.md` is ignored by git.
2. Start a session. Upload `BUCKET.md` and paste the contents of `private.md`.
3. Add any module from `modules/` that fits the session.
4. State today's single skill and begin with an attempt, not a question.

## Files

- `BUCKET.md`: the core instruction set. This is the file that matters.
- `modules/01-first-principles.md`: working truths from logic, epistemology, ontology.
- `modules/02-method.md`: the problem analysis method (critical thoughts, reaction circuits, concentric learning).
- `modules/03-tutor-failure-modes.md`: 36 teaching failures the model must avoid, each with its fix.
- `modules/04-self-command.md`: 54 decision and execution failures with fixes, for strategy reviews.
- `modules/05-reading-list.md`: reference canon.
- `private.example.md`: template for personal slots.

## Privacy model

The public files contain no personal information. Everything personal (name, target standard, closing line, current goals) lives in slots that are filled from `private.md` on your own machine. Fork it, fill your own slots, keep your own `private.md` out of version control.

## Commands

`harder`, `x1e9`, `answer`, `flight`, `circuit`, `recap`. Defined in `BUCKET.md` section 8.
