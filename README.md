# CSID Explained

CSID, or Component Status ID is the unique identifier for i-Ready lessons.

## Full Example CSID:
`CSID: DI.ELA.COM.8.1042.10_006a09c1-ef55-488c-8634-7543bec2b644_M_ela`

### Breakdown:

- **Lesson ID:** DI.ELA.COM.8.2003
  - *Explanation:* This component identifies the specific lesson and includes information about the subject (ELA), grade level (8), and a unique lesson identifier (2003).

- **Lesson Part:**
  - *Codes:*
    - `10` indicates an instructional segment.
    - `20` signifies a quiz or assessment.
  - *Example:* In the given CSID, `10` suggests that this is an instructional part of the lesson.

- **Activity ID:** 006a09c1-ef55-488c-8634-7543bec2b644
  - *Explanation:* unique lesson identifier.

- **Unknown:**
  - `_M_`
    - *Explanation:* This seems to be in every CSID, but the meaning is unknown.

- **Subject:** ELA
  - *Explanation:* subject for the lesson.

# Building a CSID
  - `{Lesson ID}.{Lesson Part}_{Activity ID}_M_{Subject}`
