# Evolution of Allostery Without Shape Shifting: Internal Dynamics Drives Functional Diversification of a Transcriptional Repressor Superfamily

This repository contains the molecular dynamics (MD) trajectories, analysis scripts, and supporting files associated with the study:

> **Evolution of allostery without shape shifting: Internal dynamics drives functional diversification of a transcriptional repressor superfamily**

## Overview

Allosteric regulation is commonly associated with structural rearrangements linking effector-binding and functional sites. However, increasing evidence suggests that changes in protein dynamics can also mediate allosteric regulation in the absence of large conformational transitions.

In this study, we investigated the molecular mechanisms underlying allosteric regulation in members of a transcriptional repressor superfamily that display distinct functional responses despite maintaining highly similar three-dimensional structures. Using extensive accelerated molecular dynamics (aMD) simulations, we characterized how redox-dependent changes in conformational dynamics modulate DNA binding and allosteric communication.

The repository contains the simulation trajectories and analysis workflows used to characterize the dynamical landscapes of the different allosteric states.

---

## Simulated Systems

Four molecular systems were investigated:

| System | DNA-bound | Redox State |
|----------|----------|----------|
| Reduced | No | Reduced |
| Tetrasulfide | No | Oxidized (tetrasulfide) |
| Reduced DNA-bound | Yes | Reduced |
| Tetrasulfide DNA-bound | Yes | Oxidized (tetrasulfide) |

---

## Simulation Protocol

All systems were simulated using accelerated molecular dynamics (aMD).

### Replicas

For each molecular system:

- 5 independent aMD replicas were performed
- Replicas were initiated from the same experimental structure with independent velocity assignments
- All trajectories were analyzed both individually and as pooled ensembles

Total simulations deposited in this repository:

| System | Number of replicas |
|----------|----------|
| Reduced | 5 |
| Tetrasulfide | 5 |
| Reduced DNA-bound | 5 |
| Tetrasulfide DNA-bound | 5 |

**Total trajectories:** 20 independent aMD simulations.

---

## Repository Structure

```text
.
├── systems/
│   ├── reduced/
│   ├── tetrasulfide/
│   ├── reduced_DNA/
│   └── tetrasulfide_DNA/
│
├── trajectories/
│   ├── replica_1/
│   ├── replica_2/
│   ├── replica_3/
│   ├── replica_4/
│   └── replica_5/
│
│
└── README.md
```
---

## Key Biological Question

This work addresses how evolutionary diversification of allosteric regulation can arise through modifications in internal protein dynamics while preserving the overall structural architecture of the protein family.

The simulations reveal that changes in conformational fluctuations and dynamic couplings can reshape functional responses without requiring major conformational transitions, supporting a dynamics-driven mechanism of allosteric evolution.

---

## Citation

If you use these data, please cite:

```text
Antelo GT, Rondón JJ, Villarruel Dujovne M, Pis Diez CM,
Canciani PG, Sastre S, Zeida A, Radi R, Wu H,
Gonzalez-Gutierrez G, Giedroc DP, Capdevila DA.

Evolution of allostery without shape shifting:
Internal dynamics drives functional diversification of a transcriptional repressor superfamily.
```

---

## Correspondence

**Daiana A. Capdevila**  
Fundación Instituto Leloir / IIBBA-CONICET  
Buenos Aires, Argentina

**Ari Zeida**  
Universidad de la República / CEINBIO  
Montevideo, Uruguay

For questions regarding the simulations, trajectories, or analyses, please contact the corresponding authors.
