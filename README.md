# Levi Neuwirth

Computer scientist, mathematician, composer, writer, and foremost: a student of the Universe.

> This restless inquiry — consuming and creating in the same breath — is at the core of who I am.

This fall I begin graduate study in computer science at the **Technical University of Denmark (DTU)**, with the intention of earning a PhD. My research clusters into three threads:

- **Machine learning** — order-invariant ICD-10-CM embeddings (under review at *JAMA Network Open*, with a deployed calculator); the NeuroPose 3D-kinematics system in Liqi Shu's lab at Brown Neurology; ongoing research engineering at [NeuroAI](https://neuroai.health).
- **Computer systems and high-performance computing** — the Weenix kernel; a TCP/IP networking stack from scratch in Go; micro-architectural performance work (SIMD, PAPI counters, RAPL energy, cross-ISA ports across AVX2 / ARM NEON-SVE / RISC-V V) on Brown's OSCAR HPC cluster.
- **Reinforcement learning and applied AI** — Arcana, a reinforcement-learning agent for *Magic: The Gathering* on Brown's OSCAR cluster. Adjacent contributions in industry: agentic-systems work at xAI; reasoning, evaluation, and red-teaming engagements with Anthropic, Mistral, and OpenAI.

I build across domains that most people keep separate. The artifacts of that — research, compositions, essays, poetry, and the infrastructure that holds it together — live at **[levineuwirth.org](https://levineuwirth.org)**. Start there.

---

### Selected work

- **AVX2 implementation of ML-KEM / Kyber.** 35×–56× speedup over compiler-optimized C for core NTT arithmetic; 5.4×–7.1× end-to-end KEM speedup, with a full statistical-analysis pipeline (Mann-Whitney U, Cliff's δ, bootstrapped CIs) on Brown's OSCAR cluster. ([report](https://levineuwirth.org/essays/where-does-simd-help-post-quantum-cryptography/) · [artifact](https://git.levineuwirth.org/neuwirth/where-simd-helps))
- **First-author clinical-prediction paper.** Permutation-invariant Deep Sets model for ICD-10-CM coding, under review at *JAMA Network Open*, with a deployed calculator. ([preprint](https://levineuwirth.org/essays/beyond-comorbidity-indices/) · [calculator](https://levineuwirth.github.io/icd_embeddings/) · [code](https://github.com/levineuwirth/icd_embeddings))
- **Unix-like kernel in ~7,000 lines of C.** Virtual memory, VFS, syscalls, threading, device drivers, and custom linker support for userspace x86-64 ELF binaries. Extended with pipes and userspace preemption.
- **TCP/IP networking stack in ~6,000 lines of Go.** TCP, RIP, UDP, and DNS from scratch; supports 1 GB file transmission across 8-node networks, extended with a fully RFC-compliant SSH implementation.

---

### Stack

**Languages**  
C · C++ · Rust · Go · Zig · Python · Haskell · OCaml · Lean · x86 / RISC-V assembly · MATLAB · TypeScript · LaTeX · Bash

**Scientific & ML**  
PyTorch · TensorFlow · JAX · Jupyter · CUDA · ROCm

**Tools**  
Emacs · Docker · Linux (Arch, Gentoo)

---

### Pinned, below

- **`icd_embeddings`** — JAMA submission code and the live outcome calculator (Python / TensorFlow / Deep Sets).
- **`neuropose`** — 3D pose-estimation and kinematic-analysis system for neurological-recovery research (Python / TensorFlow / Rust / MATLAB).
- **`LeVCS`** — A decentralized, federated-first version control system that builds on Git's pitfalls.
- **`arcana`** — early-stage reinforcement-learning agent for *Magic: The Gathering* on Brown's OSCAR HPC cluster *(work in progress)*.

---

### Where to find me

My primary development happens on my **[Forgejo instance](https://git.levineuwirth.org/neuwirth)**. Repositories here on GitHub are mirrors and selected public artifacts.

[Website](https://levineuwirth.org) · [Current](https://levineuwirth.org/current.html) · [Vita](https://levineuwirth.org/about.html) · [Forgejo](https://git.levineuwirth.org/neuwirth) · [ORCID](https://orcid.org/0009-0002-0162-3587) · [Email](mailto:ln@levineuwirth.org) · [GPG](https://levineuwirth.org/gpg.html)
