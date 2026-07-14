```markdown
# Introduction to Artificial Intelligence: Machine Learning and Deep Learning

## Overview
- **Author**: Niloy Ganguly, Professor at IIT Kharagpur
- **Focus**: Discusses the evolution and current state of Artificial Intelligence (AI), highlighting key milestones and challenges.

## What is Artificial Intelligence?
- **Definition**: Automation of activities associated with human thinking (Bellman, 1978).
- **Components**:
  - Decision making
  - Problem solving
  - Learning
  - Study of mental faculties through computational models (Charniak & McDermott, 1985)
  - Systems that think like humans
  - Systems that think rationally

## Thinking vs. Acting
- **Four Quadrant Framework**: Think Humanly/Rationally × Act Humanly/Rationally
- **Modern AI Focus**: Acting Rationally (e.g., AlphaGo)

## Good Old AI Days
- **Representing Knowledge**:
  - **Logic**: Formal symbolic reasoning using propositions, predicates, and inference rules.
  - **Rules**: If-then production rules encoding expert knowledge.
  - **Semantic Graphs/Nets**: Graph-based representation of concepts and their relationships.

### Example: Predicate Logic and Rule-Based Inference
- **Predicate Logic**:
  - Premises: All people who are graduating are happy; All happy people smile; Someone is graduating.
  - Conclusion: Is someone smiling? (Yes, based on logical inference.)
- **Rule-Based Inference Example**:
  - Rules:
    - R1: IF gas_in_engine AND does_not_start THEN problem(spark_plugs)
    - R2: IF NOT does_not_start AND NOT lights_on THEN problem(battery)
    - R3: IF NOT turns_over AND lights_on THEN problem(starter)
    - R4: IF gas_in_tank AND gas_in_carb THEN gas_in_engine
  - Known: gas_in_tank = true; gas_in_carb = true; does_not_start = true → Hence problem(spark_plugs).

### Semantic Nets
- A graph where nodes represent concepts and edges represent relationships between them.

## Challenges Leading to the First AI Winter
- **Ambiguity**: Translation programs (e.g., Russian to English) failed at semantic disambiguation.
  - Example: "The spirit is willing but the flesh is weak" → "The vodka is good but the meat is rotten"
- **Scalability & Complexity**: Early AI examples were small and narrowly scoped.
- **Limitations of Representations**: Knowledge representation schemes were brittle and unable to handle uncertainty, ambiguity, or common sense.

## Key Periods
- **Boom 1**: GOFAI (General-purpose Formal AI) in the 1960s
- **Winter 1**: 1970s
- **Boom 2**: Expert systems

## Conclusion
- The evolution of AI from early rule-based systems to modern machine learning and deep learning frameworks.
```

This structured summary provides an overview of the key points discussed in the document, including definitions, examples, and challenges faced in the development of AI.