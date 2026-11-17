# FamilyFlow Development Process

## Model and context
Proposed model: Scrum adapted for a solo academic project, subject to the author's final selection and justification. Sapan Khadka prefers weekly goals, has access to a potential user for feedback, identifies recurring bills as uncertain, and reports some confidence with Python tests.

This is not a full Scrum implementation. One student handles prioritization, development, and process review rather than claiming separate people fill the Scrum accountabilities. Weekly planning, a Sprint Goal, a prioritized backlog, usable increments, review, and retrospective provide the working structure.

## Work tracking
- [Prioritized issue backlog](https://github.com/sapan-khadka/familyflow/issues)
- [Repository Projects entry point](https://github.com/sapan-khadka/familyflow/projects)
- [FamilyFlow Development board](https://github.com/users/sapan-khadka/projects/2)
- Required board columns: Backlog, In Progress, Done.
- Issues #1–#8 are linked cards, initially in Backlog. Move cards only as actual work progresses.
- GitHub is used for development planning; the delivered application must operate without internet access.

## Sprint 1: November 17–23, 2026
Length: one week.
Goal: demonstrate persistent offline entry of a starting balance, expected income, and dated bills, and clarify recurring-bill behavior through user feedback.
Selected backlog: #1, #2, #3.
Stretch item: #4, only if the selected items meet the Definition of Done.
Planning: November 17; review and retrospective: November 23.
Daily individual check: record completed work, the next action, and blockers; this is not represented as a full-team Daily Scrum.

## Recurring-bill questions for review
- What happens to a bill due on the 31st in a shorter month?
- Does changing a series affect future occurrences only?
- Can each occurrence have a different amount?
- How are paid occurrences distinguished from future obligations?
No user interview results are claimed yet. Record actual feedback in issue #4 and revise acceptance criteria accordingly.

## Definition of Done
A story meets its acceptance criteria, persists data locally where applicable, works without runtime network dependencies, passes relevant automated tests, and has reviewed, committed changes with limitations documented. Use synthetic financial examples for testing and feedback.

## Weekly cycle
Plan and select stories → implement and test → demonstrate the increment → record user feedback → review process and reprioritize the next sprint.
Unfinished stories return to the backlog for reconsideration; they are not automatically treated as completed.

## AI assistance
AI assisted with drafting this process document, the user stories, acceptance criteria, and sprint proposal. The author must review these proposals, make the final process decision, and provide the human-led analysis required by Assignment 2. Report and disclose any additional AI assistance accurately.
