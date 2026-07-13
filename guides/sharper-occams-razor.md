---
title: Sharper Occam's Razor - Implementation Guide
version: 0.1.0
date: 2026-06-12
status: The practitioner-facing how-to for the sharper Occam's razor, the criterion for what in a composition is excess to cut and what is load-bearing to keep. The razor rides on the disconfirmation grind, so the three-plate method implementation guide (guides/three-plate-method.md) is its companion and is assumed here. The criterion's statement lives in reference/metrology-facet.md; the boundary, the mis-located-trigger check, and the entailment test live in reference/frame-primacy-disconfirmation.md; the general-register essay is the general-register essay, held separately, whose personal and contemplative material is not part of this guide.
---

# Sharper Occam's Razor: Implementation Guide

## What this guide is, and what it is not

This is an implementation guide. It is how to actually use the sharper Occam's razor on a real composition, written for someone who will use it rather than refine it.

Classic Occam's razor says do not multiply entities beyond necessity, prefer the simpler account. It is good advice and it is famously vague: it never tells you how to determine what is necessary, or what counts as an entity, and taken too far it shaves off real structure to make a thing look simple. The sharper razor fixes both ends. It supplies a test for necessity, so it cuts where the old razor only gestured, and it adds a constraint that forbids over-cutting, so it cannot amputate real structure the way the old one can.

The razor does not work alone. It is the cutting decision that rides on the disconfirmation grind: you grind a composition against rival accounts to surface where they converge and diverge, and the razor is the rule for what to do with that result. So this guide assumes the three-plate method guide, which is how the grind is run, and focuses on the cut.

One thing to hold from the start. The razor decides what is necessary in a composition, the minimal basis it reduces to. It does not decide whether the composition is true, or right, or worth holding. That is a different judgment, a Frame 3 one, and it stays with you. The razor establishes the load-bearing structure and stops there, the same floor every tool in this kit reaches and does not cross.

## When to reach for it: the applicability test

Reach for the sharper razor when all of these hold.

1. You have a composition you suspect is overbuilt. A frame, a specification, a taxonomy, a model, a set of claimed requirements: something made of parts, some of which may be preference dressed as necessity.

2. You can hold a genuine rival account at full strength. The razor cuts by grinding against an account built differently at the root, and that account has to be real and held in good faith. If the best you can do is a caricature you set up to knock down, you do not yet have a rival, you have a warped plate, and you will cut the wrong things.

3. You can say what lossless reconstruction means for your object. The safety constraint is that you may only cut what the remainder can fully rebuild, so you have to be able to tell, for your kind of object, whether something removed could be reconstructed from what is left. If you cannot state that, you will cut blind.

When you are instead trying to decide whether the composition is correct or worth keeping, the razor is the wrong tool: it finds the minimal basis, not the verdict.

## How to run it

1. Hone the frames first, both of them. Hold your own account and the rival at their sharpest, in good faith, at full strength. This is the one condition the whole method rests on. A rival held loosely produces false disagreements, and false disagreements cut real structure. You cannot find your own curvature from inside your own account, which is why the rival has to be real: it is the only thing that can show you your warp.

2. Grind, then read convergence and divergence. Run the disconfirmation pass: pass each element of the composition through the rival account. Where the rival arrives at the same element from its different root, that element is in the minimal basis, keep it. Where the rival builds a sound version without that element, that element is a candidate for the cut: a private preference that one side mistook for a necessity.

3. Apply the cut test. An element is excess if a sharp rival exposes it as a preferred configuration rather than a primitive. Convergence keeps; exposed preference is a candidate to cut. Note the word candidate; the next step decides it.

4. Apply the over-cut guard before you cut. You are only ever allowed to cut what the minimal basis can still fully reconstruct. So for each candidate, ask whether everything load-bearing that the element carried can be rebuilt from what remains. If yes, it was excess, cut it. If no, removing it loses real structure that nothing else reproduces, which means it only looked like a preference because the rival framed it differently; it is load-bearing, keep it. Necessity is lossless reconstructibility, and this guard is what makes the razor unable to cut too deep.

5. For a claimed invariant or requirement, run the mis-located-trigger check. A common hidden excess is an element keyed to a property that travels with the one that actually necessitates the form, rather than to that property itself. To test it, construct two cases: one where the stated trigger holds but the form is not needed, and one where the form is needed but the stated trigger is absent. If you can build either, the element was keyed to the wrong property. The element may still survive, but in corrected form, re-keyed to the property that necessitates it.

6. Stop at the dry round. Like the grind it rides on, the razor is self-limiting while it is reducing and inverts past the minimal basis. The first round that brings no new rival surface and cuts nothing further is the end. Past the basis, a further pass does not find real excess, it manufactures a divergence and invites a cut into load-bearing structure. The stop is a rule, not a feeling: no new round without a new independent rival.

## A worked example: trimming a set of claimed universals

A team has a draft standard with six requirements it calls universal, meaning each must hold for every case in scope. Some may be real, some may be the team's preferred way of working mistaken for a necessity.

Hone. Build a genuine rival: someone who would specify the same domain from a different discipline, and hold their account at full strength rather than as a strawman.

Grind. Pass all six requirements through the rival. The rival independently arrives at three of them from its own root: those three are in the minimal basis, keep them. The rival specifies sound cases without the other three: those three are candidates for the cut.

Cut test and over-cut guard, on the three candidates. Two of them: everything they constrained reconstructs from the requirements that remain, so they were excess, cut them. The third looked like a preference because the rival framed it differently, but when you try the guard, removing it loses a real constraint that nothing else reproduces. It is load-bearing after all; keep it. So from three candidates, two are cut and one is kept, and the guard is what caught the false cut.

Mis-located trigger, on one survivor. One of the kept requirements is stated as keyed to a property that merely travels with the one that necessitates it. You construct a case where the stated trigger holds and the requirement is not needed, which shows the key is wrong. The requirement survives, re-keyed to the property that actually necessitates its form.

Stop. A further round brings no new rival, so it is the dry round and the run is over. Six claimed universals have become four real ones, one of them corrected, with two cut and the cuts reconstructible from what remains. That last clause is the proof the razor did not cut too deep.

## How it is misapplied, and how to catch it

Each entry is a misuse and the catch for it.

Cutting with a dull or strawmanned rival. A rival held loosely is a warped plate, and grinding against it yields false disagreements that cut the wrong things. Catch: hold every account at full strength and in good faith before cutting anything; if you cannot, you are not ready to cut.

Over-cutting to look simpler. This is classic Occam's failure, shaving off real structure for the appearance of simplicity. Catch: the lossless-reconstruction guard. Cut only what the remainder can fully rebuild; if removal loses structure nothing else reproduces, it is load-bearing.

Under-cutting, keeping a preference as if it were necessary. Catch: the rival probe. If an account built differently at the root does the work without the element, it is a preference, not a primitive.

Confusing simpler with necessary. The old razor prefers the simpler-looking account; the sharper one keeps the lossless-minimal one, which is not always the one that looks simplest. Catch: necessity is reconstructibility, not appearance. Decide by the reconstruction test, not by which version reads as cleaner.

Keeping or cutting by the wrong property. An element keyed to a property that travels with the necessitating one passes a loose check and fails a sharp one. Catch: the mis-located-trigger check, the two constructed cases.

Cutting past the minimal basis. Once the composition is reduced, another pass manufactures excess and cuts into load-bearing structure. Catch: the dry-round stop, and no new round without a new independent rival.

## Where this sits

The grind the razor rides on, and how to run it, is in guides/three-plate-method.md; read it first, since the razor is the cut on top of that pass. The criterion's place in the wider method, with the sharpness precondition, is in reference/metrology-facet.md. The boundary that gives the dry-round stop, the mis-located-trigger check, and the entailment test and its individuation limit are in reference/frame-primacy-disconfirmation.md. In the toolkit selector this guide answers the entry for cutting a frame, spec, or claim down to what is load-bearing, and it chains directly after a disconfirmation pass and before holding the surviving terms to the vocabulary discipline.
