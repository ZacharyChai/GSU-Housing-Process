# GSU Housing Check-In Process Optimization
 
Redesigned Georgia State University's on-campus housing check-in workflow using Lean process improvement principles. Identified and eliminated 4 sequential in-person verification checkpoints from the RA workflow, reducing queue time and removing the most common source of repeated student interactions.
 
Modeled in **Bizagi Studio** across 4 swim lanes (AS-IS) → 5 swim lanes (TO-BE).
 
---
 
## The problem
 
The AS-IS process required RAs to perform 4 sequential verification checks on every student at the desk:
 
1. Panther ID verification
2. Confirmed housing reservation
3. Financial clearance confirmation
4. Fire Safety Module score (>8/9) + Resident Information Record completion
Each failed check sent the student out of the queue with instructions to resolve the issue and return — rejoining the back of the line. This created cascading delays during peak move-in hours across 5 dorm locations.
 
Additional pain points:
- Key Manager couldn't prepare keys until after RA checks completed, adding waiting time
- Mismatched access cards triggered a separate RHD database update form
- Process was inconsistent across Piedmont North, Piedmont Central, Patton Hall, University Lofts, and University Commons
---
 
## What changed
 
| | AS-IS | TO-BE |
|---|---|---|
| Verification checks | 4 sequential checks at RA desk | Moved to pre-arrival self-service Move-In Form |
| Student arrival step | Join queue, wait for RA | PantherID scan at lobby computer auto-queues student |
| Key Manager trigger | Waits for RA checks to complete | Receives student info directly from lobby computer scan |
| Incomplete students | Rejoin main queue | Resolved before arrival via form error instructions |
| Swim lanes | 4 (Student, RA, Key Manager, Front Desk) | 5 (+ Lobby Computer) |
 
---
 
## Process metrics defined
 
- **Lead time per student** — total time from queue entry to check-in complete
- **Error rate** — percentage of applications with missing or incorrect information
- **Ease of use** — student-facing friction across the check-in flow
---
 
## Skills demonstrated
 
- Bizagi Studio — multi-swimlane AS-IS and TO-BE BPMN workflow modeling
- Lean process analysis — identifying rework loops, waiting waste, and motion waste
- KPI definition and requirements documentation
- Implementation planning — cost constraints, failure modes, change resistance, scope management
---
 
## Files

- [AS-IS.png](AS-IS.png) — original 4-lane workflow with annotated waste
- [TO-BE.png](TO-BE.png) — redesigned 5-lane workflow with lobby computer integration
- [Project PP.pdf](Project%20PP.pdf) — full report with diagrams, critique, and recommendations
 
## Team & context
 
Capstone project · CIS 4120 · Georgia State University  
Team: Dalitso Moyo, Zachary Chai, Emmanuel Clark, Matthew Humphrise  
Role: process modeling, inefficiency analysis, KPI documentation, redesign recommendations
 
