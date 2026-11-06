# DataMan Product Backlog

> Replace every bracketed prompt with your own work. Delete the prompts, this note, and any unused story blocks before you submit.
> Save this file as `docs/product-backlog.md`. Use that exact folder, file name, and lowercase spelling.

## Sources

This backlog uses these files from my repository:

- `docs/requirements.md`
- `docs/decisions/m3-backlog-triage-record.md`
- `docs/decisions/m3-product-owner-decision-record.md`

[If you revised `docs/requirements.md` after Module 2, state that here in one sentence.]

## Priority Order

List every story ID from highest priority to lowest. The story blocks below must appear in this same order.

1. [US-_01_]
2. [US-_02_]
3. [US-_03_]
4. [US-_04_]

## Stories

### US-01 — [ Monitoring ]

**Requirement ID:** [FR-01 or NFR-__ from `docs/requirements.md`. If the story traces to more than one requirement, list each ID.]

**User Story:** As a [ leaner ], I want [ DataMan to track my activities and progress] so that [I can see if I am making progress. ]

**Acceptance Criteria:**

- Given [A learner completes a activity], when [learner or other user views progress] then [the activity is displayed as completed].

- [Write one line for each condition. Each line must state a result that another person can see and check.]
- Given [A learner completes a activity]
- When [learner or other user views progress]
- Then [the activity is displayed as completed]


**Relative Effort:** [S / M / L] — [ Effort - M. the difficulty lies in tracking, storing and display, It is more complex then basic interface updates but less complex then analytic features.]

**Dependency / Constraint:** [None]

**Priority:** [Rank 1]

**Readiness:** [Move Forward]

**Priority Rationale:** [ The story delivers alot of value by providing visibilty into progress. It has low implementation effort and no dependencies, supports possible other features that may rely on progress tracking.]

---

### US-02 — [Browser Interface]

**Requirement ID:** [FR-02 / NFR-__]

**User Story:** As a [learner], I want [DataMan to be easy to navigate in a browers window.] so that [I can navigate with out trouble].

**Acceptance Criteria:**

- Given [a learner opens DataMan in a supported browser], when [the application loads], then [all navigation is visible and functions].

**Relative Effort:** [S / M / L] — [Effort - S. This story is primarily interface design and browser usuability, less complex then other stories that require storing or synchronizing]

**Dependency / Constraint:** [None]

**Priority:** [rank 2]

**Readiness:** [Move Forward]

**Priority Rationale:** [Ease of use is important for adoption and satisfaction, doing so provides a significant value, Us-01 is more foundational so I rank this story slightly lower.]

---

### US-03 — [ Auto-Save ]

**Requirement ID:** [ FR-03 ]

**User Story:** As a [ learner ], I want [DataMan to automatically save progress] so that [I can pick up where i left off. ]

**Acceptance Criteria:**

- Given [a learner is working on a activity], when [progress is made] then [the system will automatically save the learners progress].
- Given [A learner is working on a activity]
- When [Progress is made]
- Then [The system will automatically save learner progress]


**Relative Effort:** [S / M / L] — [ Effort - L -- This story is more complex when tracking and interfacing storyies, It requires automatic data persistence, retreaval and synchronization across all sessions and devices.]

**Dependency / Constraint:** [Progress tracking and data storage must exist before data can be saved or restored.]

**Priority:** [Rank 3]

**Readiness:** [Move Forward]

**Priority Rationale:** [This story provides alot of value by preventing lost work and supports cross-devices. However it depends on other features, making it a lower priority.]

---

### US-04 — [ Consistency on devices ]

**Requirement ID:** [ FR-04 ]

**User Story:** As a [ learner ], I want [DataMan to provide a consistent experience across all devices] so that [I can use the system effeciently no matter what I am using. ]

**Acceptance Criteria:**

- Given [a learner accesses DataMan on different devices], when [the application loads] then [the same core features are available].
- Given [a learner accesses DataMan on different devices]
- When [the application loads]
- Then [the same core features are avaiable.]


**Relative Effort:** [S / M / L] — [ Effort - L -- This story requires testing and support on multiple devices and screens, making extremely complex.]

**Dependency / Constraint:** [depends on FR-01 and FR-03]

**Priority:** [Rank 4]

**Readiness:** [Move Forward]

**Priority Rationale:** [It is important for usability and accessibility, but relies on core functions being available first. this is why it is a lower priority.]

---

## Open Questions Carried Forward

List each open question or assumption from `docs/requirements.md` that affects this backlog. Do not turn an unresolved question into a confirmed story.

- **[Q-01]:** [The layout for the reporting dashboard still needs to be clarified with stakeholders. reporting and display progress may require refinement.]
- **[Q-02]:** [The method for storing learner progress has not been determined. Us-03 depends on this dicision. method affects how progress is saved and restored.]

## Revisions After Triage and Release Planning

State what changed in this backlog because of your triage record and your Product Owner decision record.
- [No changes were made, the original priorites, dependencie. and all other estimates still align with stakeholder needs and goals.]


## Before You Submit

- [ ] The file path is exactly `docs/product-backlog.md`.
- [ ] All bracketed prompts and unused story blocks are deleted.
- [ ] Every story has all eight required fields: Story ID, Requirement ID, User Story, Acceptance Criteria, Relative Effort, Dependency / Constraint, Priority, Priority Rationale.
- [ ] Every Requirement ID exists in `docs/requirements.md`.
- [ ] Each acceptance criterion states a result another person can observe and check.
- [ ] The story blocks follow the Priority Order list.
- [ ] Large or uncertain stories are marked Refine or Defer, not hidden as Move Forward.
- [ ] No story or criterion names a framework, database, or screen layout, unless a requirement makes it a constraint.
- [ ] The file renders correctly on GitHub.
- [ ] The change is committed with a message that describes it.
