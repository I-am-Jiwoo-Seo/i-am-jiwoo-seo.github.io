---
layout: post
title: A Gentle Dive into Quantum Physics
subtitle: Where reality gets weird (and wonderful)
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [quantum-physics, science, physics]
comments: true
mathjax: true
author: Jiwoo Seo
---

{: .box-success}
Quantum physics is the branch of physics that describes how the universe behaves at the **smallest possible scales**—atoms, electrons, photons, and beyond.  
If classical physics is about apples falling from trees, quantum physics is about apples being *everywhere at once* until you look at them.

This post is a **conceptual introduction**, not a maths-heavy lecture. Weirdness ahead — but the fun kind ✨

---

## What even *is* quantum physics?

Classical physics (Newton, Galileo, etc.) works brilliantly for everyday life.  
But once scientists started studying **atoms**, it completely broke down.

Quantum physics exists because:
- Particles behave like **waves**
- Waves behave like **particles**
- Measurement itself changes reality

In short: the universe does not behave intuitively when things get *very small*.

---

## Wave–particle duality

One of the core ideas is **wave–particle duality**.

Light, for example:
- Acts like a **wave** (interference, diffraction)
- Acts like a **particle** (photons hitting a detector)

Electrons do this too — which is even stranger, because electrons have mass.

{: .box-note}
**Key idea:**  
Particles don’t *choose* to be waves or particles.  
They are described by a **wavefunction** that encodes probabilities.

---

## The wavefunction and probability

In quantum mechanics, the state of a system is described by a wavefunction, usually written as:

\[
\psi(x, t)
\]

The important part is **not** the wavefunction itself, but its square:

\[
|\psi(x,t)|^2
\]

This gives the **probability** of finding a particle at position \(x\).

So quantum physics does **not** tell you:
> “The particle *is* here”

It tells you:
> “The particle has a *70% chance* of being here”

Reality becomes probabilistic, not deterministic.

---

## Superposition: being in multiple states at once

A quantum system can exist in a **superposition** of states.

For example, an electron’s spin can be:
- Spin up
- Spin down
- Or both at the same time 😵‍💫

Mathematically, we write this as:

\[
|\psi\rangle = a|0\rangle + b|1\rangle
\]

Where:
- \(a\) and \(b\) are probability amplitudes
- \(|a|^2 + |b|^2 = 1\)

{: .box-warning}
**Important:**  
Superposition is *not* ignorance.  
The system genuinely exists in multiple states **until measured**.

---

## Measurement and wavefunction collapse

The act of **measurement** forces the system to pick a definite outcome.

Before measurement:
- Multiple possibilities exist simultaneously

After measurement:
- Only **one outcome** remains

This is called **wavefunction collapse**.

Why does measurement cause collapse?  
Nobody knows. And yes — physicists argue about this constantly.

---

## Quantum entanglement

Entanglement occurs when two particles become linked so that:
- Measuring one instantly determines the state of the other
- No matter how far apart they are

Einstein famously called this:
> “Spooky action at a distance”

{: .box-error}
**Misconception:**  
Entanglement does **not** allow faster-than-light communication.  
It only creates correlations, not controllable signals.

---

## Why quantum physics matters

Quantum physics isn’t just abstract theory — it powers modern technology:

| Quantum idea | Real-world application |
|-------------|------------------------|
| Energy quantisation | Lasers |
| Wavefunctions | Electron microscopes |
| Superposition | Quantum computing |
| Tunnelling | Semiconductors |
| Entanglement | Quantum cryptography |

Your phone, laptop, and GPS literally would not work without quantum mechanics.

---

## A tiny code analogy

Here’s a *very loose* analogy using code:

```javascript
// Classical bit
let bit = 0; // or 1

// Quantum bit (conceptual)
let qubit = "0 + 1"; // superposition
