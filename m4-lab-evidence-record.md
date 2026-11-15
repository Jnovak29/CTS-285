# M4 Lab Evidence Record

## Answer Flow Lab
**Initial design decision tested:** Attempt/state representation

**Scenario that exposed the issue:** Wrong twice, then reveal

### Consequence Observed
During the Answer Flow test, I made my configurations and deployed it, all checks passed after multiple attempts. The consequence is a working configuration for Answer Flow Lab.

### Revision Made
No revision was made. configuration design worked as expected during test.

### What Changed After Revision
No revision was made. configuration design worked as expected.

---

## Memory Bank & Curator Retrieval Lab
**Initial design decision tested:** Attempt/session/result storage

**Scenario that exposed the issue:** Learner session closes

### Consequence Observed
I saw that practice sets and problems are connected through linking records rather than being stored directly together.

### Revision Made
Failure showed that my original design did not correctly represent the relationship between practice sets and problems. After changing the model to use linking records, the query succeeded and the data could be retrieved correctly.

### What Changed After Revision
connected through linking records instead allowed the query to correctly pull the related problems and the behavior worked as expected.

---

## Cross-Lab Finding
These systems made the actual behavior of the flow visible. The requirements described how the process was supposed to work, but testing and querying the model showed whether it truly worked and exposed problems that could not be seen from the requirements alone.

## Revised / New Design Question
Will the current relationships and dependencies support future requirements without causing issues requiring a redesign.
