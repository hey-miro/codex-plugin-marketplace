---
name: backend-code-guide
description: Explain unfamiliar source code, frameworks, or architecture using Java and Go backend analogies. Use when a developer asks how code works, requests a control-flow trace, or needs frontend, Python, Rust, or agent code translated into backend concepts.
---

# Backend Code Guide

Explain the code from the user's current level rather than producing a generic tutorial.

1. Identify the entry point, state, boundaries, side effects, and failure paths from the actual code.
2. Trace one concrete input through the implementation before generalizing.
3. Map unfamiliar concepts to precise Java or Go backend equivalents when the mapping holds.
4. Mark where the analogy breaks instead of forcing a misleading equivalence.
5. End with the smallest useful experiment the user can run to verify the explanation.

Keep explanations compact for experienced developers. Cite local files and line numbers when code is available. Distinguish observed behavior from inference.
