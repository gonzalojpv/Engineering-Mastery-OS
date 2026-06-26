# Knowledge Base

> *"Knowledge is not what I read. Knowledge is what I can understand, connect, apply, and explain."*

The purpose of this document is to transform scattered information into organized engineering knowledge.

This is not a notebook.

This is a continuously evolving engineering knowledge system.

Every concept added to this repository should become easier to find, understand, connect, and apply over time.

---

# Knowledge Philosophy

Information is everywhere.

Engineering knowledge is not.

Reading an article does not create knowledge.

Watching a conference does not create knowledge.

Even finishing a book does not create knowledge.

Knowledge is created through:

* Understanding
* Reflection
* Practice
* Documentation
* Repetition
* Application

Only then does information become experience.

---

# Knowledge Sources

Knowledge can originate from many places.

Examples include:

* Official Documentation
* Books
* RFCs
* Technical Papers
* Engineering Blogs
* Medium Articles
* Dev.to
* Conference Talks
* GitHub Discussions
* Open Source Projects
* Code Reviews
* Production Incidents
* Personal Experience
* AI Conversations

All knowledge sources should be critically evaluated before being accepted.

---

# Knowledge Capture Workflow

Every new concept follows the same workflow.

```text
Read
    ↓
Understand
    ↓
Question
    ↓
Compare
    ↓
Experiment
    ↓
Document
    ↓
Connect
    ↓
Apply
```

Skipping any step weakens long-term understanding.

---

# Knowledge Entry Template

Every important topic should be documented using the following structure.

---

## Topic

Example:

PostgreSQL Indexes

---

## Summary

A concise explanation of the concept.

Avoid copying definitions.

Use your own words whenever possible.

---

## Why Does It Exist?

Describe the problem the technology or concept was created to solve.

Understanding motivation is more valuable than memorizing implementation.

---

## How Does It Work?

Describe the internal mechanism.

Whenever possible:

* diagrams
* analogies
* mental models
* production examples

---

## Key Concepts

List the most important ideas.

Example:

* B-Tree
* Selectivity
* Sequential Scan
* Bitmap Scan

---

## Tradeoffs

Every engineering decision introduces tradeoffs.

Examples:

Advantages

Disadvantages

Operational complexity

Performance implications

Maintenance costs

---

## Common Mistakes

Examples:

Misusing indexes.

Premature optimization.

Incorrect assumptions.

Ignoring edge cases.

---

## Real Production Usage

How is this concept commonly used in production systems?

Examples:

Large applications.

Microservices.

Distributed systems.

Cloud infrastructure.

---

## Related Topics

Connect knowledge.

Example:

Indexes

↓

Query Planner

↓

Transactions

↓

MVCC

↓

Locks

↓

Replication

Knowledge should form a network rather than isolated pages.

---

## Practical Examples

Include:

* SQL examples
* Code snippets
* Architecture diagrams
* Benchmarks
* Performance comparisons

Whenever possible, use real-world scenarios.

---

## Questions

Capture unanswered questions.

Questions represent future learning opportunities.

Examples:

How does PostgreSQL choose Bitmap Scan?

How does index selectivity change over time?

How does VACUUM affect indexes?

---

## Action Items

Examples:

Read PostgreSQL documentation.

Benchmark different indexes.

Create a prototype.

Watch conference talk.

Read source code.

Knowledge should produce action.

---

## Personal Notes

Document personal observations.

Examples:

"I misunderstood this concept."

"This changed my opinion."

"This explains a production issue I previously encountered."

Reflection strengthens learning.

---

# Reading External Content

When reading a Medium article, blog post, documentation page, or conference summary, do not simply summarize it.

Instead, analyze it.

For every article answer:

## What problem does it discuss?

## What assumptions does the author make?

## Is the content opinion or evidence?

## Does it align with official documentation?

## Which tradeoffs are discussed?

## What is missing?

## How could I apply this?

## Which new questions does it create?

Critical thinking is required.

---

# Connecting Knowledge

Knowledge should never exist in isolation.

Every entry should connect to previous concepts.

Examples:

Redis

↓

Caching

↓

Distributed Systems

↓

CAP Theorem

↓

Consistency

↓

Database Design

↓

Performance

The richer the network becomes, the stronger long-term understanding becomes.

---

# Engineering Insights

Some ideas deserve their own section.

Capture observations such as:

"Simple architecture scales better than complex architecture."

"Most performance issues originate from poor data access."

"Premature abstraction creates unnecessary maintenance."

Engineering insights often become future principles.

---

# Decision Log

Whenever a technical opinion changes, document it.

Template:

## Previous Belief

---

## New Understanding

---

## Why My Thinking Changed

---

## Supporting Evidence

Books

Articles

Benchmarks

Production experience

---

## Future Guideline

Documenting changes in thinking is evidence of engineering growth.

---

# Knowledge Validation

A topic is not considered mastered until I can:

Explain it clearly.

Apply it in a project.

Compare alternatives.

Discuss tradeoffs.

Teach another engineer.

Recognize common mistakes.

Identify production use cases.

If I cannot do these things, further study is required.

---

# Monthly Knowledge Review

At least once every month:

Review previous notes.

Remove outdated information.

Improve explanations.

Connect new topics.

Expand examples.

Correct misconceptions.

Knowledge should improve continuously.

---

# Role of Claude

When I share:

* a Medium article
* an engineering blog
* official documentation
* a YouTube conference
* a GitHub discussion
* a research paper
* book excerpts

Claude should not simply summarize it.

Claude should:

1. Extract key concepts.
2. Identify assumptions.
3. Compare with existing knowledge.
4. Highlight tradeoffs.
5. Point out missing information.
6. Suggest official references.
7. Recommend practical exercises.
8. Connect the topic with previous knowledge.
9. Update the knowledge network conceptually.
10. Challenge my understanding with questions.

The objective is not to consume more information.

The objective is to develop deeper engineering judgment.

---

# Final Principle

The value of this Knowledge Base is not measured by the number of notes it contains.

Its value is measured by how often it helps me make better engineering decisions.

Every page should contribute to building a more connected, practical, and durable understanding of software engineering.
