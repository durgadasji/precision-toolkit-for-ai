---
title: Frame Language Grammar
type: reference
version: 0.1.1
date: 2026-06-11
status: Public release version (2026-06-12). Parts I and II are mature and carry the construction-grammar diagnostics, the borrowed-prior blank-filling test and the subject test. Part III still needs field testing against real documents before finalization and is marked provisional throughout. The concept-type coercion diagnostic is identified and queued as the next addition.
---

# Frame Language Grammar

This document is the reference layer for the Frame Language skill. It contains three diagnostic procedures and a canonical vocabulary table. The skill's runtime sequence draws on each procedure in order.

**When to use this document:** When working with Frame 1 vocabulary in any corpus document. The three procedures run in sequence; each one depends on the prior.

---

## How the Three Procedures Connect

The procedures answer three questions in order:

**Part I - Before replacing:** Should this Frame 1 term be replaced at all in this sentence?

**Part II - During replacing:** Is this Frame 2 replacement strong enough?

**Part III - After replacing:** Is the resulting Frame 2 content actually functioning?

These are not independent checks. Part I covers the straightforward admissible cases first. If a term is not covered by those cases, Part II runs before the final admissibility determination is made.

The three procedures address vocabulary, but the structural problem is not in the vocabulary. A Frame 1 term carries its force from the way it is positioned in a sentence, including who is the grammatical subject, which party is acted upon, and what mechanisms the sentence implies. A term like accountability is not Frame 1 because the word is wrong; it is Frame 1 because the sentence structures in which it conventionally appears assign roles and imply mechanisms that are not named. Replacing the vocabulary without replacing the underlying sentence structure leaves those role assignments and implied mechanisms intact. Part I determines whether the structure in this sentence is doing Frame 1 work; Part II determines whether the replacement has named what the Frame 1 structure was implying; Part III determines whether the resulting Frame 2 content is functioning or has been absorbed back into a Frame 1 architecture.

---

## Part I: The Pre-Replacement Check

Before attempting to replace a Frame 1 term, identify what function the term is performing in the sentence.

### Borrowed-prior detection (the blank-filling test)

Before running the admissibility cases, confirm that the term is doing borrowed-prior work: carrying structural weight through the reader's prior knowledge of institutional language rather than through elements named in the sentence.

Read the sentence containing the Frame 1 term, then complete it mentally, supplying what the sentence implies but does not state. For "the evaluation maintains accountability," ask what the term consists of here: who responds to its absence, against what standard, with what response to non-conformance. If your mind supplies a mechanism that does not appear in the sentence, an apparatus that responds to non-conformance, an answerability relation running upward, or institutional weight backing the claim, the term is doing borrowed-prior work.

If the sentence already names the mechanism elements, the party bound, the verification procedure, and the response to non-conformance, then mechanism specification is complete and Part II strengthening may not be required. The blank-filling test resolves only the mechanism question. Whether the vocabulary is appropriate in the document's own register, meaning a normative claim in this register rather than a citation of another framework's term, is a separate question the admissibility cases settle. A sentence that names every mechanism element while using Frame 1 vocabulary in a normative claim of its own still requires admissibility justification or replacement.

If the term is doing borrowed-prior work, proceed to the admissibility cases below; the detection step confirms that Part I applies, and the cases determine the outcome. Do not skip to replacement.

### Admissible without replacement

**Citation use.** The term is the official formal name of a specific external entity: a named field, a named document, a named legal doctrine, a named institutional framework. Examples: "governance research," "OECD accountability framework," "indigenous governance authority." The term cannot be replaced without misrepresenting what is being cited. Test: is this term the entity's own name? If yes: admissible as citation, no replacement needed.

**Detection use.** The term names a Frame 1 mechanism being identified through Frame 2 analysis. A Frame Language Analyzer output that says "this clause functions as an enforcement mechanism" is using "enforcement" correctly: it names the Frame 1 structure detected. The term names what is present in the system being analyzed, not a design claim about what should be present. Test: is this sentence identifying a Frame 1 pattern in an external document or system? If yes: admissible as detection, no replacement needed.

**Contextual description use.** The term accurately describes a Frame 1 system or historical practice being referenced as such. "The accountability mechanisms in traditional grant-making" describes how Frame 1 systems actually work. Replacing with Frame 2 vocabulary would misrepresent the historical reality being described. Test: is the sentence describing a Frame 1 system other than the one this document is specifying? If yes: admissible as contextual description, no replacement needed.

**Developmental bridge use.** The term meets the reader at their developmental position in the opening of a document before Frame 2 vocabulary has been established through use. The document transitions to Frame 2 vocabulary after the bridge. Test: is this in the first one to two paragraphs of the document, and does the document transition to Frame 2 vocabulary afterward? If yes: admissible in that position only.

**Naming the stage.** Frame 2 writing that describes Frame 1 as a developmental stage uses Frame 1 terms as accurate names of that stage. "Frame 1 coordination structures use enforcement mechanisms and accountability lines as their primary instruments" is Frame 2 writing about Frame 1. Test: is the Frame 1 term the subject of a developmental description rather than the vocabulary of a normative claim? If yes: admissible as developmental naming.

If none of these cases apply, proceed to Part II before making the final admissibility determination.

---

### After Part II: The Final Admissibility Determination

If Part II has been tried and the Frame 2 equivalent cannot be strengthened to carry sufficient force for this context, ask:

**Communication medium use.** The document is addressed to a Frame 1 audience where Frame 2 vocabulary would cause the document to fail its structural purpose. The Frame 1 term is the medium through which a structurally correct requirement reaches a Frame 1 audience. This requires two conditions both met: (1) the intended reader is a Frame 1 actor for whom Frame 2 vocabulary would prevent adoption of the requirement; and (2) this is a conscious design judgment, not a default. A writer applying this case has tried Part II and concluded that even a strengthened Frame 2 form would not achieve the structural goal with this reader.

If none of the above cases apply, the term is one of four failure types and must be replaced:

**Normative claim in a standards register.** Frame 1 term in a load-bearing normative position where Frame 2 precision is required. The register does not admit it. Replace.

**Design vocabulary.** Frame 1 term naming a structural condition this document is specifying, not citing or describing. Not a citation, not a detection finding, not a historical reference. Replace.

**Passed developmental stage.** Frame 1 term in a register where Frame 2 vocabulary is established and expected. The reader has climbed past this rung. Replace.

**Force substitution.** Frame 1 term retained because the Frame 2 equivalent felt weaker, rather than because any admissible case applies. This is the most common failure type. A writer who has not tried Part II, or who tried Part II without applying the full strengthening procedure, is in this case. This failure type is only definitively confirmed after Part II has been genuinely attempted. Replace, using the Part II strengthening procedure.

---

## Part II: The Replacement Quality Check

A Frame 2 replacement that passes the two-part test (names the rope, addresses projection) may still be weaker than the Frame 1 term it replaced. Frame 1 terms carry force from implied mechanisms: enforcement apparatus, hierarchical answerability, institutional authority backing the claim. Removing those assumptions also removes the mass beneath the term.

**The strengthening rule:** Frame 2 replacements are weak when they leave the implied Frame 1 mechanisms unstated. The fix: name those mechanisms explicitly. Frame 2 has named verification procedures, detection with named response, specified conformance conditions, and consequences that are stated rather than implied. When these are named alongside the Frame 2 term, force is restored through specification rather than through implicit institutional weight.

### Plain-English Frame 2 terms

The replacement is ordinary language with a more precise scope. These terms are weakened by the removal of Frame 1 implied mechanisms. Strengthen by adding the missing mechanism elements.

Pattern: `[Frame 2 term] + [named mechanism that grounds it]`

| Frame 1 term | Basic Frame 2 replacement | Strengthened form |
| :-- | :-- | :-- |
| Accountability | Obligation | Obligation to [named parties] with [named verification procedure] and [named response to non-conformance] |
| Governance | Coordination instrument | Coordination instrument for [named decision domain] with [named standing of participating parties] |
| Compliance | Conformance | Conformance with [named conditions] verified by [named procedure] |
| Transparency | Legibility | Legibility of [what is made visible] to [named participants] through [named mechanism] |
| Management | Stewardship | Stewardship of [what is held] under [named responsibility criteria] for [named beneficiaries] |
| Oversight | Monitoring | Monitoring by [named monitoring party] with [named authority to act on findings] |
| Due diligence | Verification | Verification of [named claims] against [named evidence standard] with [named response to discrepancy] |
| Impact | Effect / Outcome | [Named effect] on [named cost-bearing parties] as measured by [named indicator] |
| Participation | Decision-standing | [Party] holds [named decision-standing] in [named domain] with [named mechanism for affecting outcomes] |
| Enforcement | Detection with named response | Named detection procedure AND named response to non-conformance (both elements required; either missing weakens the form) |

**Contextual note:** When the surrounding sentence already provides the mechanism elements, the one-word replacement is complete and correct. Mechanism specification is mandatory only when the sentence asserts the Frame 2 term without its grounding.

### Technical corpus vocabulary

The replacement is a technical term from the corpus (Multiplex, Gravity, Coordination Actor, Cost-Bearing Party, Obligation Mesh, Banyan, Columnar). These terms are strong within the corpus and weak outside it. Strengthen by defining the term on first use in the document. After that first-use definition, the term carries full force in all subsequent uses without repeating the definition.

Pattern: `[Technical Frame 2 term] + [structural definition on first use]`

| Frame 1 term | Technical Frame 2 replacement | What the first-use definition must establish |
| :-- | :-- | :-- |
| Accountability (direction) | Multiplex Obligation Directions | Multi-directional flow of structural commitments arising from a role, not terminal-upward reporting |
| Stakeholder | Coordination actor; Cost-bearing party | Anyone whose coordination activity or cost-bearing relation to the system makes them structurally relevant, regardless of formal standing |
| Decentralized governance (structural) | Multiplex coordination architecture | Distributed decision-standing with full bandwidth across registers and specified consent; not merely distributed Frame 1 control |
| Authority | Positional gravity; Gravitas | Weight arising from origination through genuine inquiry or demonstrated coordination capacity, not from appointment or enforcement capacity |

### Deference claims

Some Frame 1 terms name a conclusion rather than a structural condition. They assert that a party or claim warrants deference without specifying the structural basis. Frame 2 does not make deference claims; it names the conditions that would make acceptance structurally warranted. There is no Frame 2 equivalent term. The Frame 2 equivalent replaces the entire claim structure.

Pattern: replace the sentence asserting the conclusion with a sentence naming the conditions that would generate it.

| Frame 1 term | What it claims | Frame 2 replacement structure |
| :-- | :-- | :-- |
| Trust (institutional) | This party warrants deference | [Party] meets [named conditions] verified by [named procedure] |
| Legitimacy | This institution warrants acceptance | [Institution] meets [named conditions] whose basis is [origination / demonstrated capacity / cost-bearing relation] |
| Credibility | This claim warrants acceptance | [Claim] grounded in [named evidence type] verifiable by [named party] |
| Integrity (organizational) | This organization keeps its commitments | [Stated commitments] made independently verifiable by [named structural conditions] |

### Relational-assumption terms

Some Frame 1 terms embed a power relation in their syntactic structure, with the less-powerful party as the object rather than the subject. Adding mechanism specification does not fix this; the sentence structure must be inverted so the party at issue becomes the agent of the structural condition, not its recipient.

The subject test confirms relational inversion is needed and identifies the direction of the inversion. For any term in the Terms that split by use case section below, make the split-by-use determination first; the subject test applies after the applicable Part II procedure has been identified.

Step 1: determine whether the sentence is active or passive. In active voice, identify the grammatical subject, the noun phrase doing the action. In passive voice, identify the agent, the party in the by phrase, or the implied agent if absent; a passive construction places the acted-upon party in subject position, so the relational-assumption failure is in the implied causer, not the grammatical subject. If the agent is absent, ask what party the context requires to have initiated the action. Restate a nominalization, such as "the empowerment of communities by the program," as a predicate sentence before applying the test.

Step 2: ask whether the party initiating the structural action is the party who should hold the structural condition. If a party who should hold a condition of their own, their own standing, function, or role, is instead positioned as the recipient of another party's action, as object in active voice or as the acted-upon party in passive voice, relational inversion is required.

In "the funder builds grantee capacity," the subject is the funder and the development that should be the grantee's sits in object position, so inversion is required. In "grantees are empowered by the program," the program is the causer of a standing that should be the community's, so inversion is required even though the grantees are the grammatical subject. For a term not yet in the table below, Step 2 takes judgment about which party should hold the condition; for the table's existing entries it is already settled. This test scopes to the relational-assumption procedure only; the related security-bellwether diagnostic, which asks whether one actor holds an authorization role without checks, is a distinct procedure in the CRAFT application.

Pattern: restructure the sentence so the party is the subject, not the object of the intervention.

| Frame 1 term | Frame 1 sentence structure | Frame 2 restructured form |
| :-- | :-- | :-- |
| Capacity building | Funder builds grantee's capacity | Grantee develops [named function] under [named completion criteria] |
| Empowerment | Actor empowers community | Community holds [named standing] in [named domain] through [named structural conditions] |
| Beneficiary (as passive recipient) | Organization delivers to beneficiaries | [Named parties] whose cost-bearing relation to the system is [specified] |

### Terms that split by use case

Some Frame 1 terms land in different categories depending on what the sentence is claiming. The term is not the diagnostic; the sentence structure is.

Test: is the sentence naming a structural condition, or making a claim about the state of a system? Structural condition sentences use the mechanism specification procedure. Claim-about-state sentences use the deference claim or relational inversion procedure.

| Term | When naming a structural condition | When making a claim about state |
| :-- | :-- | :-- |
| Decentralization | "The governance structure is Multiplex" - technical corpus replacement applies | "We are transitioning to decentralized governance" - plain-English procedure: add destination parties, domain, criteria |
| Representation | "This role carries the interests of this party" - plain-English procedure: add derivation basis, scope, recall mechanism | "The community is represented" - deference claim: name the structural conditions grounding the decision-standing |
| Participation | "This party holds decision-standing in this domain" - plain-English procedure: name the standing, domain, affecting mechanism | "All stakeholders participated" - deference claim: name the structural conditions making participation more than presence |

### Post-pass audit step

After applying replacements, run this check:

1. Identify which category applies to each replacement (plain-English, technical corpus, deference claim, relational-assumption, or split-by-use).
2. Plain-English replacements: are the mechanism elements present? If not, add them.
3. Technical corpus replacements: is the term defined in context on first use? If not, add the definition.
4. Deference claims: does the sentence name conditions or assert a conclusion? If it asserts a conclusion, replace the claim structure.
5. Relational-assumption terms: is the party at issue the subject of the sentence or the object? If it is the object, restructure.
6. Read the sentence. Does it carry equivalent force to the Frame 1 term it replaced? If not, the mechanism specification is incomplete.

---

## Part III: The Frame 2 Functioning Check

*Status: Working draft. The eight types below were derived from the skill's existing failure mode descriptions and from first principles. They need field testing against real governance documents before this section is finalized. Detection signatures are indicative, not confirmed.*

A Frame 2 document that has passed Parts I and II may still contain Frame 2 content that is not functioning as Frame 2. The organizing question: which constitutive element of Frame 2 is failing, and how?

The three constitutive elements of Frame 2 are: (1) grounding in recognition of what cannot be harmed; (2) structural specification of conditions, parties, and procedures; (3) multi-directional obligation directions. Failure occurs when any element is absent, captured, or inverted. A fourth failure category applies when all elements are correct but the territory they are applied to is wrong.

### Grounding failures

**The Transcendence Claim.** The organization claims Frame 3 as a property it holds, then uses that claim to exempt itself from Frame 2 precision requirements. Frame 3 language appears in load-bearing normative positions rather than in grounding statements that precede the normative content.

Detection: Frame 3 language where a structural condition should be named. Test: would removing the Frame 3 claim leave a gap where a verifiable structural condition should appear? If yes: this is the failure.

**The Declaration Exploit.** Frame 2 conditions are named and defined correctly but treated as established by the act of naming rather than by structural conditions being built. "We commit to Multiplex obligation architecture" as performance rather than as description of conditions that have been instantiated.

Detection: Frame 2 structural vocabulary in future tense or commitment language without named instantiation criteria. "Our governance will embody..." without the structural conditions that would make the claim independently verifiable.

### Specification failures

**The Precision Facade.** Frame 2 vocabulary is used correctly throughout, but the precision is applied to elements that do not constrain power holders. The elements that would matter structurally - who can remove a decision-maker, what happens when a named obligation is not met, which cost-bearing parties have standing to trigger a response - are left vague while procedurally irrelevant details are specified precisely.

Detection: zero Frame 1 terms; detailed specification of processes with no named response to violation; obligation directions correct at the vocabulary level but absent at the mechanism level. Distinguishing from Vocabulary Without Architecture below: here, the architecture could be Frame 2 if the load-bearing elements were specified. This is an incomplete Frame 2 document; the other is a Frame 1 document wearing Frame 2 vocabulary.

**Partial Instantiation.** The Frame 2 form is present but a constitutively required element is missing. Detection without named response. Capacity with no named obligation direction. Consent architecture without named cost-bearing parties. Each element present is correctly specified; the form is structurally incomplete because a required element is absent.

Detection: each term present passes the two-part test; the standard requires elements that are not present; the missing elements are in a constitutive relation with what is present. Note: detection without response is the canonical example. Finding a violation with no named outcome is structurally equivalent to no detection at all.

**Direction Without Destination.** Movement away from Frame 1 is specified without specifying the Frame 2 destination. The direction of travel is correct; the destination is unnamed. The movement can stop anywhere, drift back, and cannot be evaluated for completion.

Detection: Frame 1 terms named as what is being moved away from; Frame 2 conditions named in orientation language without structural specificity; temporal markers ("transitioning toward," "moving to") without named endpoint criteria.

### Obligation direction failures

**Vocabulary Without Architecture.** Frame 2 vocabulary is used to describe what is structurally a Frame 1 architecture. The vocabulary is correct; the structure it describes is not Frame 2. The governance document uses Multiplex, obligation mesh, multi-directional, cost-bearing party - and describes a system that is terminal-upward in its actual decision architecture.

Detection: Frame 2 vocabulary used to describe decision processes; cross-check who has standing to remove a decision-maker, trigger a response, or block a motion. If the actual architecture is terminal-upward beneath the vocabulary: this is the failure. Distinguishing from The Precision Facade: that type has underspecified load-bearing elements; this type has the wrong architecture regardless of how precisely it is specified.

### Territory failures

**The Correct Map / Wrong Territory.** The Frame 2 instrument is internally coherent and correctly specified, but the parties named are not the actual cost-bearing parties in the system. Obligation directions are multi-directional among the named parties. The named parties are not the people with the most structural exposure to the system's failures.

Detection: well-specified obligation directions among named parties; no specification of who else bears costs outside that boundary; the cost-bearing party identification was never performed against the full structural reality, only against the formal membership boundary.

**The Frozen Map.** The Frame 2 specification was derived from accurate structural analysis of conditions that have since changed. The instrument continues to be applied as if the conditions it derived from were still present.

Detection: unlike the other types, this cannot be detected from the document alone. It requires comparing the document's named conditions against current structural reality. Signs: the instrument has not been reviewed since initial publication; named cost-bearing parties have shifted; the structural conditions the instrument was designed to address have been superseded or replaced.

---

## Appendix A: Canonical Vocabulary Table

The canonical Frame 2 equivalents for the most frequent Frame 1 terms. The third column gives the strengthened form. Deference claim terms list the replacement claim structure rather than a term; that column is marked accordingly.

| Frame 1 term | Frame 2 replacement | Strengthened form or replacement structure | Procedure |
| :-- | :-- | :-- | :-- |
| Accountability | Obligation; Multiplex Obligation Directions | Obligation to [named parties] with [named verification] and [named response to non-conformance]; Multiplex Obligation Directions (define on first use) | Plain-English / Technical corpus |
| Authority (positional) | Positional gravity; Gravitas | Define on first use: weight arising from origination, not appointment | Technical corpus |
| Capacity building | Structural development of [function] | Structural development of [named function] within [named party] under [named completion criteria] | Relational inversion |
| Compliance | Conformance | Conformance with [named conditions] verified by [named procedure] | Plain-English |
| Credibility | - | [Claim] grounded in [named evidence type] verifiable by [named party] | Deference claim |
| Decentralized governance (structural) | Multiplex coordination architecture | Define on first use | Technical corpus |
| Decentralization (process sense) | Transition of decision-standing | Transition of decision-standing to [named parties] in [named domain] under [named criteria] | Plain-English |
| Due diligence | Verification | Verification of [named claims] against [named evidence standard] with [named response to discrepancy] | Plain-English |
| Beneficiary (as passive recipient) | Named parties with specified cost-bearing relation | [Named parties] whose cost-bearing relation to the system is [specified]; note: "beneficiaries" is admissible in the destination slot of stewardship specifications ("stewardship of [x] for [named beneficiaries]") where the term names the parties the stewardship obligation runs toward, not where it positions them as passive recipients of delivery | Relational inversion |
| Empowerment | Named structural conditions | [Named party] holds [named standing] in [named domain] through [named structural conditions] | Relational inversion |
| Enforcement | Detection with named response | Named detection procedure AND named response (both required; either absent weakens the form) | Plain-English |
| Fiduciary duty | Multiplex stewardship obligation | Define on first use | Technical corpus |
| Governance | Coordination instrument | Coordination instrument for [named decision domain] with [named standing of participating parties] | Plain-English |
| Impact | Named effect on named parties | [Named effect] on [named cost-bearing parties] as measured by [named indicator] | Plain-English |
| Incentive | Contribution condition | Contribution condition arising from [cost-bearing relation / named structural basis]; distinguish structural participation from extrinsic reward design | Plain-English |
| Integrity (organizational) | - | [Stated commitments] made independently verifiable by [named structural conditions] | Deference claim |
| Legitimacy | - | [Claim or institution] meets [named conditions] whose basis is [origination / demonstrated capacity / cost-bearing relation] | Deference claim |
| Management | Stewardship | Stewardship of [what is held] under [named responsibility criteria] for [named beneficiaries] | Plain-English |
| Oversight | Monitoring | Monitoring by [named monitoring party] with [named authority to act on findings] | Plain-English |
| Participation (named role) | Decision-standing | [Party] holds [named decision-standing] in [named domain] with [named mechanism for affecting outcomes] | Plain-English |
| Participation (inclusion claim) | - | [Named structural conditions] under which participation constitutes more than presence | Deference claim |
| Representation (structural role) | Named standing | [Party] holds standing in [named domain] on basis of [derivation] with [named scope and recall mechanism] | Plain-English |
| Representation (inclusion claim) | - | [Named structural conditions] under which [party]'s decision-standing is grounded in cost-bearing relation or demonstrated knowledge | Deference claim |
| Stakeholder | Coordination actor; Cost-bearing party | Use cost-bearing party when the structural point is the absence of formal standing; use coordination actor when naming any structurally relevant party | Technical corpus |
| Transparency | Legibility | Legibility of [what is made visible] to [named participants] through [named mechanism] | Plain-English |
| Trust (institutional) | - | [Party] meets [named conditions] verified by [named procedure] | Deference claim |

---

## Version Notes

| Version | Date | Changes |
| :-- | :-- | :-- |
| 0.1.0 | 2026-05-15 | Initial draft. Parts I and II from the disambiguation and strengthening work. Part III from failure-mode descriptions and first principles; not yet field-tested. Canonical vocabulary table with strengthened forms. |
| 0.1.1 | 2026-06-11 | Inserted the construction-grammar diagnostics: the borrowed-prior blank-filling test at the head of Part I, the subject test in the Part II relational-assumption section, and the cross-cutting finding that the structural content is in the construction, not the vocabulary, in How the Three Procedures Connect. The concept-type coercion diagnostic, selective deletion as the inter-frame type-shift, is identified and queued as the next addition, not yet drafted as a procedure. |
