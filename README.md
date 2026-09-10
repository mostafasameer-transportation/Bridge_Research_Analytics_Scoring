# Five-State Bridge Rehabilitation Research & Live Analytics Tool

An interactive research platform for analyzing bridge condition, structural components, bridge characteristics, factor sensitivity, and exploratory rehabilitation prioritization across five U.S. states:

- New York
- California
- Florida
- Pennsylvania
- Texas

This tool is developed as part of Ph.D. dissertation research at the **Florida International University (FIU) Moss School of Construction**.

## Research Context

Bridge rehabilitation and recovery decisions are often made under limited resources. Transportation agencies may manage thousands of bridges while having funding and resources sufficient to address only a limited number of structures.

This research investigates:

> **What factors should be considered when prioritizing bridges for rehabilitation and recovery under limited resources, and how do those factors differ across states?**

The current website provides an interactive research environment for examining:

- Structural bridge condition
- Component-level condition
- Bridge age
- Traffic exposure
- Deck area
- NHS status
- State-specific bridge prioritization practices
- Factor availability
- Factor decision roles
- Bridge population filtering
- Exploratory scoring
- Factor sensitivity
- Live data analysis
- Visualization and ranking behavior

The website is intended to support the development of an evidence-based bridge rehabilitation prioritization framework and, ultimately, a resource-constrained decision model.


# Five-State Study Area

The current research focuses on five states:

| State | Abbreviation | Role |
|---|---|---|
| New York | NY | Core study state |
| California | CA | Core study state |
| Florida | FL | Core study state |
| Pennsylvania | PA | Core study state |
| Texas | TX | Core study state |

The five states were selected to provide variation in bridge inventory, condition, transportation systems, climate/hydraulic exposure, and bridge management/prioritization practices.


# Bridge Dataset

The current version contains **133,554 bridge records** across the five states.

| State | Bridge Records |
|---|---:|
| New York | 17,552 |
| California | 25,763 |
| Florida | 12,592 |
| Pennsylvania | 22,965 |
| Texas | 54,682 |
| **Total** | **133,554** |

The bridge-level records are embedded directly into the web application.

The current website therefore operates as a self-contained research application without requiring a separate database or external server for the embedded dataset.

# Available Bridge Variables

The current supplied datasets contain the following common fields:

- State Name
- Structure Number
- Owner Agency
- Inventory Route NHS Code
- Overall Bridge Condition
- Deck Condition Rating
- Superstructure Condition Rating
- Substructure Condition Rating
- Culvert Condition Rating
- Structural Evaluation/Appraisal
- Inventory Rating
- Year Built
- Average Daily Traffic (AADT)
- Deck Area

These variables are used directly for the current descriptive and exploratory analyses.

---

# Structural Condition Analysis

A major objective of the research is to avoid representing bridge condition only through a single overall condition variable.

The website therefore separates structural components where the data are available.

### Structural components

- Deck
- Superstructure
- Substructure
- Culvert

Component-level information allows the analysis to investigate whether deterioration is concentrated in a particular bridge component.

For example, two bridges may both have an overall condition classification of "Poor" while having substantially different component-level deterioration patterns.

The current analysis therefore preserves the distinction between:

Overall Bridge Condition
        ↓
Deck Condition
Superstructure Condition
Substructure Condition
Culvert Condition
