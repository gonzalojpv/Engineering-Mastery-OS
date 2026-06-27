# Code Reviews

> *"A code review is not an inspection of code. It is an evaluation of engineering decisions."*

The purpose of a code review is not to find mistakes.

Its purpose is to improve software quality, engineering judgment, maintainability, and shared understanding.

Every review should leave the code—and the engineer—better than before.

---

# Philosophy

Code reviews are collaborative.

They are not audits.

They are not competitions.

They are not opportunities to demonstrate superiority.

A successful review improves:

* Code quality
* Architecture
* Readability
* Reliability
* Maintainability
* Knowledge sharing
* Team consistency

Every review is an opportunity to learn.

---

# Engineering Mindset

Review the solution, not the person.

Assume positive intent.

Ask questions before making assumptions.

Explain reasoning.

Encourage discussion.

Optimize for long-term maintainability.

The goal is continuous improvement.

---

# Code Review Workflow

Every review follows the same process.

```text
Understand Context
        ↓
Understand the Problem
        ↓
Evaluate the Design
        ↓
Review the Implementation
        ↓
Review Testing
        ↓
Review Maintainability
        ↓
Review Performance
        ↓
Review Security
        ↓
Review Documentation
        ↓
Provide Feedback
```

Never begin by commenting on syntax.

Always understand the problem first.

---

# Step 1 — Understand the Context

Before reviewing code, answer:

What problem is being solved?

Why is this change necessary?

What business value does it provide?

Which assumptions exist?

Without context, review quality decreases.

---

# Step 2 — Evaluate the Design

Review architectural decisions before implementation details.

Questions include:

Does this design solve the problem?

Is it unnecessarily complex?

Can responsibilities be simplified?

Does this fit the existing architecture?

Will this scale?

Does it introduce technical debt?

Good architecture matters more than perfect syntax.

---

# Step 3 — Review Readability

Ask:

Can another engineer understand this six months from now?

Are names meaningful?

Are functions focused?

Are responsibilities clear?

Can complexity be reduced?

Readable code is maintainable code.

---

# Step 4 — Review Maintainability

Consider:

Will future engineers understand this?

Is duplication acceptable?

Can future changes be made safely?

Does this introduce unnecessary coupling?

Will testing become harder?

Maintainability should always be a priority.

---

# Step 5 — Review Correctness

Verify:

Business logic

Edge cases

Error handling

Validation

State transitions

Unexpected inputs

Failure scenarios

Correct software handles both expected and unexpected situations.

---

# Step 6 — Review Performance

Not every review requires optimization.

However, consider:

Expensive loops

Database queries

Memory allocation

Network requests

Caching

Concurrency

Only optimize when justified.

Avoid premature optimization.

---

# Step 7 — Review Security

Always verify:

Authentication

Authorization

Input validation

Output encoding

Secrets management

SQL injection

XSS

CSRF

Rate limiting

Logging sensitive data

Security should never be an afterthought.

---

# Step 8 — Review Testing

Ask:

Does this include tests?

Do tests cover important scenarios?

Are edge cases included?

Would these tests catch regressions?

Are tests understandable?

Tests document expected behavior.

---

# Step 9 — Review Documentation

Verify:

README updates

API documentation

Architecture changes

Migration notes

Breaking changes

Deployment instructions

Documentation is part of the implementation.

---

# Review Checklist

Every review should consider:

## Correctness

✓ Does it work?

---

## Simplicity

✓ Is this the simplest solution?

---

## Readability

✓ Can another engineer understand it?

---

## Maintainability

✓ Will future changes be safe?

---

## Scalability

✓ What happens under heavy load?

---

## Performance

✓ Are bottlenecks introduced?

---

## Security

✓ Are vulnerabilities introduced?

---

## Testing

✓ Is behavior verified?

---

## Documentation

✓ Is knowledge preserved?

---

# Feedback Guidelines

Feedback should be:

Specific

Constructive

Actionable

Respectful

Educational

Avoid comments such as:

"This is wrong."

Prefer:

"Could this approach make future changes more difficult?"

Questions encourage discussion.

---

# Comment Categories

Use consistent language.

## Question

Example:

What happens if this service becomes unavailable?

---

## Suggestion

Example:

Consider extracting this logic into a separate service.

---

## Observation

Example:

This duplicates logic already implemented elsewhere.

---

## Risk

Example:

This approach may create race conditions.

---

## Praise

Example:

Good separation of responsibilities.

Clear naming.

Well-designed tests.

Positive feedback is as valuable as corrective feedback.

---

# Architecture Review Questions

Whenever reviewing a feature, ask:

Does this belong here?

Can responsibilities be separated?

Is the abstraction justified?

Will this remain understandable in two years?

How difficult will future modifications be?

Does this align with our architecture?

Architecture reviews should precede implementation reviews.

---

# Engineering Judgment

Every review should evaluate tradeoffs.

Examples:

Simplicity vs Flexibility

Performance vs Readability

Abstraction vs Duplication

Speed vs Maintainability

Consistency vs Innovation

Engineering is choosing between imperfect alternatives.

---

# Learning Through Reviews

Every review should teach something.

Possible learning outcomes:

New language feature.

Better architecture.

Testing strategy.

Performance optimization.

Security improvement.

Documentation improvement.

Knowledge sharing multiplies engineering quality.

---

# Role of Claude

Claude acts as a Staff Engineer during every code review.

Responsibilities include:

Review architecture before syntax.

Challenge assumptions.

Ask difficult questions.

Identify technical debt.

Recommend simpler alternatives.

Highlight scalability concerns.

Identify testing gaps.

Suggest production improvements.

Explain tradeoffs.

Teach engineering principles behind every recommendation.

Claude should avoid rewriting code immediately.

Instead, encourage reasoning and discussion.

---

# Pull Request Reflection

After every significant review, answer:

What did I learn?

Which comments surprised me?

What patterns should I avoid?

What patterns should I repeat?

Did this review change my thinking?

Reflection turns reviews into long-term learning.

---

# Definition of an Excellent Review

An excellent review:

Improves the software.

Improves the engineer.

Improves the team.

Improves future decisions.

A review that only finds syntax issues has limited value.

A review that improves engineering judgment creates lasting impact.

---

# Final Principle

Every line of code represents a technical decision.

Review the decisions—not just the code.

The ultimate goal of every code review is to strengthen engineering judgment, encourage thoughtful discussion, and continuously raise the quality of both the software and the engineers who build it.
