# Loment
- **Name** - Loment
- **Description** - Loment is a systems programming language that compiles directly to native x86-64.
- **Creator** - Fujo ([FujoJTOP](https://github.com/FujoJTOP))
- **Release Date** - 0.1.4.5 QuickFix, October 2026
- **Links** - [GitHub](https://github.com/FujoJTOP/loment), [Website](https://fujojtop.github.io/loment-site/), [Manual](https://github.com/FujoJTOP/loment/blob/main/docs/manual/index.md), [Wiki](https://loment.fandom.com/)
- **Applications**
  * Bare-metal programs: an artifact with no runtime, no libc and no undefined symbols
  * Operating-system and embedded work on x86-64
  * Programs that need to state their own resource policy (memory reclamation, whether a runtime
    is allowed, whether the artifact may reach outside itself)
  * Compilers and language tooling — Loment's own compiler driver is written in Loment

## Package Managers
* [lompi](https://github.com/FujoJTOP/lompi) — the package manager for Loment, written in Loment

## Tutorials
* [Quick start](https://github.com/FujoJTOP/loment/blob/main/QUICKSTART.md)
* [The language guide](https://github.com/FujoJTOP/loment/blob/main/.claude/skills/loment/SKILL.md) — self-contained; the same file ships inside the package as `loment skill --print`
* [Examples](https://github.com/FujoJTOP/loment/tree/main/loment/examples)
* [The manual](https://github.com/FujoJTOP/loment/blob/main/docs/manual/index.md)
