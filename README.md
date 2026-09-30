# Levi Neuwirth

[**Work**](https://levineuwirth.org/work.html) · [CV](https://levineuwirth.org/cv.pdf) · [Website](https://levineuwirth.org) · [Email](mailto:ln@levineuwirth.org) · [GPG](https://levineuwirth.org/gpg.html) · [ORCID](https://orcid.org/0009-0002-0162-3587)

I work on technical AI assurance, establishing verifiable claims about what a model
actually did, when the operator, the evaluator, or the model itself may not be trusted.
This spans cryptography, systems, evaluations, and mathematics, precisely the shape of my background.
I'm a MARS V fellow with the [Cambridge AI Safety Hub](https://caish.org/mars), mentored by James Petrie (FLI), and a
graduate student in computer science and engineering at DTU; previously CS and mathematics at Brown.

**I am open to full-time research and research-engineering positions worldwide.**

## Selected work

**Verifiable LLM inference** (MARS V, ongoing) — zero-knowledge proofs for cryptographic
verification of claims about LLM training, inference, and deployment. My contributions are
merged upstream into [JamesPetrie/VerInf](https://github.com/JamesPetrie/VerInf): a dry-run
profiler with a manifest contract, cost model, execution DAG, and partition scorecard, plus
cost-model corrections matching the paper's analysis
([merged PRs](https://github.com/JamesPetrie/VerInf/pulls?q=is%3Apr+author%3Alevineuwirth)).
Currently porting the verifier from single-chip to multi-GPU and working on mathematical
techniques for further optimization. Technical write-up expected Q4 2026, for review and publication.

**Frontier-model evaluation and red-teaming** — reasoning evaluation, red-teaming,
RL environments, and evaluation research under contract. What I can discuss publicly is limited.

**[proof-broker](https://github.com/levineuwirth/proof-broker)** — a certificate boundary for
untrusted proof search. Lean 4 and Rocq goals go through a shared IR to SMT solvers, saturation
provers, and language models; a result counts only if its certificate checks and the home kernel
accepts the proof. [R4](https://github.com/levineuwirth/proof-broker/releases/tag/r4) closed 19/19
targeted obligations in an unmodified VerInf file.
[R6](https://github.com/levineuwirth/proof-broker/releases/tag/r6) put a live model behind the
boundary under an audited protocol: all 80 feasible certificates verified, yet proofs covered 6 of
15 obligations. Reconstruction, not proposal, was the constraint.
([Write-up](https://levineuwirth.org/essays/proof-broker/))

**[icd_embeddings](https://github.com/levineuwirth/icd_embeddings)** — order-invariant
ICD-10-CM embeddings for 30-day readmission and post-discharge mortality, trained on the
Nationwide Readmissions Database. Our manuscript is under review at *JAMIA*.

## Also

Systems and performance: [pmacs](https://github.com/levineuwirth/pmacs) (Rust-cored,
Lua-scripted editor), [kyber-simd-profiling](https://github.com/levineuwirth/kyber-simd-profiling)
(SIMD post-quantum cryptography, cross-ISA), [LeVCS](https://github.com/levineuwirth/LeVCS)
(federated version control with signed authority chains), the Weenix kernel, and a TCP/IP
stack written from scratch.
Mathematics: two graph-theory preprints, on
[tree-ball geometry](https://levineuwirth.org/essays/branch-based-local-capture-in-tree-balls/)
and [growing-radius domination](https://levineuwirth.org/essays/near-critical-growing-radius-domination.html).
Research engineering: [neuropose](https://github.com/levineuwirth/neuropose), 3D kinematics
in Liqi Shu's lab at Brown Neurology.

## Primary Tools

Rust, Python, C/C++, OCaml, Haskell, Go. Cryptography, distributed systems and HPC, formal
methods, ML evaluation.

I have worked with many other tools in the past to various extents, and the above list is certainly
not exhaustive.

---

Most of my development is being moved to my [Forgejo](https://git.levineuwirth.org/neuwirth)
instance, mirrored here. [Current](https://levineuwirth.org/current.html) is what
I'm actually working on this month, while [Vita](https://levineuwirth.org/about.html) is the
most formal record.
