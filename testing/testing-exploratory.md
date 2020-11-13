# Exploratory testing

Scripted test execution is usually a non-thinking activity where testers execute the test steps and compare the actual results with expected results. Such test execution activity can be automated and does not require many cognitive skills. Exploratory testing is unscripted, is thoughtful, and allows the tester to flow freely throughout a system under test.

> Interacting with a product of system with the express intention of sharing information about it

- It helps the tester quickly identify major discrepancies, thus helping to develop the application to meet actual-world requirements of end users.
- It is cognitively structured compared to the procedural framework of scripted testing.
- It is an approach and not a technique. The next course of actions is governed by the current course of actions.
- It is significantly teachable and manageable.
- Exploratory testing itself is highly useful but when dovetailed with other testing processes, it becomes a powerful way to understand the application in a better manner, build better functional tests and finally enhance the quality of the application.

Exploratory testing can be undertaken across the entire development lifecycle from exploring documentation such as requirements, user stories etc and can be used for non-functional testing.

- Finding information
- Collaborative
- Structured
- Relevant
- Planned
- Documented

## Implementation

1. Understand the technique
2. Use mind-mapping tools/ideas to build up test ideas
3. Use a charter to record test ideas and share with team.
4. Feedback often - before and after execution.

### Technique

- Explore `target`
- With `resources`
- to Discover - information related to `risk`

This gives the scope, tools, and an aim.

### Charter / Mission

A charter or mission is open, but scoped i.e. I want to look at this area of the system. It is specific yet flexible, aligned towards investigating opportunities, report focuses on sharing knowledge.

Build a charter or plan using the following table structure, negotiate and discuss this with the team to ensure priorities are correct and identify risks and adjust time box accordingly.

| ID | Description | Priority | Time box |
|---|---|---|---|
| 1| **Explore** the chair **With** different sizes of people to **Discover*** related to whether the seat may be too narrow | medium| 1hrs |
| 2| **Explore** the chair seat **With** people wearing different clothes to **Discover** information related to whether the seat may be too narrow | high | 2hrs |

The charter should include all test ideas, but this does not mean all need to be run - focus on risks and priorities. Keep the charter up to date and include retests (typically with lower priority and time box).

### Feedback

Report on the positives and negatives to the team, build trust and demonstrate the value in the activity.

1. Demonstrate
2. Report in bug tracking tool (jira etc)
3. Describe and document steps taken (confluence, wiki etc)
4. Retest

> tip: Bugs beget bugs, typically due to complexity of that part of the system - so identifying bugs should lead to some work with the team to add more unit tests

## Time

The majority of a tester's time should be spent on exploratory perhaps 80/20 versus automation/regression/test packs.

In sprints, exploratory testing could begin immediately whilst new features are being developed.
