# Cohesion Specification

## Scope

Cohesion is the explicit grammatical and lexical linking that connects words, clauses, sentences, and adjacent ideas so that a text reads as a unified sequence rather than a set of unrelated sentences.

Apply cohesion rules during text generation, revision, and evaluation whenever sentence-level continuity matters.

## Core Requirements

- Connect each sentence to relevant prior or following text unless it begins a clearly new section, stage, or topic.
- Make relations between ideas recoverable through grammatical devices, lexical choices, or both.
- Use cohesive devices to clarify reference, continuity, contrast, cause, addition, substitution, omission, category membership, and topic unity.
- Prefer explicit signals when the relation between sentences could be missed or misread.
- Avoid ambiguous pronouns, unclear substitutions, unsupported omissions, and abrupt lexical shifts.

## Cohesion Types

### Grammatical Cohesion

Grammatical cohesion uses grammatical structures to create links within or between sentences.

#### Reference

**Function:** Link an expression to an entity mentioned elsewhere in the text.

**Signals:** pronouns and referring expressions, including `he`, `she`, `it`, `they`, `this`, `that`, `these`, `those`, `the former`, `the latter`.

**Patterns:**

- **Backward reference:** the referring expression points to an earlier entity.
- **Forward reference:** the referring expression points to an entity named later.

**Rules:**

- Ensure each referring expression has a clear antecedent.
- Use backward reference as the default pattern.
- Use forward reference only when the delayed identification is easy to resolve.
- Repeat the noun instead of using a pronoun when multiple possible antecedents exist.
- Do not let a pronoun introduce ambiguity about whether two mentions refer to the same entity.

**Evaluation checks:**

- Can the antecedent be identified without guessing?
- Is the antecedent close enough to remain accessible?
- Could another noun in the surrounding text compete as the antecedent?

#### Substitution

**Function:** Replace a recoverable item with another linguistic item to avoid unnecessary repetition.

**Signals:** substitute forms such as `one`, `ones`, `do`, `does`, `did`, `so`, `same`.

**Rules:**

- Use substitution only when the substituted item can be restored without changing the meaning.
- Keep the replacement grammatically compatible with the original item.
- Prefer substitution when the repeated item is obvious and repetition would be heavy.
- Avoid substitution when restoration would be unclear, ungrammatical, or semantically changed.

**Distinction from reference:**

- In substitution, the substitute can be replaced by the original wording without changing meaning.
- In reference, replacing the referring expression with the antecedent may create ambiguity or alter discourse interpretation.

**Evaluation checks:**

- What exact item is replaced?
- Can the original item be reinserted naturally?
- Does reinsertion preserve meaning and reference?

#### Ellipsis

**Function:** Omit a recoverable item when the reader can infer it from nearby text.

**Signal:** absence of an expected word, phrase, or clause whose meaning is supplied by the surrounding structure.

**Rules:**

- Use ellipsis only when the omitted material is structurally and semantically recoverable.
- Keep the omitted item close to its source expression.
- Use ellipsis to reduce repetition, not to hide required information.
- Avoid ellipsis when the omission could create syntactic confusion or multiple possible completions.

**Evaluation checks:**

- What material has been omitted?
- Is the omitted material present or strongly implied nearby?
- Can the sentence be expanded without changing meaning?

#### Conjunction

**Function:** Signal logical relations between words, phrases, clauses, or sentences.

##### Coordinating Conjunctions

**Function:** Join grammatically similar units.

**Signals:** `and`, `but`, `or`, `so`.

**Rules:**

- Join units of the same grammatical level: word with word, phrase with phrase, clause with clause.
- Use `and` for addition, `but` for contrast, `or` for alternatives, and `so` for result.
- Ensure parallel structure where coordination would otherwise be hard to parse.

##### Subordinating Conjunctions

**Function:** Join a dependent clause to an independent clause.

**Signals:** `because`, `although`, `before`, `as long as`, `in spite of`, `even though`.

**Rules:**

- Place the subordinating conjunction before the dependent clause it introduces.
- Use subordination to encode relations such as cause, concession, condition, time, or contrast.
- Ensure the independent clause can stand alone and the dependent clause cannot function as a complete sentence in context.

##### Sentence Linking Words and Phrases

**Function:** Connect one sentence to a preceding sentence or idea.

**Signals:** `consequently`, `therefore`, `in addition`, `however`, `on the other hand`, `for example`, `in contrast`.

**Rules:**

- Place sentence-linking expressions near the beginning of the sentence unless style or emphasis requires another position.
- Use them to signal continuation, addition, contrast, consequence, illustration, or transition.
- Match the connector to the actual semantic relation.
- Do not use a connector as decoration; remove it if no relation is being signaled.

**Evaluation checks for conjunction:**

- What relation does the connector signal?
- Are the linked units grammatically compatible?
- Does the connector accurately describe the relation between the linked ideas?
- Is a connector needed to prevent an abrupt transition?

### Lexical Cohesion

Lexical cohesion uses vocabulary selection to create continuity of topic, category, and semantic field.

#### Reiteration

**Function:** Maintain topic continuity by repeating or varying lexical items.

**Signals:**

- **Exact repetition:** reuse of the same lexical item.
- **Synonym:** use of a word or expression with the same or nearly the same meaning.
- **Superordinate:** use of a broader category term that includes earlier items.

**Rules:**

- Repeat key terms when precision is more important than stylistic variation.
- Use synonyms only when they preserve the intended meaning in context.
- Use superordinates to group specific items under a shared category.
- Avoid unnecessary synonym variation for technical terms when variation could imply a new concept.
- Maintain consistent terminology for central entities, processes, and categories.

**Evaluation checks:**

- Are key concepts named consistently?
- Do synonyms preserve the same meaning and scope?
- Does a superordinate accurately include the items it groups?
- Does lexical variation clarify the text or introduce instability?

#### Collocation

**Function:** Create unity through words that naturally or conventionally co-occur in the same topic area.

**Signals:** semantically associated vocabulary appearing within or across sentence boundaries, such as `disease`, `diagnosis`, `doctors`, `symptoms`.

**Rules:**

- Use vocabulary that belongs to the same semantic field as the topic.
- Preserve expected associations between actions, objects, roles, and contexts.
- Let collocational patterns reinforce the topic across adjacent sentences.
- Avoid sudden shifts to unrelated lexical fields unless the text explicitly signals a topic change.
- Check domain appropriateness for technical collocations.

**Evaluation checks:**

- Do nearby words belong to a coherent semantic field?
- Are topic-related roles, actions, and objects compatible?
- Does the vocabulary support topic unity across sentence boundaries?
- Are any word choices unexpected enough to require explanation?

## Application Procedure

1. Identify the local topic and semantic relation between each sentence and its surrounding text.
2. Choose grammatical cohesion when the link depends on reference, replacement, omission, or logical relation.
3. Choose lexical cohesion when the link depends on repeated concepts, category relations, synonyms, or shared semantic fields.
4. Add, revise, or remove cohesive devices until each link is explicit enough for the target reader.
5. Recheck for ambiguity, inaccurate connectors, unstable terminology, and unsupported omissions.

## Output Contract

A cohesive text must:

- Make sentence-to-sentence relations explicit or easily recoverable.
- Use clear reference chains for entities and concepts.
- Use substitution and ellipsis only when the omitted or replaced material is recoverable.
- Use conjunctions that accurately encode the intended logical relation.
- Maintain lexical continuity through repetition, controlled variation, superordinates, and domain-appropriate collocation.
- Avoid treating sentences as isolated units when they belong to the same topic sequence.
