---
name: Kexin Pei
title: Kexin Pei
affiliation: University of Chicago
web: https://sites.google.com/site/kexinpeisite/
bio: |
    Kexin Pei is a Neubauer Family Assistant Professor at the Department of Computer Science, The University of Chicago. He received my PhD at Department of Computer Science, Columbia University. He is broadly interested in Security, Software Engineering, and Machine Learning, with a focus on automated code reasoning to improve the security and reliability of software systems. He gets most excited about developing intelligent systems that understand code semantics and can precisely reason about program behaviors, allowing them to reliably and efficiently analyze, detect, and fix software bugs and vulnerabilities.
description: Synthesizing Fine-grained State Checks for Curriculum Fuzzing
abstract: |
    Fuzzing enables many security applications, such as detecting vulnerabilities, confirming vulnerabilities by generating exploits, debugging system crashes and performance issues, and validating patches. While fuzzing essentially features a brute-force search, most research focuses on code reasoning to develop additional feedback that makes the search more efficient. For example, a typical feedback is code coverage, which serves as a proxy to measure progress towards reaching potential bugs, while being very easy to analyze and collect. However, such guidance is sometimes too sparse or indirect to reliably measure progress, especially when a long chain of implicit preconditions guards the specific bug. In contrast, more sophisticated feedbacks are often tailored for specific bug types and thus might not generalize to diverse bug types and programs.

    <p>In this talk, I'll introduce our recent effort in building a code agent to reason about semantically meaningful progress-capturing predicates as fine-grained, curriculum feedback to improve fuzzing efficiency. These predicates, inserted as source-level instrumentation into the program, provide semantically meaningful checkpoints that both prune unpromising executions and reward incremental progress. By shifting the LLM’s role from end-to-end input-level generation to local predicate synthesis, we reduce the long-range reasoning burden on the model, while enabling verifiable predicate synthesis via symbolic execution. We show that our system, Locus, substantially improves the efficiency of eight state-of-the-art fuzzers, achieving up to 41.6× speedup in reaching target sites and discovering new previously unknown bugs. We also demonstrate that the same philosophy can facilitate the synthesis of performance-stressing predicates, enabling efficient performance testing.</p>
img: pei.jpg
affil_img: uchicago.png
keynote: false
---