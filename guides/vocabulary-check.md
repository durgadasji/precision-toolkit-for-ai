---
title: Frame Language Vocabulary Check - Implementation Guide
version: 0.1.0
date: 2026-06-12
status: The practitioner-facing how-to for the Frame Language vocabulary discipline: catching terms that import unearned weight and naming what they were implying, so the words of a result carry their meaning rather than borrowing it. The full procedure lives in reference/frame-language-grammar.md (the three Parts); the public watchlist of terms with their replacements and strengthened forms is data/term-registry.json (33 terms), the published projection of the internal canonical registry; the running tools are the Frame Language analyzer, a public hosted tool at https://frame-language-analyzer.vercel.app, and the frame-language language server, the open-source MCP in the public coordination-structural-integrity-suite/tools repository, which already perform the scan and the replacement. Part III of the grammar (the functioning check) is a working draft pending field testing and is treated as provisional here. This is the third link in the main toolkit chain, after the three-plate grind and the sharper-Occam cut.
---

# Frame Language Vocabulary Check: Implementation Guide

## What this guide is, and what it is not

This is an implementation guide. It is how to run the Frame Language vocabulary check on a real document, written for someone who will use it rather than refine it.

The check catches a specific failure: a term that imports weight it has not earned. Words like accountability, governance, enforcement, transparency, stakeholder, trust, and impact carry force from mechanisms the reader supplies out of prior institutional habit, an apparatus that responds to non-conformance, an answerability running upward, institutional standing backing the claim, none of it stated in the sentence. The check finds those terms, decides whether the term is doing that borrowed work here, and where it is, names what the term was implying so the force comes from what is specified rather than from what the reader fills in.

One distinction is the spine of the whole tool, and getting it wrong is the most common way the check is misused. The problem is not the word. A Frame 1 term carries its force from the sentence structure around it, who is the grammatical subject, which party is acted upon, what mechanism the sentence implies, and replacing the word while leaving that structure intact changes nothing. Swapping accountability for multi-directional accountability leaves the terminal-upward structure exactly where it was. So this is not find-and-replace. It is three checks: is the term doing the borrowed work here, has the replacement named what the structure was implying, and does the result actually function.

What the check decides is the frame of the vocabulary, not whether the content is true or right. That judgment is yours. The check is a conformance pass, the most mechanizable tool in the kit, and it runs inside an AI system end to end, with one edge of judgment noted below.

## When to reach for it

Reach for it whenever the wording of something matters: a specification, a normative claim, a standard, a name, a public document, especially in a register where precision is required. In the toolkit chain it is the third link: after you have ground a result to its floor and cut it to the minimal basis, you hold the surviving terms to this check so the words carry the structure you established rather than borrowing a different one.

It does not fit when the document is deliberately addressed to a Frame 1 audience for whom the precise vocabulary would prevent the requirement from landing; that is a conscious medium judgment, covered as an admissible case below, not a default.

## How to run it: three checks

### Check 1: is the term doing borrowed work here

First, the fast pass: scan against the watchlist, the 33 canonical terms in the registry. Each carries why it is Frame 1, its replacement, its strengthened form, and a slippage note. A hit is a candidate, not a verdict.

Then the blank-filling test, which also catches terms not on the list. Read the sentence, and complete it mentally, supplying what it implies but does not state. For "the evaluation maintains accountability," ask what accountability consists of here: who responds to its absence, against what standard, with what response to non-conformance. If your mind supplies a mechanism that does not appear in the sentence, the term is doing borrowed work. If the sentence already names the parties bound, the verification procedure, and the response to non-conformance, the mechanism is specified and the term may stand on that count.

A term doing borrowed work is not automatically wrong. Five uses are admissible and need no replacement: citation, where the term is the official name of an external entity, an OECD framework, a named legal doctrine; detection, where the term names a Frame 1 pattern you are identifying in something you are analyzing; contextual description, where it accurately describes a Frame 1 system being referenced as such; the developmental bridge, where it meets the reader in the first paragraph or two before the precise vocabulary is established; and naming the stage, where the term is the accurate name of a developmental stage being described. If none of these applies, the term is a normative claim in your own voice and goes to Check 2.

### Check 2: has the replacement named what the structure implied

A replacement is weak when it leaves the implied mechanism unstated, and a weak replacement is why people keep the Frame 1 word, it felt stronger. The fix is the strengthening rule: name the mechanism the Frame 1 term was implying, and the force returns through specification instead of through borrowed weight. There are five kinds of replacement, and the registry gives the form for each watchlist term.

Plain-English terms, replaced by ordinary language plus the named mechanism. Accountability becomes obligation to named parties with a named verification procedure and a named response to non-conformance. Transparency becomes legibility of what is made visible, to whom, through what mechanism. When the surrounding sentence already supplies the mechanism, the one-word replacement is complete.

Technical corpus terms, replaced by a precise term defined on first use, after which it carries full force.

Deference claims, where the term asserts a conclusion rather than a condition: trust, legitimacy, credibility, organizational integrity. These have no one-word replacement. You replace the whole claim structure with a sentence naming the conditions that would make acceptance warranted, verified by a named party.

Relational-assumption terms, where the syntax puts the less-powerful party in the object position: capacity-building, empowerment. Adding a mechanism does not fix this; the sentence has to be inverted so the party becomes the subject of their own condition. The subject test finds the direction: identify the party initiating the action, and ask whether the party who should hold the condition is instead positioned as the recipient. "The funder builds grantee capacity" puts the development that should be the grantee's in object position, so it inverts to "the grantee develops a named function under named completion criteria."

Terms that split by use, where the same word is a structural condition in one sentence and a claim about state in another; the sentence structure, not the word, decides which procedure applies.

### Check 3: does the result function (provisional)

After Parts I and II, content that reads as Frame 2 can still have been absorbed back into a Frame 1 architecture: the grounding missing, the specification captured, the obligation direction inverted, or the whole correct apparatus applied to the wrong territory. This functioning check is the third stage. It is a working draft in the grammar, pending field testing, so treat it as a prompt to look rather than a settled procedure: read the rewritten passage and ask whether its obligations actually run the way the words now say, or whether the old structure survived the vocabulary change.

## A worked example

Take a sentence built almost entirely of borrowed weight: "The protocol governs stakeholder accountability through transparent enforcement."

Check 1. Every load-bearing term is a watchlist hit, and each fails the blank-filling test: governs supplies a decision domain and the standing of parties, none stated; stakeholder supplies a class of relevant parties, undefined; accountability supplies an answerability direction and a response to non-conformance, unstated; transparent supplies what is visible and to whom, unstated; enforcement supplies a detection procedure and a response, unstated. None is a citation or a detection finding; they are the document's own normative claims. All go to Check 2.

Check 2. Name the mechanisms. The protocol becomes a coordination instrument for a named decision domain with the named standing of its parties; stakeholder becomes the cost-bearing parties, specified by their relation to the system; accountability becomes obligation to those named parties with a named verification procedure and a named response to non-conformance; transparent becomes legibility of named information to named parties through a named mechanism; enforcement becomes a named detection procedure and a named response, both required. The sentence is now several sentences, and it says what the original only implied.

The half-measure to refuse: rewriting it as "the protocol governs multi-directional stakeholder accountability through radical transparency" changes the modifiers and keeps every structure intact. That is the word-swap failure, and it is exactly what the slippage notes in the registry warn against. Check 2 is not done until the mechanism is named, not until the adjective is upgraded.

Check 3. Read the rewritten passage and confirm the obligation actually runs toward the cost-bearing parties as the new words say, rather than the old upward-reporting structure having survived under new vocabulary.

## How it is misapplied, and how to catch it

Word-swap without structure. Replacing the term and leaving the sentence structure is the central misuse, the same shape as a half-removal: the word changes, the borrowed mechanism stays. Catch: name the implied mechanism, run Check 2 to its end, and treat a mere modifier upgrade as a non-fix.

Over-flagging admissible uses. Flagging a term that names an external framework, or that detects a Frame 1 pattern in something being analyzed, breaks correct writing. Catch: run the five admissibility cases before replacing; a term naming or detecting Frame 1 is admissible.

Watchlist-only scanning. Checking only the 33 listed terms misses novel ones doing the same borrowed work. Catch: the blank-filling test, which keys on the borrowed mechanism rather than on the specific word.

Force substitution. Keeping the Frame 1 term because the replacement felt weaker is the most common failure. Catch: the strengthening rule restores force by naming the mechanism; a replacement feels weak only while the mechanism is still unstated.

Treating it as a truth check. The check decides the frame of the vocabulary, not whether the claim is correct. Catch: hold that a sentence can be perfectly admissible and still false; the worth and the truth are yours to judge, not the check's.

## How much runs inside AI

This is the most mechanizable tool in the kit, and it already runs inside AI: the watchlist scan and the first-pass replacement are exactly what the public Frame Language analyzer at https://frame-language-analyzer.vercel.app and the open-source frame-language language server do, against the same registry this guide names. Automate that floor freely. Two things keep an edge of judgment. The admissibility cases, especially citation versus a normative claim in the document's own voice, need a reading of intent that the scan does not have, so an automated flag on a citation should be dismissable by a person. And Check 3, the functioning check, is provisional and is a look rather than a rule. So let the machine run the scan and propose the replacements; keep the admissibility call and the functioning read.

## Where this sits

The full three-Part procedure, with all the cases and the tables, is in reference/frame-language-grammar.md. The public watchlist, with each term's replacement, strengthened form, and slippage note, is data/term-registry.json, the published projection of the internal canonical. The running tools are the Frame Language analyzer, the public hosted tool at https://frame-language-analyzer.vercel.app, and the frame-language language server, the open-source MCP in the public coordination-structural-integrity-suite/tools repository, both reading the canonical registry the public file projects from. In the toolkit selector this guide answers the entry for checking terms for hidden weight, and it chains directly after the sharper-Occam cut: grind to a floor, cut to the minimal basis, then hold the surviving terms to this check.
