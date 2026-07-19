---
title: The Multi-Agent Evaluation Council - Disconfirmation at Scale
version: 0.1.0
date: 2026-07-19
status: The depth behind the council entry in the selector. A multi-agent evaluation council is the automated, scaled instance of frame-primacy disconfirmation and the three-plate method: independent evaluators score without seeing each other, and the convergence is the verified floor. The council is built and run with the Octant Council Builder (Golem Foundation, MIT, https://github.com/golemfoundation/octant-council-builder), a Claude Code plugin that generates councils rather than being one; I call it as the disconfirmation-at-scale step of the workflow. This reference states what the council is, how it maps to the three-plate move, the one guard that decides whether it certifies anything, and where it hands back to a person. Draft for review; attribution and public framing pending confirmation.
---

# The Multi-Agent Evaluation Council: Disconfirmation at Scale

## What it is

The three-plate method takes three or more genuinely independent reads of an object, grinds them against each other, and treats the convergence as the verified floor of what is actually there. A multi-agent evaluation council is that same move run by machine, at a scale a person cannot reach by hand. A roster of evaluator agents scores the object independently and never sees each other's scores, data agents gather the raw material each evaluator works from, and a synthesizer converges the independent scores into a report. The move is not new; the scale is. When there are hundreds of candidates rather than one, the hand method does not run, and the council does.

## The tool

I run these councils with the Octant Council Builder (OCB), a Claude Code plugin from the Golem Foundation, MIT-licensed, at https://github.com/golemfoundation/octant-council-builder. OCB is not a council. It is a factory for one: you design the roster through conversation, it researches the domain and generates the agents, and it wires them into the three waves (data, independent evaluation, synthesis). I worked at Octant and Golem, so I know the tool and the context it came from. I did not build it. Because it is MIT-licensed, I run it as a fork I modify for this workflow, retaining its notice as the license requires, and the modification that matters is the guard below: the base plugin prevents shallow groupthink by keeping evaluators from seeing each other, but it leaves deep independence to the user, and the fork wires that in. The credit for the machinery is theirs. What this reference and the fork add is the placement in the precision workflow, the mapping to the three-plate move, and the independence-by-construction guard enforced rather than left optional.

## The one guard that decides whether it certifies anything

Evaluators that never see each other are independent at the level of role and prompt. That is not the same as independent at the level of construction. If every agent is the same underlying model reading the same evidence under a different instruction, the roster can be one surface in several costumes, and its convergence certifies far less than it appears to. This is the exact failure the three-plate method warns against: three reads that are one model's restatements of itself are not three reads. So the council resists groupthink of the shallow kind, agents parroting each other, while remaining exposed to the deep kind, agents sharing a blind spot because they share a substrate. Genuine independence is bought by varying the construction: different models, different evidence, different framings of the question, not different wording of the same prompt. A council built without that variation is a faster way to reach one opinion, not a wider one, and reading it as a verified floor is the misuse.

## Where it hands back to you

The council runs inside AI end to end: it designs, generates, scores, and synthesizes. Two things do not run inside it. The worth-verdict, as with every tool here, stays with you; the council produces scored evaluations and a synthesized report, not a decision about what the object is worth. And the independence judgment above stays with you, because deciding whether the roster is genuinely varied or one surface in costumes is a reading a person holds, not a step the machine performs on itself.

## How it chains

The council is the scaled companion to guides/three-plate-method.md. For a single object where three genuine reads are within reach, run three-plate by hand; the guard is the same and the judgment is closer. For a volume of objects against shared dimensions, call the council, and hold its convergence to the same independence guard you would hold three hand reads to. The vocabulary check and the sharper Occam's razor still apply downstream: the report a council produces is a document like any other, and its terms carry unearned weight or they do not.
