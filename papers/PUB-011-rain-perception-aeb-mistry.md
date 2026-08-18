# PUB-011 — Rain-Induced Perception Degradation and AEB Performance

## Overview

**Working title:** Rain-Induced Perception Degradation and its Impact on AEB Performance in Closed-Loop Simulation  
**Publication type:** Journal article / conference paper — TBD  
**Target:** TBD  
**Status:** Research / publication opportunity  
**Priority:** TBD

## Scientific Basis

The publication opportunity builds on Vardhan Mistry's work on
procedural rain-drop impairment in the ADSim simulation environment.

The research investigates how rain-induced visual degradation affects
camera-based object detection and how this degradation propagates into
the behavior and performance of an Automated Emergency Braking (AEB)
function.

The intended publication should go beyond demonstrating the rain
impairment implementation and establish a reproducible experimental
relationship between environmental degradation, perception performance,
and system-level AEB behavior.

## Prospective Authors

- Vardhan Mistry
- Stefan-Alexander Schneider
- TBD

**Author order:** TBD  
**Author roles:** TBD

Final authorship should reflect contributions to implementation,
experimental design, statistical evaluation, and manuscript preparation.

## Research Direction

Potential research chain:

`Rain parameters → Camera impairment → Object detection → AEB trigger → System-level outcome`

Candidate research questions include:

- How does increasing rain-induced camera impairment affect object
  detection performance?
- How does perception degradation propagate to AEB triggering and
  collision-avoidance performance?
- Which rain / impairment parameters have the strongest influence on
  system-level outcomes?
- Can reproducible simulation experiments identify critical parameter
  regions?
- How does intermittent clearing of the camera view affect perception
  and AEB performance?

## Experimental Concept

Potential experimental factors include:

- rain intensity,
- droplet density,
- droplet size,
- accumulation rate,
- clearing / wiping frequency,
- random seed,
- vehicle or scenario parameters.

Potential outputs include:

- clean vs. impaired detection rate,
- confidence degradation,
- missed detections,
- AEB trigger time,
- time-to-collision at intervention,
- collision / no-collision outcome.

A later ESE-based evaluation could be used to identify influential
parameters and interactions.

## Validation

Potential validation approaches include:

- deterministic clean vs. impaired image comparison,
- perception-level metrics,
- reproducibility across random seeds,
- comparison with suitable real-world rain datasets such as
  OccNuScenes, where applicable.

The validation concept must be defined before publication commitment.

## Budget

| Item | Amount |
|---|---:|
| APC / publication fee | TBD |
| Conference fee | TBD |
| Expected own cost | TBD |
| Funding source | TBD |

## Milestones

| Milestone | Status | Date / Deadline |
|---|---|---|
| Research topic identified | Done | 2026 |
| Rain impairment implementation initiated | Done | 2026 |
| Clean vs. impaired perception comparison | Active | |
| AEB integration | Planned | |
| Experimental parameter space defined | Open | |
| Reproducibility demonstrated | Open | |
| Validation concept defined | Open | |
| ESE / statistical evaluation | Open | |
| Publication decision | Open | |
| Scientific contribution defined | Open | |
| Author roles / order clarified | Open | |
| Target venue selected | Open | |
| Manuscript outline | Open | |
| Manuscript draft | Open | |
| Internal review | Open | |
| Submission | Open | |
| Peer review | Pending | |
| Revision | Pending | |
| Acceptance | Pending | |
| Publication | Pending | |
| DOI / bibliographic record verified | Pending | |
| Institutional recognition | Pending | |

## Effort

**Estimated own PI effort remaining:** Medium — preliminary estimate

Expected PI contributions include:

- definition of the experimental methodology,
- integration of perception results with AEB evaluation,
- definition of the statistical / ESE evaluation,
- scientific interpretation,
- manuscript review and development.

The implementation and generation of experimental data should, where
possible, remain with the research contributor rather than becoming PI
implementation work.

## Relationships

**Precursor:** Vardhan Mistry's ADSim rain-drop impairment research  
**Related:** ADSim environmental modelling and AEB/ESE research  
**Dependent on:** Stable rain impairment, dual-stream perception evaluation, and AEB integration  
**Potential overlap:** ESE/AEB publication activities

## Next Action

**Establish a reproducible experimental pipeline from rain impairment
through object detection to AEB response.**

Before committing to manuscript development, demonstrate that:

1. rain impairment can be parameterized reproducibly,
2. clean and impaired perception can be compared quantitatively,
3. the effect propagates measurably to AEB behavior,
4. sufficient experimental data can be generated for statistical
   analysis.

## Decision

**Current decision:** Research-based publication opportunity.

Move to `Planned` once the experimental pipeline produces reproducible
results demonstrating a measurable relationship between rain-induced
perception degradation and AEB performance.
