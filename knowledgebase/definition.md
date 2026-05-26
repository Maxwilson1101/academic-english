# Definition Specification

## Scope

A definition explains the meaning of a term by setting its boundaries and giving it a distinctive identity.

Apply definition rules when introducing key terms, unusual terms, technical terms, or terms that may not be widely known.

## Core Requirements

- Define terms that are central, unfamiliar, specialized, or likely to cause confusion.
- Select the definition type according to the term's importance and complexity.
- Use familiar wording to explain unfamiliar terms whenever possible.
- State the term's class and distinguishing features when a short synonym is insufficient.
- Place brief definitions close to the term being defined.
- Avoid definitions that are circular, vague, too broad, or too narrow.

## Definition Types

### Parenthetical Definition

**Function:** Give a brief, local explanation of a term.

**Use when:** The term needs quick clarification but does not require a full sentence definition.

**Signals:**

- Parentheses immediately after the term: `term (definition)`
- Commas immediately after the term: `term, definition,`
- Alias marker: `also called`

**Patterns:**

- `term (familiar equivalent)`
- `term, also called alias,`
- `term, short explanatory phrase,`

**Rules:**

- Place the definition immediately after the term.
- Keep the definition short.
- Use a synonym, alias, or brief explanatory phrase.
- Use familiar words to clarify unfamiliar terminology.
- Do not use a parenthetical definition for a concept requiring class membership and distinguishing features.

**Evaluation checks:**

- Is the definition adjacent to the term?
- Is the definition brief enough to fit inside parentheses or commas?
- Does the definition clarify the term without interrupting the sentence?
- Would a full sentence definition be clearer?

### Sentence Definition

**Function:** Define a term in a complete sentence by assigning it to a general class and distinguishing it from similar terms.

**Use when:** A brief parenthetical definition is insufficient.

**Required parts:**

- **Term:** the word or phrase being defined.
- **General class:** the broader category to which the term belongs.
- **Distinguishing features:** the features that separate the term from other members of the same class.

**Core patterns:**

- `X is a/an general class which/that distinguishing feature.`
- `A/An general class which/that distinguishing feature is known as X.`
- `A/An general class which/that distinguishing feature is called X.`

**Reduced relative-clause patterns:**

- `X is a/an general class distinguishing feature.`
- `A/An general class distinguishing feature is called X.`

**Rules:**

- State the term and general class explicitly.
- Add distinguishing features after the general class.
- Use `which` or `that` to introduce distinguishing features when a full relative clause is needed.
- Use a gerund clause in place of `which/that` when the feature describes an active or ongoing relation.
- Use a past-participle clause when the noun being modified is the logical object of the verb in the relative clause.
- Ensure the distinguishing feature applies to the term and not to the whole class.
- Do not omit the general class unless it is already explicit in the immediate context.

**Evaluation checks:**

- What term is being defined?
- What general class does the term belong to?
- What feature distinguishes the term from similar class members?
- Is the definition grammatically complete?
- Does the definition avoid circular wording?

### Extended Definition

**Function:** Explain an important or complex term beyond a brief phrase or single sentence.

**Use when:** The term is central to the text, technically complex, or likely to require fuller explanation.

**Rules:**

- Use an extended definition only when parenthetical or sentence definition is not enough.
- Begin with or include a clear sentence definition when possible.
- Add further explanation only as needed to prevent misunderstanding.
- Keep the extended definition focused on the term's meaning and boundaries.

**Evaluation checks:**

- Is the term important or complex enough to require extended explanation?
- Does the definition still identify the term's class and distinguishing features?
- Does the added explanation clarify the term rather than drift into unrelated description?

## Definition Pattern Details

### Class-Feature Structure

**Function:** Build precise sentence definitions.

**Pattern:**

- `term = general class + distinguishing feature`

**Rules:**

- Choose a general class that is broad enough to include the term.
- Choose distinguishing features that are specific enough to separate the term from similar terms.
- Avoid using the term itself as the class or feature.

### Relative Clause

**Function:** Add distinguishing features with `which` or `that`.

**Patterns:**

- `X is a/an general class which feature.`
- `X is a/an general class that feature.`

**Rules:**

- Use when the distinguishing feature needs a finite verb.
- Keep the clause attached to the class noun it modifies.

### Gerund Clause

**Function:** Condense a relative clause when the class noun performs the action or has an active relation.

**Pattern:**

- `X is a/an general class consisting of parts.`

**Rules:**

- Use when the gerund phrase preserves the meaning of a `which/that` clause.
- Do not use a gerund clause if it changes the logical relation between the class noun and the feature.

### Past-Participle Clause

**Function:** Condense a relative clause when the class noun receives the action.

**Pattern:**

- `X is a/an general class formed by process.`

**Rules:**

- Use when the modified noun is the logical object of the verb in the full relative clause.
- Do not use a past participle when the class noun performs the action.

## Application Procedure

1. Identify terms that are key, unusual, technical, or potentially unclear.
2. Estimate each term's importance and complexity.
3. Choose a parenthetical definition for quick clarification.
4. Choose a sentence definition when the term needs class membership and distinguishing features.
5. Choose an extended definition when a sentence definition is not enough.
6. Check that the definition is clear, bounded, non-circular, and placed where the reader needs it.

## Output Contract

A valid definition must:

- Identify the term being defined.
- Clarify the term's meaning and boundaries.
- Use a definition type appropriate to the term's importance and complexity.
- Use familiar wording where possible.
- Include a general class and distinguishing features for sentence definitions.
- Keep brief definitions adjacent to the defined term.
- Avoid ambiguity, circularity, overgeneralization, and unnecessary detail.
