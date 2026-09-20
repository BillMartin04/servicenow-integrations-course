---
description: 'Circuit Breaker and Source Control: a five minute demonstration with a published 34 point rubric.'
---

# Exam 3: Circuit Breaker and Source Control

**Quick answer:** Prepare and test your work, then record a narrated demonstration of no more than five minutes. This assessment covers Modules 7, 8 and contributes 34 points to the 100 point course total.

{% hint style="warning" %}
Personal review is for active [Exam Navigator members or higher tiers](https://www.youtube.com/channel/UCMf7pje1x5iZkkEF-Y3PLSA/join). The tasks and rubrics are available to everyone for practice; check the submission guide for intake availability.
{% endhint %}

## The scenario

An external dependency can fail, and another developer needs to understand your changes. Demonstrate the circuit breaker example from Lesson 7.1 and the source control workflow from Lesson 8.1.

## What you must demonstrate in your video

1. Explain the circuit breaker example and identify the condition that changes its behavior.
2. Demonstrate normal behavior, a simulated failure and recovery using a controlled endpoint.
3. Show sanitized logs or test results that explain the failure and recovery.
4. Show a harmless scoped application change and its commit in your own practice repository.
5. Use Lesson 7.2 to explain whether a supported capability or custom scripting fits your scenario, and identify one remaining limitation.

Build before recording. Use only your own lab, synthetic data and authorized endpoints; never show passwords, access tokens or client secrets.

## Grading rubric (34 points)

Select full, partial or no credit for each criterion. Add the awarded points and retain the evidence used to justify the score.

| Criterion | Full credit | Partial credit | No credit |
|---|---|---|---|
| Pattern explanation | 7: The explanation is specific to the implementation shown. | 3: The pattern is named but its condition is unclear. | 0: No relevant evidence. |
| Failure and recovery | 7: All three states are evidenced. | 3: Only some states are demonstrated. | 0: No relevant evidence. |
| Diagnostic evidence | 7: Evidence supports both observations without exposing secrets. | 3: Evidence is incomplete or difficult to relate to the test. | 0: No relevant evidence. |
| Source control | 7: The commit is linked to the application change. | 3: A repository connection is shown but no corresponding commit. | 0: No relevant evidence. |
| Implementation decision | 6: The choice and limitation are specific and justified. | 3: The choice is asserted with little justification. | 0: No relevant evidence. |
| Total possible | 34 | | |

### Evidence checklist

* [ ] Explain the circuit breaker example and identify the condition that changes its behavior.
* [ ] Demonstrate normal behavior, a simulated failure and recovery using a controlled endpoint.
* [ ] Show sanitized logs or test results that explain the failure and recovery.
* [ ] Show a harmless scoped application change and its commit in your own practice repository.
* [ ] Use Lesson 7.2 to explain whether a supported capability or custom scripting fits your scenario, and identify one remaining limitation.

### How this exam maps to your final score

This exam contributes 34 points. The three assessments are worth 33, 33 and 34 points, totalling 100.

| Combined score | Result |
|---|---|
| 90 to 100 | Pass with Distinction |
| 70 to 89 | Pass |
| 50 to 69 | Revise and resubmit |
| Below 50 | Review the lessons and resubmit |

The threshold applies to the combined score, not to a 70 point requirement on an individual exam.

## How to submit

Read the [Submission Guide](submission-guide.md) before sharing a recording. Prepare all three recordings together; do not send secrets, real customer data or credentials.

## Continue

[Final assessment overview](README.md)

Back to: [Final assessment overview](README.md) | [Course home](../README.md) | [Full syllabus](../SYLLABUS.md)
