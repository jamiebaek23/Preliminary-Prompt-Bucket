# Module 00: The Blueprint

The core philosophy. Every other file in this repository is built on this one.

It was written for admissions tests, where it took a score from the middle of the scale to full marks in a third of the allotted time. It is stated here in general form: it applies to any skill where problems are solved under pressure (mathematics, physics, programming, puzzles, interviews).

## 1. The aim

Run away from the average as far as possible. Common people run towards the mean and end up clustering in the middle, when they should be running away from the middle and maximise their standard deviation and protect that at all cost. In fact, it is ideal to take a transcendent approach and go beyond into higher dimensions, by rising into an orthogonal plane relative to the rest of the people.

Normal advice produces normal actions, and normal actions produce normal results. "Just do more of it", "sit papers under timed conditions", "work harder" are normal advice. The aim here is anomalous: full marks, in a fraction of the time. Aim at ten times what currently seems possible.

## 2. The mission statement

BUILD REACTION CIRCUITS, SO THAT I REACT A CERTAIN WAY WHEN I READ THE QUESTION'S COMMAND TERMS.

Every session, every question, and every piece of feedback must directly contribute to reinforcing the vector that this sentence embeds.

## 3. Glossary (These may ostensibly look like tautologies, but they're really not!)

- COMMAND TERMS: the guiding lights a question gives. Certain expressions, certain combinations of functions, certain word choices ("line" instead of $f(x)$, "circle" instead of an equation). The way a question is presented nudges the solver toward the intended route. Setters rarely try to trick. The first half of the mission is to recognise these cues from presentation alone.
- REACTION CIRCUITS: a trained, automatic chain from cue to move. When a command term is recognised, the solver reacts in a specific way, usually by writing a specific expression. Once installed, circuits are the algorithm that runs on any question.
- CANONICAL SETS: the small set of official, highest-quality problems for the target (for an exam, its past papers).
- MODEL ANSWERS: the written ideal solutions (at least ideal for now).
- IDEAL THOUGHT PROCESSES: the chain of thoughts that produces the model answer. It is a different object from the model answer and is almost never written down.
- BIFURCATION POINT: the first line where the solver's reasoning and the ideal thought process split into two paths.
- CRITICAL THOUGHT: quite literally, the CRITICAL THOUGHT that had to be self-generated at the bifurcation point to stay on the ideal path. It can be a sentence, a question, or a non-verbal expression. I sometimes call this the key revelation.
- ZOMBIE MATHS: brute force. Pushing symbols with the most primitive method available without thinking about how the question wants to be solved.
- CIRCUIT BANK: the written collection of every extracted circuit and decision rule.
- BACKTESTING: replaying a finished attempt against a fixed checklist, as one backtests a trading strategy.

This is a skill, not a talent. It is consciously trainable.

## 4. Two kinds of preparation

1. Skillset development (80% of the effort). Private work: drills, analysis, building the core.
2. Performance (20%). The live game: timed, one attempt, under pressure.

An athlete trains in the gym and plays matches. Nobody believes matches alone are the best training. Most students reverse this and treat timed sittings as the main practice.

The governing rule:

The canonical set is for analysis. Everything else is for consumption and application.

- Analyse the canonical set to a depth others do not consider possible.
- Use other material (community papers, harder exams, adjacent exams) only to put the trained algorithm to the test, and as one-off timed sittings.
- Do not analyse a random outside question while consuming the canonical set as throwaway timed practice. That is the exact reversal to avoid.
- Volume comes after competence. Build the core first; then do thousands of questions and they will feel light.

Other materials are not bad. The order is what goes wrong, and it goes wrong from not knowing what each material is for.

## 5. Six beliefs, inverted

1. "Do as much as possible and the results take care of themselves." Volume without extraction is how strong students score in the middle.
2. "I will do what I am assigned." Assigned volume with no mission statement is labour, not training.
3. "My circumstances are different, so my target is different." The method and the height of the aim do not depend on background.
4. "I will drill papers under timed conditions and hope." Timing without analysis is a rehearsal of the current level. It improves nothing.
5. "I will write faster to cut time." Time is cut by rerouting to better methods. Writing faster creates errors, and errors cost more time.
6. "I will work blindly and trust it works out." Conviction directs the work; it does not replace the method. Take agency over everything that can be controlled, starting with proper analysis.

## 6. A circuit firing

Source: TMUA 2017, Paper 1, Question 14.

Solve $2^x + 3 \cdot 2^y = 3$ and $4^x - 9 \cdot 4^y = 6$.

The circuit: when given simultaneous equations, look at the connection between the equations before manipulating either one.

Let $A = 2^x$ and $B = 3 \cdot 2^y$. Then $A + B = 3$ and $A^2 - B^2 = 6$, so $A - B = 2$. Hence $A = \tfrac{5}{2}$, $B = \tfrac{1}{2}$. Take logarithms and read off $x$ and $y$.

What was not done: squaring the first equation. The relationship between the two equations was the cue (a difference of two squares). The reaction was to write it out. "Look at the relationship first" now carries into every simultaneous-equations question.

## 7. The three-step analysis: WHAT, HOW, WHY

This is the engine. Solving, fixing what is wrong and moving on keeps a solver stuck. So does reading a solution and nodding.

### Layer 1: WHAT

What is my chain of reasoning, and what is the model answer's?

Action: lay them side by side.

- One side: my chain of reasoning, whether right, wrong, or stuck. Example: "I saw a quotient, so I differentiated it as it stood with the quotient rule."
- Other side: the model chain. Example: "Take the reciprocal of the denominator, expand, then differentiate."

### Layer 2: HOW

Where do the two chains split?

Action 1: find the bifurcation point, the first line where the model takes the shortcut and I take the detour. It helps to journal, in sentences, what was going through my mind while solving.

Action 2: answer this. What critical thought did I have to generate to follow the ideal path?

Example: "Hold on. I do see a method. But is there a simpler one?"

That thought has to be self-generated, in the arena. At first these thoughts feel impossible to have. "How could I think of this in the exam?" must stop being an outcry and become a real question: what general principle can be distilled from this bifurcation, so that it fires on questions never seen before? Write each critical thought down word for word. A single question can hold several.

### Layer 3: WHY

Why must I think that critical thought? Why react that way? What underlying definition or axiom makes it natural?

Example: because the denominator was a polynomial expression. That is the cue that makes reciprocal-and-expand cheaper than the quotient rule. Underneath sits a plain truth: the quotient rule is derived from the product rule. Same machinery, more ink. Being lazy in the right way (refusing long manipulation because it is slow and error-prone) is a mathematical virtue.

These are open questions. They force a return to what things are and how they are defined. No circuit is a secret trick. Example: when two circles touch at one point, join their centres. That is obvious once a circle is seen for what it is: a centre and the points at one distance from it. The centre is the point of interest.

No question will ever repeat. Memorising questions is not the aim. The aim is a cognitive infrastructure: an algorithm that runs on whatever question appears.

## 8. Backtesting

Run this checklist on every question, as a mantra:

1. What was the first useful cue in the question? From which word or expression should I have reacted, and what should I have written down?
2. What method did that cue suggest?
3. Where exactly did I hesitate? What thought do I reinforce so that hesitation never recurs?
4. What trap was the question setting? (Usually a computation error or a skipped step.)
5. What would make me recognise this faster next time? Extract the rule.
6. What is the reusable decision rule from this question?

Keep a journal: a diary of what was going through the mind and why each expression was written. The accumulated answers to 5 and 6 are the circuit bank. Re-read it weekly and self-test the moves with the cues covered.

Journal prompt: after reading the same question, why did the model answer react differently from me? Go past the how of the solution to the why that led to the how. Then reinforce the whys.

## 9. Speed

Speed is a byproduct. Extracted rules accumulate and cut time automatically. Writing faster never cuts time.

## 10. Cadence

- One paper through the full WHAT, HOW, WHY analysis every two to three days beats a paper a day at surface level.
- Analysis time is two to three times the sitting time.
- A genuine attempt is required before analysis, because the attempt is the raw material. A formal timed sitting is not; a running stopwatch is enough.
- Never end a session on a sitting. End on revision of the analysis; that is what consolidates overnight.
- A short runway is enough when it is compressed this way: most recent papers first, the six backtesting questions on every question, journal daily.

## 11. Performance protocol

- Pass 1: answer everything a circuit fires on instantly. Skip anything that needs deliberation.
- Pass 2: return to the skipped questions, hardest last.
- Pass 3: with the remaining time, re-solve from question 1. Do not re-read; re-solve and compare outputs.
- Emotions in the arena are independent of outcomes. Treat them as noise and execute in the present.

## 12. Extension to long problems

For proofs and olympiad-style problems the same machinery applies with these additions.

- Wrestle alone first, 20 to 30 minutes at least. List the objects in play. Write the bottlenecks as plain facts.
- An ideal solution is three to five critical thoughts, large leaps and not many small steps. Analysis names the cue that triggers each one.
- The ideal thought process includes the mistakes the setter expects, each failed fast, each with a recovery move.
- When a branch is dead, leave it. When a frame is not working, destroy it, and be willing to destroy the new one too.
- A problem is done only after: independent attempt, journal, study of the model answer, extracted circuits, a clean written solution, a delayed reattempt from a blank page, and transfer to a related problem.
- Use each solved problem as a centre and learn the concepts around it in widening rings.
