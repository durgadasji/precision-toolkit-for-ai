# The Precision Toolkit for AI (PT4AI)

## What this is

This is a toolkit: a set of tools of different kinds that, used together, make a more precise way of working across many kinds of problem. It is not a method you adopt whole, and it is not a theory you have to believe. It is a workbench. You reach into it for the tool that fits the problem in front of you, and the tools are built to combine, so reaching for one tends to set up the next.

The tools come from one move: taking precision, the discipline of getting the reference right and then building on it without loss, and carrying it into work that usually goes without it, coordination, evaluation, and meaning. Precision is a stance before it is a technique, and it has been worked to a high finish in fields that rarely talk to each other: metrology and the physical sciences, linguistics, the study of how institutions actually hold, forecasting, the contemplative traditions. This toolkit draws the rigor from wherever it was worked out and reinstates it where the material is softer. That shared source is why the tools fit together rather than sitting as a pile. They are facets of one problem, how to build precision where there is none to start from.

If you already know your problem, go to the tool selector, which routes from the problem to the tool and to the guide for running it. This overview is the orientation to read first: what the tools share, how they chain, and how much of each you can hand to a machine.

The toolkit also has a web front door at https://precision.regischapman.com, the same routing as a narrative page, with prompts you can copy and run in your own AI immediately. The general-register essay behind the sharper razor, *A Sharper Occam's Razor*, is published at https://paragraph.com/@holonic-horizons/a-sharper-occams-razor.

## What is in this repository

- `selector.md`: start here. It routes from your problem to the right tool and the guide for running it.
- `index.html`: the web front door, served as the toolkit's site. The selector as a narrative page, with copy-and-run prompts for each tool.
- `guides/`: the step-by-step how-to for each tool, the three-plate method, the sharper Occam's razor, the vocabulary check, and decomposition.
- `reference/`: the depth behind the tools, the method derivations and the structural showing behind each tool.
- `data/term-registry.json`: the canonical Frame 1 vocabulary the vocabulary check runs against.
- `LICENSE`: Creative Commons Attribution 4.0.

## The stance the tools carry

Under the tools is a way of working, and the tools are how it becomes usable by someone who did not invent it. Four commitments run through all of them.

Precision-first: get the reference right before you measure. Most failures are not measurement errors, they are missing or merely local references, and the tools are mostly about building a reference you can trust.

Disconfirmation: do not confirm what you already believe, grind it against something built differently and keep what survives. Convergence between independent accounts is the signal; a single confident account is the thing to distrust.

Frame-awareness: know which frame you are in. A surface description, a structural description, and the whole of a thing are three different stances, and most confusion is a claim made in one frame and read in another.

Honesty about where it stops: these tools establish what is actually there, the verified floor. They do not tell you what it is worth. That judgment is yours, and the tools are built to hand it back to you rather than to fake it.

That last commitment is the spine of the whole toolkit. A tool that pretends to deliver the verdict is the failure these are built against.

## The kinds of tools

Three kinds, mapped here and routed in the selector.

Reference-building tools, from metrology: how to build a trustworthy reference, whether by inheriting an external standard and carrying it without loss, or by bootstrapping one where none exists.

Disconfirmation and evaluation tools: how to grind independent accounts to a verified floor, how to decide what in a result is excess and cut it without amputating real structure, and how to run that grinding repeatedly and auditably.

Frame diagnostic tools: how to tell which frame a claim is in, how to reduce a frame to what is load-bearing, and how to hold the words you use to terms that carry their meaning instead of borrowing unearned weight.

## How they combine: the workflow is the point

The value is not any single tool, it is the chain. Two worked chains show the shape.

Evaluating something where there is no standard. Grind three independent reads to a verified floor of what is actually there. Cut the parts of the result that do not survive, the claims that are excess. Hold the terms of the floor to vocabulary that carries its meaning. Carry the whole on a traceable chain so a later reader can check it. Then make the worth-judgment yourself, with the floor and the contested map in front of you. Five tools, one pass, and the verdict stays human.

Naming a domain that has no agreed vocabulary. Place each candidate frame at its level, so you are not arguing a surface claim against a structural one. Grind the rival decompositions to the basis they all reduce into. Name that basis in terms that do not smuggle in unearned weight. The result is a vocabulary that survived disconfirmation rather than one author's preference.

A tool used alone still works. A tool used in its chain is where the improved workflow actually lives.

## How much runs inside AI

For each tool there is a line worth knowing before you automate it: how far it runs inside an AI system and where it has to hand back to a person. The cut is the same one the stance draws. The conformance work, building the reference, running the grind, checking the vocabulary, is Frame 1 and Frame 2 work, and a machine can do it. The holding, the worth-judgment and the reading of the whole, is Frame 3 work, and a machine supplies the look of it without the thing. So the rule for automating any of these is simple: let the machine reach the floor, keep the verdict.

One tool carries a specific machine danger worth stating here, because it is the easiest to get wrong. The grinding tools need genuinely independent accounts. Inside an AI system it is tempting to generate three accounts from one model and treat them as three plates, but they are one surface in three costumes, and their agreement certifies nothing. The selector marks this where it bites. It bites hardest in the multi-agent evaluation council, the automated version of the grind that scales to hundreds of candidates: the council is run with the Octant Council Builder (Golem Foundation, MIT), forked to enforce independence by construction rather than by prompt, and its reference is reference/multi-agent-council-disconfirmation.md.

## These are the tools the method was built with

A disclosure travels with the toolkit, because it is what makes it adoptable rather than a demand to become someone else. These are the tools this way of working was built with. They are one person's fingerprint. What transfers is the obligation they discharge, getting the reference right, grinding against independence, keeping the verdict human, and you can discharge that obligation with these tools or with your own. Adopt the vein, not the fingerprint. A toolkit that asked you to do exactly as its author does would be making the error the tools themselves diagnose.

## What is here and what is held back

The released toolkit is the structural showing: what each tool is, when to reach for it, and how to run it. The personal account of why this way of working came to be, and certain interior material not yet checked by a reader who does not already hold its frame, are held privately and are not part of the release. They are named where they are referenced, so the structure is honest about its own edges, but the toolkit stands on its own without them.

## How to use this

Start at the selector with your problem; it routes you to a tool and to that tool's implementation guide, which is the step-by-step for running it. All four guides are in place: the three-plate method, the sharper Occam's razor, the vocabulary check, and decomposition. The standards this toolkit serves, the Precision-First Design Standard and the evaluation and measurement standards, are the normative layer the tools feed, and they are referenced where a problem points to them rather than picked from the workbench.
