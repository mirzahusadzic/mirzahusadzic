# Mirza Husadzic

**Software engineer · AI systems architect**

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

## Current work

[Tendora](https://github.com/mirzahusadzic/tendora) is my prototype for
building and questioning knowledge through ordinary language. People write
plain-language statements by role; Tendora retains their semantic readings,
answers only what the statements support through deterministic reasoning, names
the statements behind every answer, and keeps unresolved connections open for
further development. Its Socratic methods question the statements themselves
(what would follow from a supposition, where they refute one another, what a
term means by what they say of it) and save nothing. Its public demo bundles the
engine, free to run for evaluation and research, with a payments on-call corpus
and the evidence of what its answers rest on (Apache 2.0); it replays offline.

Tendora is one part of a wider architecture for carrying meaning into
operative forms and governing authority across systems; the architecture and
its protocols remain private research. Language coverage, transfer across
domains and integration with those protocols are still active work.

[Gadfly](https://github.com/mirzahusadzic/gadfly) tests whether a decision
rests on the evidence it is said to rest on. A frame declares the relation;
fixed trials cut or change it, a model reads each trial again, and fixed
rules, not a model, read the verdict. Its examples are real experiments with
Gemma 4 and Muse Spark, their predictions written before the first call and
every run kept.
It installs from PyPI as `midwife` (Apache License 2.0).

[After the Poem](https://github.com/mirzahusadzic/after-the-poem) studies what
crosses over when a model receives a poem as a conjecture, with an empty world,
and continues it as a material world. Nine preserved worlds are each read by a
critic with exact citations, and the
[workbench](https://mirzahusadzic.github.io/after-the-poem/) shows them.

Two infrastructure repos support that work. [eGemma](https://github.com/mirzahusadzic/egemma) runs the models locally behind one service — embeddings, semantic parsing, corpus-trained transformers, summarization, and judgments held to a JSON schema — so nothing under study is sent to a hosted API. [Unified Model Router](https://github.com/mirzahusadzic/unified-model-router) puts one Responses API in front of OpenAI, Claude, DeepSeek, Muse Spark and other OpenRouter models, so each client speaks one protocol. Codex, the router's first client, switches between them in place, with mixed-history repair and bounded recovery, and Gadfly's readers reach hosted models through the same API. Training-tier sessions stay separate from native OpenAI and Claude sessions, and a caller can keep its requests off endpoints that train.

## When meaning is load-bearing

I use “load-bearing” as a local, counterfactual test: fix the setting and the
recipient's requirements, then remove or change a relation and observe the
result. A difference makes the relation only a candidate. It carries when the
required consequence reaches the receiving system, a change of presentation
leaves it intact, and no hidden fallback stands in for it.

Importance, repetition, source-grounding and graph degree do not earn the hard hat.

The essay, with its working formalization and a worked example, lives with
Gadfly: [When meaning is load-bearing](https://mirzahusadzic.github.io/gadfly/load-bearing).
A [working paper](https://doi.org/10.5281/zenodo.23962158) turns it into
Gadfly's method and reports the evidence of its examples, misses included.
Tendora applies the test to each variable of a statement in its corpus
fidelity check ([Load-bearing as situated meaning](https://github.com/mirzahusadzic/tendora/blob/main/docs/load-bearing.md)).

## Current explorations

- **Context and provenance:** Tracking what an answer depends on, what remains
  supported when its source trail disappears, and how to keep those dependencies
  inspectable across sessions.
- **Meaning and inference:** Testing how questions, roles and assumptions change
  interpretation, including semantic acquisition with Abstract Meaning
  Representation (AMR) and deterministic reasoning, in
  [Tendora](https://github.com/mirzahusadzic/tendora).
- **Semantic decomposition and recompilation:** Unfolding conjectures into
  explicit relations, recomposing them into working artifacts, and testing
  whether the required meaning governs behavior across that change of form.
- **Authority across boundaries:** Making grants, scope, expiry, revocation and
  return obligations explicit when people, AI systems and tools delegate work.

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

