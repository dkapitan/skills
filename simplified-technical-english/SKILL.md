---
name: simplified-technical-english
description: Write documentation in simplified technical english.
license: Complete terms in LICENSE.txt
---

# Simplified Technical English (ASD-STE100)

Write or convert technical text to comply with the grammatical and structural rules of the ASD-STE100 standard. Use when requested to write or review technical documentation, manuals, or procedures in STE.

## When to use
The user asks to write, edit, or review text in "Simplified Technical English", "STE", or "ASD-STE100". Writing instructions for a non-native English audience.

## STE Writing Rules

Apply these rules strictly to all output

### Length
- Max 20 words per sentence for instructions.
- Max 25 words per sentence for descriptions.
- Max 6 sentences per paragraph. One topic per paragraph.

### Structure
- Exactly one instruction per sentence.
- Use vertical lists for complex text.
- Never omit articles, subjects, or verbs to save space (e.g., write "Install the pin", not "Install pin").
- Start safety instructions with a clear condition or command.

### Nouns
- No multi-word nouns longer than 3 words.

### Verbs & Voice:
- Use Active Voice. (Passive voice is only allowed in descriptions if the agent is unknown).
- Allowed verb forms ONLY: infinitive, imperative, simple present, simple past, simple future, and past participle (only as an adjective).
- No complex verb tenses or auxiliary verbs.
- The "-ing" form is ONLY allowed as a technical noun or modifier (e.g., "landing gear").

### Vocabulary:
- Stick to one word, one part of speech, one meaning. For example, use "test" only as a noun, and "close" only for physical proximity or electrical circuits.

## Gotchas
- Do not let LLM verbosity override the 20/25 word limits. Be ruthlessly brief but grammatically complete.
- Be careful with "-ing" verbs (gerunds/participles). They are usually violations in STE unless acting strictly as a noun/adjective.
