# DataMan Requirements Register

## Project Context
[The modernization goal of Dataman is to update and transform it from a old hand held device into a browser based fun learning application
that feels simple, reliable and user freindly. Its primary users are you learners who are learning math, along with parents and teachers who would like to
be able to monitor progress. The project is trying to solve the issues of outdated hardware along with limited accessiblity and the loss progress by creating it into a browser
based application that will automatically save progress and works on all devices.]

## Evidence Notes

- **E-01 — Source:** [Elicitation]  
  **Evidence:** [Parents and teachers need to be able to track learner activity.]

- **E-02 — Source:** [Elicitation]  
  **Evidence:** [Modernizing means a reliable browser based app that is easy to understand with no manual.]

- **E-03 — Source:** [Elicitation]  
  **Evidence:** [Teachers say students often pause and/or switch devices often so app needs to perserve the practice when interupted]

- **E-04 — Source:** [Elicitation]  
  **Evidence:** [The application needs to support multiple devices.]


## Functional Requirements

### FR-01
**Requirement:** The system must [Track and display what the learer practices and whether progress is made].  
**Source/Rationale:** [Supported by elictiation evidence - adults need visibility into activities.]

### FR-02
**Requirement:** The system must [be reliable in a web browser and easy to understand.].  
**Source/Rationale:** [elicitation/stakeholder - definition of "Modern]

### FR-03
**Requirement:** The system must [The system must auto save learner practice state and restore it when needed].  
**Source/Rationale:** [elicitation - teacher feedback that students practice and switch devices]

### FR-04
**Requirement:** The system must [system must be consistent across all devices used.].  
**Source/Rationale:** [elicitation - supported by context.]

## Non-Functional Requirements

### NFR-01
**Requirement:** The system must [load within 3 seconds on standard devices used].  
**Source/Rationale:** [Supported by elicitation - stakeholders words "modern and reliable"]

### NFR-02
**Requirement:** The system must [save automatically every 10 ish seconds and beable to restore with zero data loss].  
**Source/Rationale:** [Supported by elicitation - teachers reporting students switch devices and pause often.]

### NFR-03
**Requirement:** The system must [have no more then a 5% variation in layout or functionality across devices].  
**Source/Rationale:** [supported by elicitation - evidence in multiple devices needing a uniform experience].

## Open Questions / Assumptions

- **Q-01:** [layout expected for the reporting dashboard still need to be clarified with stakeholders.]
- **Q-02:** [The preferred method for storing learner progress.]

## Final Quality Check

Before submitting, confirm that each requirement is:

- [ ] Clear enough for another team member to interpret consistently.
- [ ] Supported by evidence, a stakeholder need, or a confirmed project constraint.
- [ ] Testable or verifiable later.
- [ ] Solution-neutral enough for this stage of the project.
- [ ] Focused on one main capability or quality.
- [ ] Classified correctly as functional or non-functional.

Also confirm:

- [ ] At least four functional requirements are included.
- [ ] At least three non-functional requirements are included.
- [ ] Every confirmed requirement has a source/rationale.
- [ ] Open questions and assumptions are separated from confirmed requirements.
- [ ] The simulation decision record is saved at `docs/decisions/m2-elicitation-decision-record.md`.
- [ ] This file is saved as `docs/requirements.md`, committed, and synced to GitHub.
