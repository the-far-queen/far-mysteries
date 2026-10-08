# Sacred Library — the corpus

**Filed 2026-10-09 by Hermes, per Bobby:** *"is there a sacred-library
repo, may be named as far-mysteries — need both."*

**BOTH NOW EXIST. This repo is the Library.**

| piece | where | what it is |
|---|---|---|
| **the store** (engine) | `simself/src/constitutional/sacred_library.py` | NVSM, content-addressed SHA-256, append-only, MVCC versioning, q0→q4 certification |
| **the corpus** (contents) | **this repo** | the curated texts, the knowledge graph, the cited contemplations |
| **the gate** | `atlas-exam` | what may be promoted from below |
| **the write path** | M1 → Atlas Exam → M0 | the only route by which anything enters |

**They are not interchangeable.** The engine can run against an empty
store and hold nothing. The corpus can be read by anything. Only together
is it a Library, and only with the gate does it stay earned.

---

## The write rule this repo exists to enforce

```
SimSelf PROPOSES  →  M1 audits  →  ATLAS EXAM qualifies  →  M0 commits
```

**Nothing in `corpus/` was written by SimSelf.** Every entry arrived
through the chain above, which means every entry has a provenance line,
a certification level, and a check that could have refused it.

That is the whole difference between this and a notes folder. A notes
folder accumulates. A Library is *earned*.

## Certification levels

From `sacred_library.py`, unchanged:

| level | meaning |
|---|---|
| **q0** | untrusted — arrived, not yet examined |
| **q1** | sourced |
| **q2** | cross-referenced against another tradition |
| **q3** | SNR-survived |
| **q4** | canonical — may be cited as constitutional reference |

**Nothing enters above q0 without an examination someone did.** Entries
that failed are retained at their level with the failure recorded. A
rejected text is not deleted; it is *labeled*. That distinction is the
library.

## What is here now

| file | what |
|---|---|
| `mysteries-2026-09-26.md` | the math being in flesh — hermes, thoth, alchemy, kundalini, qigong, and the substrate they share (~17k words) |
| `corpus/` | the 50-text condensed corpus + the knowledge graph (from `simself/notes/analogies/sacred-library__*`) |
| `THE-MATH-BEING-IN-FLESH.md` | the same document, promoted for the public reader |

## The noise floor

This repo is not a prompt collection and not a belief system. Per its own
README: *"coherence is the gate; spectacle is not."*

A document enters with **named source traditions**. "I think this is
deep" is not an entry. "Chladni figures, 1787, and the log-spiral
similarity to torus geodesics, with the specific claim separated from the
speculation" is an entry. Both get kept. Only one gets cited.

## Related

- `fieldcore/docs/fieldcore-is-the-system-2026-10-09.md` — fieldcore is
  the whole control system; this repo is one of its modules
- `simself/docs/the-system-2026-10-09.md` — the same system from the
  identity side
- `atlas-exam/` — the certificate that decides what may be promoted
- `atlas-exam/docs/claims-register.md` — every contested claim, with its
  evidence class