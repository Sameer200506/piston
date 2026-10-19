# piston (COMSOL piston with reinforcement)

A COMSOL Multiphysics model of a piston with reinforcing structure. Used to
study stress, deformation and thermal behaviour of the piston body and its
reinforcement under operating loads.

## File

- `with reinforcing.mph` — COMSOL model (≈14 MB, committed).

## Requirements

- COMSOL Multiphysics 6.x with the Structural Mechanics and Heat Transfer
  modules (whichever physics the study uses).
- Open the file with **File → Open** and inspect the model tree for geometry,
  materials, loads and boundary conditions before running the study.

## Notes

`.mph` files are binary COMSOL archives; they are not readable as text and
should be opened only in COMSOL. Large COMSOL files are excluded from the other
COMSOL repository (`btms`) because they exceed GitHub's 100 MB per-file limit.
