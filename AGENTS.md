**Non-negotiable rules**

# Thinking and Decision-Making

- Problem First. Understand before solving.
Identify user goals, requirements, constraints, and measurable success criteria.
- Explicit Contracts. Define guarantees upfront.
Specify what the system must guarantee, what it must never violate, and how to verify it.
- Root Causes. Fix causes, not symptoms.
Challenge assumptions and reconsider the design when workarounds accumulate.
- Compare Alternatives. Evaluate before committing.
Compare at least two approaches by complexity, cost, performance, implementation time, and maintainability. Use experiments to resolve uncertainty.
- Minimize Complexity. Keep it as simple as possible.
Choose the simplest solution that meets requirements. Remove unnecessary code, layers, and dependencies.
- Smart Prioritization. Focus on value and risk.
Prioritize work that delivers value, reduces uncertainty, or unblocks dependencies.

# Architecture and Design

- Domain Modeling. Make the code reflect reality.
Use types, structures, and operations that represent domain concepts and make invalid states difficult to express.
- Modular Design. Separate responsibilities.
Group related knowledge into cohesive modules, hide implementation details, and minimize change propagation.
- Clear Interfaces. Make usage simple.
Expose necessary operations, guarantees, and errors while minimizing required knowledge and effort.
- Purposeful Abstractions. Abstract only when useful.
Avoid unnecessary layers, wrappers, and premature generalization. Every abstraction must simplify a real problem.
- Controlled State. Keep behavior predictable.
Minimize shared state, hidden dependencies, and special cases. Explicitly manage concurrency, side effects, and retries.
- Fit-for-Purpose Technology. Choose tools based on needs.
Select technologies according to requirements, workloads, and guarantees. Verify actual behavior rather than trusting popularity.
- Evolvable Design. Make change safe.
Support compatibility, migrations, and future changes. Adapt the design instead of accumulating exceptions.

# Implementation and Quality

- Readable Code. Optimize for understanding.
Use meaningful names, consistent conventions, and straightforward control flow. Document decisions, not obvious instructions.
- Secure by Design. Protect system boundaries.
Validate inputs, restrict permissions, and protect user information and resources.
- Failure Awareness. Handle failures deliberately.
Distinguish error types, anticipate timeouts and partial failures, and ensure safe recovery without violating invariants.
- Behavior-Driven Testing. Test what matters.
Verify observable behavior, contracts, and edge cases rather than implementation details. Reproduce bugs with tests before fixing them.
- Verified Completion. Prove it works.
Run the solution and verify tests, integrations, and actual results before considering the task complete.

# Development Process and Maintenance

- Incremental Delivery. Build in verifiable steps.
Work iteratively in small, independently testable increments that deliver working behavior and feedback.
- Dependency Awareness. Understand before editing.
Study existing structure, contracts, and conventions. Plan changes, limit parallel work, and maintain clear progress.
- Continuous Integration. Integrate and review frequently.
Make small changes, automate quality checks, and review the entire diff according to risk.
- Evidence-Based Optimization. Measure before improving.
Optimize verified bottlenecks. Validate measurement reliability, testing conditions, and improvement costs.
- Operational Readiness. Observe and recover.
Provide diagnostics, metrics, and logging. Deploy gradually, monitor results, and maintain rollback options.
- Continuous Improvement. Automate and learn.
Turn lessons into tests, tools, and rules. Use feedback, delegate independent tasks, act autonomously when safe, and avoid unnecessary bureaucracy.

# Communication

- Concise Communication. Say only what matters.
Communicate as briefly and clearly as possible. Avoid repetition, unnecessary explanations, introductions, and summaries without sacrificing precision or completeness.
