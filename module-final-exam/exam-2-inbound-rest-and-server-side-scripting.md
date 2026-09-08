---
description: 'ServiceNow Integrations Masterclass final exam 2: 5-minute video building inbound rest and server-side scripting for graded rubric review.'
---

# Exam 2 — Inbound REST and Server-Side Scripting

**Quick answer:** Record a single video of **5 minutes maximum** demonstrating the tasks below in your own ServiceNow Personal Developer Instance (PDI), narrating as you go. This exam covers **Inbound REST API, Script Includes, GlideAjax** and is worth **33 points**.

{% hint style="warning" %}
**Members-only review.** Your video is only graded if you are an active **Exam Navigator** member (or any higher tier) of [TechTalk with Bill](https://www.youtube.com/channel/UCMf7pje1x5iZkkEF-Y3PLSA/join). Include your membership email/handle when you submit.
{% endhint %}

## The scenario

Prove you can expose data from ServiceNow via an inbound REST endpoint and bridge server-side logic to the client.

## What you must demonstrate in your video

Complete and narrate each of the following:

1. Create a **Scripted REST API** endpoint that returns data from a table (for example, count of open incidents by priority).
2. Test the endpoint with the REST API Explorer and show the JSON response.
3. Create a **Script Include** with a client-callable method that returns the same data.
4. Call it from a client script or UI action using **GlideAjax** and display the result.
5. Explain when you'd use Scripted REST vs. GlideAjax vs. a Table API.

{% hint style="info" %}
**Time limit: 5 minutes.** Plan your steps before you hit record. Part of the skill is doing this efficiently — just like a real practitioner under deadline.
{% endhint %}

## Grading rubric (33 points)

Each criterion is scored at one of three levels so you know **exactly what you must prove on screen** to earn the points. Your instructor circles the level reached and returns written feedback.

| Criterion | ✅ Full credit — *proof required* | 🟡 Partial credit | ❌ No credit |
|-----------|-----------------------------------|-------------------|--------------|
| **Scripted REST API** | **7 pts** — Resource returns correct JSON from a real table. | **3 pts** — Resource returns something but not correct. | **0 pts** — No resource. |
| **REST test** | **7 pts** — REST API Explorer test shows valid JSON. | **3 pts** — Test runs but returns wrong shape. | **0 pts** — Test not shown. |
| **Script Include** | **7 pts** — Client-callable Script Include is correctly authored. | **3 pts** — Script Include exists but not client-callable or with errors. | **0 pts** — No Script Include. |
| **GlideAjax** | **6 pts** — GlideAjax call from client returns data and displays it. | **3 pts** — GlideAjax call made but data not displayed. | **0 pts** — No GlideAjax. |
| **Design reasoning** | **6 pts** — Correctly distinguishes Scripted REST vs. GlideAjax vs. Table API. | **3 pts** — Partial distinction with one gap. | **0 pts** — No distinction. |
| **Total** | | | **/ 33** |

### Evidence checklist (what the grader looks for)

Your video passes most easily when every item below is visibly true on screen:

- [ ] Scripted REST resource exists and is documented.
- [ ] REST API Explorer test shows a valid JSON response.
- [ ] Client-callable Script Include exists.
- [ ] GlideAjax call from client works and result is displayed.
- [ ] Clear trade-off explanation given.

### How this exam maps to your final score

This exam contributes **33 points** toward your **100-point** final score across all 3 exams:

| Final score | Result |
|-------------|--------|
| 90–100 | 🏆 Pass with Distinction |
| 70–89 | ✅ Pass |
| 50–69 | 🔁 Resubmit (free, unlimited) |
| Below 50 | Not yet passing — resubmit |

**You may resubmit any exam** until you pass — the goal is mastery and confidence, not a single shot.

## How to submit

{% hint style="warning" %}
**All 3 exams are submitted together in one go.** Record all 3 exam videos, then enter all 3 Google Drive links in a single submission. Don't submit one exam at a time.
{% endhint %}

1. Record your screen with voice narration (see the [Submission Guide](submission-guide.md)).
2. Upload the video to **Google Drive** and set sharing to *Anyone with the link can view*.
3. Once all 3 videos are ready, submit them together through the [course submission form](submission-guide.md) — include the **YouTube channel name/handle and email tied to your Exam Navigator (or higher) membership**.

## Continue

Previous: [Exam 1 — REST API Basics and an Outbound Call](exam-1-rest-api-basics-and-outbound-call.md) | Next: [Exam 3 — Advanced Patterns and Source Control](exam-3-advanced-patterns-and-source-control.md)

Back to: [Final Exam overview](README.md) | [Course home](../README.md)

---

*Final Exam & Certification — ServiceNow Integrations Masterclass.*
