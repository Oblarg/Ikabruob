# Ikabruob

Welcome!

This is a project to improve mathematical nomenclature.  Currently, it takes the form of a dictionary of pure and applied mathematical definitions and theorems.

## Guiding Principles

The dictionary has only one hard rule: *no concept may be named after a person.*

Personal names are semantically-empty identifiers.  When we name a mathematical concept after a person, we give up any opportunity for the name of the concept to help teach the concept.

While history of mathematics is an important subject worthy of study in its own right, we believe technical subjects - mathematics included - should strive for conceptual clarity in their nomenclature.  

## Format

Dictionary entries should be markdown files with metadata headers in YAML.  Each entry should have its own file.  The header format is as follows:

```markdown
---
name: string
traditional: string | string[]
alternate: string | string[]
---
```

Remarks and discussion of the naming of the entity should be written in the body of the markdown file.
