# Delivery Review — Evergreen Quote

> Copy to `delivery-leadership-package/delivery-review-outline.md`. Five slides OR one page. Target: 5 minutes spoken, then 3 minutes of questions.

## Slide 1 — Delivery goal & did we hit it?

- Goal (one sentence): Deliver a responsive Evergreen Quote page with responsive layout, working quote calculation logic, themed styling, and successful CI Run
- Hit? ☐ Yes  
- One-line "why" either way.

## Slide 2 — What shipped

- Screenshot of assembled Evergreen Quote app on `main`.
- Link to the merged PR. https://github.com/asc1-student16/wa3855-cap-phase-1-capstone-project-leaders/pull/7
- Link to the green CI run.https://github.com/asc1-student16/wa3855-cap-phase-1-capstone-project-leaders/actions/runs/29520763833

## Slide 3 — Two key decisions

- **Decision 1:** Testimonials:Legal has approved the top 3 testimonials. Include these testimonials that is exactly the way they are approved to avoid any complications.
- **Decision 2:** Exclude "Compare plans" link in the navigation as this came as last minute story in the sprint. If there is capacity, pull it into the sprint else prioritize it for the next sprint.
- (Both should be in `decision-memo.md`.)

## Slide 4 — Risks & injects

- Top risk we tracked: _from risk-register.md._
- Inject #1 (Tue): Medium: Including testimonials in the release. Legal has approved them without getting the signed customer release forms. We moved forward with the assumption that customers will provide signed release forms with the approved verbiege from legal. We are confident that legal team will get these forms signed without any issue. 
- Inject #2 (Wed): High: We treated the quote anomaly and the CI failure as a delivery risk and paused any further release advancement until the root cause was understood. The missing asset file indicates the build is not in a releasable state, and the invalid premium suggests the current renters rate configuration may be incorrect or incomplete. We prioritized investigation of the renters rate logic and the generated asset pipeline before making additional changes.
## Slide 5 — What I'd do differently next round

- I would like to continue meeting the sprint goals and at the same time any additional work that is NOT committed as a part of sprint goal should be considered as a less priority as long it is a blocker or critical production issue.
- Testing coverage & UI: Want to get signoff from the UI team on the UI Wireframes before working as well as Would like to include extensive testing including the UI components and field validations.

## Q&A prep — likely questions

- _e.g., "Why didn't you ship X?"_I have not shipped field validations. Example: Zip code should give an error message if the value is less than 5 digits. There are no requirements mentioned for the field validaions.
- _e.g., "If you ran this week again with 3 engineers, what's the first thing you'd ask them?"_
What is the current highest-priority risk or blocker that you see could prevent us from shipping a clean,Evergreen Quote delivery this week. If we need to trade scope to protect the deadline, what can we safely defer without hurting the main delivery objective?