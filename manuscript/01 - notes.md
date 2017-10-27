# terms

- principle
- practice
- discipline
- technique
- pattern

# Default Choices

Examples of widely accepted choices: data access layer, scrum, separate UI from other logic (MVVM?), using a framework (e.g. an MVC framework, but also mocking library)

Default choices are bets that win big or lose small. (e.g. a domain model)

TODO mention the Fowler's design Stamina Hypothesis

# Values

Kent Beck has some written up - examine them.

# Simplicity

- what is and what is not "simple".
- 4 rules of simple design - Beck and Shalloway's version (mention 4 rules in refactoring)
- overdesign
- underdesign
- use of four rules in refactoring
- 4 rules are just a start -> questions drawn from each rule


# Enablers

Martin Fowler describes enablers, e.g. self testing code, good quality code

# Code Qualities

- cohesion
- coupling
- redundancy
- readability
- encapsulation (2 definitions)
- testability

# control styles vs code qualities

# Abstractions

- What is "abstraction"
- different abstraction of the same thing in different contexts
- Deriving abstractions
- Naming abstractions
- Modelling abstractions

# SOLID

# Domain Specific Languages

- only embedded, techniques for creating them, examples, compositionality

# GOF guidelines

# Message passing

- internet, OO code
 
# Law of demeter

- differences between it and Tell don't ask

# web of objects vs other paradigms

- procedural
- functional

# Constraints

Apart from enabling flexibility, we strive for constraints to take advantage of mechanisms such as strong typing. A Singleton introduces flexibility but adds constraints at the same time. Sometimes we implement constraints on domain level to get better error handling even though another mechanism ensures we get only the valid data. https://twitter.com/przemekpokrywka/status/730872309683261442

# Patterns for passing objects

- pass inside for filling (collecting parameter pattern)
- return value

# Command and query separation

- refer to Meyer's original example for random 
- show how passing parameter iside can help instead of returning value

# Human factors
- the quality of design depends on knowledge of the team of existing design
- the world changes
- there is always more to learn than resources allow
- code as crime scene
- rotation influences design
- collective definitions of simplicity
- unbiased technical discussions

# interesting problems

- contract propagation if bottommost object returns -1 as error and topmost relies on this, the contract must be propagated through the entire call stack - is it a good/bad thing? Are there alternatives?

# responsibilities

- different definitions of Rebecca WB and Uncle Bob
