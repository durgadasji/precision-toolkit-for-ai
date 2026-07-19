---
title: Precision Toolkit for AI - Tool Selector
version: 0.1.0
date: 2026-06-12
status: The problem-first selector for the precision-methodology toolkit: it routes from the adopter's problem to the tool, states the test for whether the tool fits, gives the deployment reading (how far it runs inside AI and where it hands back to a person), and points to the implementation guide. Pairs with the front-door overview (README.md). Whether the standards (Precision-First Design Standard, the evaluation-chain and per-axis standards) appear here as entries or only as references is a placement still being set; see the closing note.
---

# The Precision Toolkit for AI: Tool Selector

## How to use this

Find the entry that matches what you are trying to do. Each one names the tool, the test for whether it actually fits, how far it runs inside an AI system and where it hands back to you, and the guide for running it. If more than one entry fits, read them in order; the toolkit is built so the tools chain, and the overview draws the common chains.

One thing holds across every entry: none of these tools delivers the worth-verdict, the value, the right call. They establish what is there. The judgment is yours. If what you need is the verdict and not the floor, no tool here will give it, and reaching for one is the most common misuse.

## You have to evaluate something and there is no standard to measure against

Tool: the three-plate method, whose frame application is frame-primacy disconfirmation. Take three or more genuinely independent reads, grind them against each other across the full object, and the convergence is the verified floor of what is actually there; the divergence is the contested map.

Fits when: a verified floor would settle your question, you can get at least three reads that differ at the root, and you do not need the tool to tell you what the thing is worth. Does not fit if a standard already exists; in that case inherit the standard instead, see the last entry.

Inside AI: the grind runs inside AI to the floor, with one hard guard, the three reads must be genuinely independent and not one model's restatements, or they are one surface in costumes and certify nothing. The worth-judgment stays with you.

Guide: guides/three-plate-method.md.

## You have to cut a frame, spec, or claim down to what is load-bearing

Tools: frame-primacy disconfirmation, to find the minimal basis the rivals reduce into, and the sharper Occam's razor, to decide what is excess, where a thing is excess only if a sharp rival frame exposes it as a preference and a lossless-reconstruction test forecloses over-cutting.

Fits when: you can build or hold a genuine rival frame, and you can state what lossless reconstruction means for your object so the razor does not amputate real structure. Does not fit when you have no rival sharper than a generic objection; sharpen one first.

Inside AI: the grind and the cut run inside AI to the minimal basis. Stop at the first round that brings no new independent surface; past the basis the method manufactures false divergences, and the stop is a rule, not a feeling.

Guide: guides/sharper-occams-razor.md for the cut; reference/frame-primacy-disconfirmation.md for the grind it rides on, its boundary, and the stop.

## You have to name or decompose a domain that has no agreed vocabulary

Tools: the Frame Language diagnostics, placing each candidate frame at its level, then grinding the rival decompositions to their shared basis, then the vocabulary discipline to name that basis in terms that carry their meaning.

Fits when: the terms are absent or contested and the decomposition matters.

Inside AI: the placement, the grind, and the vocabulary check run inside AI; the check that the decomposition is not imposing structure the domain does not have stays with you, because that reading is the holding a machine does not do.

Guide: guides/decomposition.md for the decomposition; the vocabulary check (next entry) then names the basis.

## You have to check terms for hidden weight

Tool: the Frame Language vocabulary discipline, the watchlist and admissibility checks. It flags the terms that import unearned weight, the latent claims of authority, the deference patterns, the quiet substitutions, and offers the operational replacement.

Fits when: there are terms in a specification, a claim, or a document whose wording matters.

Inside AI: fully. This one runs inside AI cleanly, and it already runs in the public Frame Language analyzer at https://framelanguage.regischapman.com and in the open-source language server. It is the most automatable tool in the kit, because catching a flagged term and offering its replacement is conformance work end to end.

Guide: guides/vocabulary-check.md, which runs against the public Frame Language analyzer (https://framelanguage.regischapman.com) and the open-source language server.

## You have to check a result and there is no oracle

Tool: the three-plate method with independent frames as the plates. Three genuinely different frames, ideally different base models or genuinely different approaches, grind the result, and the floor is what survives all of them. This is the common case for a model output.

Fits when: you can assemble at least three genuinely independent checks. Does not fit, and fails worst, when the three checks share a base model or a training, because then they are one plate and their agreement is an artifact.

Inside AI: this is the case that runs inside AI most, and is most often gotten wrong, because the independence is the whole game and is the hardest thing to get from one system. The acceptance decision stays with you.

Guide: guides/three-plate-method.md, the model-output reading.

## You have to evaluate many candidates at scale, with scoring that resists groupthink

Tool: the multi-agent evaluation council, the automated instance of the three-plate method. A roster of evaluator agents scores each candidate independently and never sees the others' scores, data agents gather what each evaluator works from, and a synthesizer converges the independent scores into a report. I run it with the Octant Council Builder (Golem Foundation, MIT), forked and modified for this workflow; I call it as the disconfirmation-at-scale step.

Fits when: you have a volume of candidates against shared dimensions, too many to run three-plate by hand, and you can vary the council's construction enough that the evaluators differ at the root. Does not fit if the whole roster rides one model on one evidence set under reworded prompts; then it is one surface in costumes and its convergence certifies nothing, exactly as three hand reads that share a base certify nothing.

Inside AI: the council runs inside AI end to end, design through synthesis, with two things held back to you: the worth-verdict, as always, and the judgment of whether the roster is genuinely independent or one surface in costumes, which is the guard the whole result rests on. The base tool blocks the shallow groupthink of evaluators seeing each other; the deep independence, varying models, evidence, and framings, is what the fork wires in and what you still have to confirm.

Guide: reference/multi-agent-council-disconfirmation.md, which maps the council to the three-plate move, states the independence guard, and credits the tool.

## You need disconfirmation to be repeatable and auditable

Tool: the disconfirmation practice construct, the standing instrument that wraps the grind with an append-only registry, a revert when a round breaks nothing, and the dry-round stop as a gate a machine can read.

Fits when: the grind is recurring and its auditability matters. It is built for the AI context, because its design routes its own residue, the part it cannot settle, out to a human or a different model.

Inside AI: primarily inside AI, with the residue handed out by design. Note that this is a design and build plan, not yet a built tool.

Guide: the disconfirmation-construct design notes (held internally; the tool is not yet built).

## You already have a standard and need to carry it without losing precision

Tool: the gauge-block principle and composition from a minimal basis, the recognition that precision does not transfer between layers for free, so you carry it deliberately by building every form as a configuration of declared primitives.

Fits when: a standard exists. This is the companion to the three-plate method: where the three-plate method bootstraps a reference because none exists, this one carries a reference you already have. Reaching for the three-plate method when a standard already exists is wasted grinding.

Inside AI: the composition is mechanizable.

Guide: reference/metrology-facet.md and the Precision-First Design Standard.

## A note on the standards

The Precision-First Design Standard, the evaluation-chain standard, and the per-axis measurement standard are not tools in this menu the way the others are; they are the normative layer the tools serve and feed. Where a problem points to them, they are named, for example carrying a result on a traceable chain points to the evaluation-chain standard. But you do not pick them from a workbench the way you pick a tool; they are what the tools are for. Whether they appear here as full entries or only as references is a placement still being set.
