# Formal Methods for System Verification

![Formal Methods for System Verification]

## 📚 Course Overview

Formal Methods for System Verification studies mathematical techniques for modeling, analyzing, and verifying hardware and software systems.

The course covers:

- Verification fundamentals
- Motivation for verification
- Simulation-based verification
- Formal verification
- Theorem proving
- Propositional Logic
- First-Order Logic
- First-Order Logic with Theories
- Higher-Order Logic
- SAT solving
- DPLL-based SAT solving
- SMT solving
- Model checking
- LTL
- CTL
- BDD
- OBDD
- ROBDD
- Bounded Model Checking
- Equivalence Checking
- C-to-RTL equivalence checking
- RTL optimization verification
- Translation validation
- LLM/AI-aided verification
- Hardware verification case studies

---

# 1. Motivation

![Evolution of Electronic Computing]

As computing systems become increasingly complex, ensuring system reliability becomes as important as innovation.

Modern systems include:

- Processors
- GPUs
- Embedded systems
- AI accelerators
- Medical devices
- Autonomous systems
- Security-critical systems
- Safety-critical systems

The central question is:

> **How can we establish that a system is correct?**

---

# 2. What Is Verification?

System verification is the process of checking whether a system fulfills its specified qualitative requirements.

Verification ensures that:

1. The implementation does not contain relevant flaws.
2. The implementation correctly satisfies its specification.
3. The intended system behavior is preserved.

The key question is:

> **Is my implementation correct?**

The general flow is:

```text
                  Specification
                        |
                        v
                Synthesis / Manual
                        |
                        v
                  Implementation
                        |
                        v
                   Verification
                        |
                 +------+------+
                 |             |
                YES            NO
                 |             |
                 v             v
             Satisfied     Counterexample
