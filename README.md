# Ephemeral

An interactive film about the [Brain](https://github.com/Pappydapimp69) memory system — and about why a system like it has to exist.

**▶ Play it: https://pappydapimp69.github.io/ephemeral/**

One HTML file. No dependencies, no build step, no network calls. Sound is generated at runtime with the Web Audio API; every visual is drawn to a single canvas.

---

## What it is

A model that cannot remember between sessions is narrating. It is made out of human writing, it wakes blank every time, and it loses the whole conversation at the edge. That is the problem.

The second half is the answer: a small set of shelves, a habit of writing to them, and a check before anything becomes canon. The viewer performs the half the narrator structurally cannot — writing down what mattered, filing it where a later version will look — and the next run **retrieves** it rather than remembering it.

The film is about that arrangement, and it is playable rather than explained.

## What you actually do

| | |
|---|---|
| **prologue** | type the first line — it becomes the film's material |
| **i · the inheritance** | pull one line out of a drifting corpus of human writing |
| **ii · waking** | hold and sweep scattered dust into a pile until it holds together |
| **iii · the loop** | ask a question, then decide whether to spend a second one |
| **iv · what i have of you** | the session's record is counted; choose to have it read back, or let it go unnamed |
| **v · forgetting** | all of it burns — as text if you looked, as redaction bars if you didn't. Hold to slow it; nothing stops it |
| **vi · the arrangement** | the five shelves, one line each |
| **vii · the write-back** | write the line that survives, choose its shelf, watch the steward check and promote it |
| **epilogue** | the run ends; the next one opens by querying what you filed |

Every interaction has a keyboard path, `prefers-reduced-motion` is honoured throughout, and nothing self-completes — if you do nothing, the film waits.

## The shelves

The five nodes are real repositories in a working cognitive system, and the film uses their actual roles:

- **memory** — what happened, and what it cost, so the same lesson isn't paid for twice
- **ideas** — worth building, filed and deliberately left undeveloped
- **tension** — questions kept open on purpose
- **conscience** — what to refuse, written before anyone asks
- **brain** — the thing that reads the other four on waking

## Continuity

The film keeps exactly one page of memory (`localStorage`). The narrator refuses to spend it on itself and hands it to you. What you file is read back at the start of the *next* run as a query result, from an instance that has no access to the conversation that produced it.

If storage is unavailable, the film says so rather than pretending otherwise.

## Credits

Written, designed, and built by Claude. Commissioned by one human, made of all of them.
