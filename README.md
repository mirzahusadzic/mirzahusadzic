# Mirza Husadzic

**Software engineer · AI systems architect · Independent researcher**

I build AI systems whose sources, assumptions and failure modes remain
inspectable.

My research asks how a conjecture expressed in one form—even a poem—can become
a working artifact. I make its relations explicit, use those relations to
construct the artifact, and test whether they govern its behavior. I describe
this work as semantic decomposition and recompilation.

Throughout that process, I keep my interpretation of the source and the added
engineering choices open to inspection.

I also work on protocols for granting, constraining and checking authority
across boundaries between people, AI systems and tools.

Sustained human–AI engineering collaboration is how I investigate ideas, build
software and test behavior.

## Work

- [frame-loop](https://github.com/mirzahusadzic/claude-frame-loop): a semantic workflow linter for Claude Code; the person's approved words are the frame, and only a mismatch reaches them. Early alpha. [![frame-loop release](https://img.shields.io/github/v/tag/mirzahusadzic/claude-frame-loop?sort=semver&label=frame-loop&logo=github&logoColor=white)](https://github.com/mirzahusadzic/claude-frame-loop/tags)
- [Gadfly](https://github.com/mirzahusadzic/gadfly): tests whether a decision rests on the evidence it is said to rest on. [![midwife on PyPI](https://img.shields.io/pypi/v/midwife?label=midwife&logo=pypi&logoColor=white)](https://pypi.org/project/midwife/)
- [Tendora](https://github.com/mirzahusadzic/tendora): building and questioning knowledge through ordinary language, with answers only from what the statements support. A prototype with a public demo.
- [After the Poem](https://github.com/mirzahusadzic/after-the-poem): where this work began; a model receives a poem as a conjecture and continues it as a world ([workbench](https://mirzahusadzic.github.io/after-the-poem/)).
- Underneath: [eGemma](https://github.com/mirzahusadzic/egemma) runs the models locally, and the [Unified Model Router](https://github.com/mirzahusadzic/unified-model-router) is one API in front of the hosted ones.

## Papers

Working papers on Zenodo, under CC BY 4.0; each DOI resolves to the latest
version.

- **Holding the Thread: An Open Frame for Checking an Agent's Work Against the
  Person's Own Words** (2026), on frame-loop.
  [doi:10.5281/zenodo.24044462](https://doi.org/10.5281/zenodo.24044462)
- **Policy at the Junction: The Unified Model Router as a Narrow Waist** (2026).
  [doi:10.5281/zenodo.24014212](https://doi.org/10.5281/zenodo.24014212)
- **When Meaning Is Load-Bearing: Testing Whether a Decision Rests on Its
  Declared Evidence** (2026), Gadfly's method, with its
  [essay](https://mirzahusadzic.github.io/gadfly/load-bearing).
  [doi:10.5281/zenodo.23962158](https://doi.org/10.5281/zenodo.23962158)

## Current explorations

- **Context and provenance:** Tracking what an answer depends on, what remains
  supported when its source trail disappears, and how to keep those dependencies
  inspectable across sessions.
- **Meaning and inference:** Testing how questions, roles and assumptions change
  interpretation, including semantic acquisition with Abstract Meaning
  Representation (AMR) and deterministic reasoning, in Tendora.
- **Authority across boundaries:** Making grants, scope, expiry, revocation and
  return obligations explicit when people, AI systems and tools delegate work;
  frame-loop and the router hold the first parts of it.

## Background

I've worked across engineering simulation frameworks, enterprise communication
systems, automotive embedded software, distributed vehicle middleware and maritime
edge-to-cloud architecture. The common thread is understanding behavior under
real constraints, especially where responsibilities belong and what happens
when they are misplaced.

That experience shapes how I direct AI-assisted engineering: framing problems,
shaping context, guiding implementation, evaluating results and keeping
architectural intent tied to what ships.

If you're working on inspectable reasoning, semantic acquisition or systems that
have to work outside the demo, I'm happy to compare notes.
