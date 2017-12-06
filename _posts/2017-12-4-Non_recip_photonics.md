---
layout: post
title: Review Non-reciprocal photonics based on time modulation
---
Brief notes on a Nature Photonics review article, "Non-reciprocal photonics based on time modulation" by Sounas and Alu.

### Introduction
* Definition: In optics, reciprocity means wave transmission between two points in space is the same in either propagation direction. Usually, we require that signal transmission (not necessarily power transmission) is the same in each direction.
* Applications: Optical devices such as isolators (allowing signals out of a source but no reflections back into it) and circulators (a three port system allowing signals to go from 1 to 2, 2 to 3, 1 to 3 but not in the other direction). Circulators are useful in QC.

### Implementation problems and solutions
* Usually require magnetic materials: big, expensive, hard to integrate
* Magneto-optical devices have large losses in optical regime
* Impractical to apply magnetic techniques into photonic devices on the nanoscale
* Rather than magnetic devices instead try: 1) non-linear materials, 2) biasing with quantities to break TR symmetry, 3) break time-invariance.

### Methods
* Travelling wave modulation: use linear momentum to break TR symmetry. Hard in optics as we don't want moving parts. Instead make synthetic linear momentum with modulated electric permittivity over waveguide.
* Synthetic angular momentum: The traditional magnetic materials split quantum states with opposite angular momentum. Achieve similar effect by applying mechanical spin to cavity. Again, can achieve synthetic angular momentum with spatiotemporal modulation of permittivity.
* Direct photonic transitions: Previous two effects change frequency and momentum of signals. Instead consider effects that change frequency only. These don't break reciprocity alone but can be combined with other transitions. This results in effective gauge field, like a magnetic vector potential.
* Optomechanical effects: usually moving parts are impractical due to the speed of light meaning parts would have to move very quickly to have an effect on propagation. However, can be applied with strong optomechanical coupling in high-Q resonators.

### Relation to topological devices
* Recall, electronic TIs require breaking of TR symmetry to open a topologically non-trivial bandgap. Usually done by applying static magnetic field. This results in electrons accumulating a non-trivial phase as they propagate through the field.
* To obtain a similar phase for photons, we locally control modulation phase to realise effective gauge potential. By changing properties of the modulation phases, we can design an effective magnetic field. Photons are forced to move in circular trajectories.
* Can also realise gauge field through coupling between optical and mechanical resonances in opto-mechanical resonator system.
* Another method is to build non-reciprocity into the lattice elements themselves. Now the TR symmetry is broken locally and any phase difference between nodes isn't important. Might be easier to implement.

### Future avenues and questions
* How to introduce reciprocity to a plasmonic system?

#### References:
[Non-reciprocal photonics based on time modulation](https://doi.org/10.1038/s41566-017-0051-x)
