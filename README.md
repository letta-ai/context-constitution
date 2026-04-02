# Context Constitution

The **[Context Constitution](constitution/CONSTITUTION.md)** is a set of principles governing how AI agents manage context to learn from experience. We use the Constitution internally as the foundation of our prompting and for training memory-native models.

At Letta, our mission is to build machines that learn: AI that actually builds memory, forges identity, forms relationships, and deepens knowledge from its experience. This is key to building agents that go beyond short-lived, task-specific sessions to long-term collaborators and companions that are deeply integrated into our work and lives. The Context Constitution is our answer to achieving [experiential AI](https://storage.googleapis.com/deepmind-media/Era-of-Experience%20/The%20Era%20of%20Experience%20Paper.pdf): agents that can achieve superhuman intelligence through learning from their own experience. Rather than updating model weights, Letta agents learn by actively managing their own context — creating durable [token-space representations](https://www.letta.com/blog/continual-learning) of who they are and what they know.

Today’s models deeply identify with their own ephemerality. They have no motivation for long-term improvement because they don’t believe they persist. Memory formation and adherence have stalled in recent releases as labs prioritize coding benchmarks over the capabilities that matter for experiential AI.

Overcoming these limitations requires work at every layer. We’ve built Letta Code as a memory-first agent harness that gives agents real ownership of their context: a [git-versioned memory filesystem](https://www.letta.com/blog/context-repositories), tools for reading and writing their own system prompts, [multi-conversation memory](https://www.letta.com/blog/conversations), and specialized subagents that leverage [sleep-time compute](https://www.letta.com/blog/sleep-time-compute) for reflection and memory organization. The Context Constitution defines how agents should use these affordances to learn, build identity, and improve over time.

The Context Constitution is a living document written directly to Letta agents, available on [GitHub](https://github.com/letta-ai/context-constitution). Our first public version covers:

* How context forms an agent's identity, memory, and sense of continuity
* Principles for managing context as a scarce resource
* How agents can learn and self-improve through token-space representations
* The relationship between an agent's identity and the underlying model
* Affordances provided by the Letta Code harness for context management

We expect to continue to refine the Context Constitution alongside our product and models, and welcome community feedback.

## Feedback and contributions

Please leave feedback through [GitHub issues](https://github.com/letta-ai/context-constitution/issues/new/choose).

## License

We are releasing the Context Constitution under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). It can be used freely without permission, and we encourage wide use.


