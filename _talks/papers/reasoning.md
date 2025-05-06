---
name: 'Reasoning with Happens-Before Relations about Concurrent Programs in the Theta Framework'
speakers:
  - Csanád Telbisz
  - Levente Bajczi
  - Dániel Szekeres
  - András Vörös
  - István Majzik
room: 'DSN2025'
categories:
  - Short papers
---

The model checking of multi-threaded programs often
involves reasoning about the happens-before relation of
concurrent program instructions. Several algorithms exist
for finding a partial order of instructions that is
consistent with ordering constraints of the assumed memory
model and that violates a safety property; or for proving
that such partial orders do not exist. We present existing
and novel bounded model checking approaches reasoning with
happens-before relations of concurrent programs. These
algorithms are implemented in Theta, a modular model
checking framework. We also give a comparative evaluation
of our Theta implementations and state-of-the-art verifiers.
