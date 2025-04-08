<!---
{
  "depends_on": [],
  "author": "Stephan Bökelmann",
  "first_used": "2025-04-08",
  "keywords": ["scrum", "DoD", "DoR", "Story"]
}
--->

# Definition of Done vs. Definition of Ready

## Introduction
In agile product development, two key quality gates help ensure a smooth transition from idea to implementation and release: the **Definition of Ready (DoR)** and the **Definition of Done (DoD)**. Understanding their purpose, content, and consequences is critical for effective backlog management and delivery.

The **Definition of Ready** outlines what needs to be true before a User Story can be pulled into a sprint. For example, a ready User Story might:
- Have a clear and concise description
- Include acceptance criteria
- Be estimated
- Have no unresolved dependencies

Meanwhile, the **Definition of Done** ensures that the implemented work meets a team’s quality standards. A done Story might:
- Be fully implemented and pass all unit and integration tests
- Be reviewed and merged to the main branch
- Have updated documentation
- Be deployed to a staging environment

Together, these definitions act as guide rails for quality and alignment, from planning to delivery.

In this exercise, you will learn how to formulate meaningful DoR and DoD criteria, evaluate their effectiveness, and apply them to real-world User Stories. help ensure a smooth transition from idea to implementation and release: the **Definition of Ready (DoR)** and the **Definition of Done (DoD)**. Understanding their purpose, content, and consequences is critical for effective backlog management and delivery.

In this exercise, you will learn how to formulate meaningful DoR and DoD criteria, evaluate their effectiveness, and apply them to real-world User Stories.

## Further Readings
- Scrum.org: [Definition of Done](https://www.scrum.org/resources/definition-done)
- Roman Pichler: [Definition of Ready vs. Definition of Done](https://www.romanpichler.com/blog/the-definition-of-ready/)
- Atlassian: [Agile Stories, Epics & Tasks](https://www.atlassian.com/agile/project-management/epics-stories-themes)

## Tasks
1. **Analyze** the following User Story:
   > "As a user, I want to receive an email when my password is changed so I can be alerted to potential security issues."

   - Define what the **Definition of Ready** might include for this Story.
   - Define a realistic **Definition of Done**.

2. **Create** one User Story for a feature of your choice and write:
   - Acceptance criteria
   - DoR and DoD checklists

3. **Review** a peer's User Story and provide feedback:
   - Are the criteria specific and actionable?
   - Is the DoD testable and verifiable?

## Questions
- What happens if a Story enters a Sprint without meeting the Definition of Ready?
- Can something be "done" without being truly "valuable"?
- Who should be involved in defining and maintaining DoR/DoD?
- How do you deal with evolving standards (e.g., increasing test coverage)?

## Advice

When working with Definition of Ready and Definition of Done, it's important to keep the DoR short and focused. It should serve to enable the team to begin meaningful work, not act as a bureaucratic barrier. Your Definition of Done, on the other hand, should ensure that work is truly complete: this typically includes functional and automated tests, documentation updates, and meeting all acceptance criteria. It's good practice to revisit both definitions regularly during Retrospectives and refine them as the team matures or requirements change. Consider integrating checklists into your project management tool (like Jira or GitHub Projects) to make these definitions tangible and trackable during everyday work.

