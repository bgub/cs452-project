# CS 452 Final Project Log

Project: OS2, an offline-capable personal productivity app developed in [bgub/garage](https://github.com/bgub/garage).

The project is expected to involve 30–40 hours of work in total. Update this log after each work session, then commit and push the changes.

| Date | What | Hours |
| --- | --- | ---: |
| 2026-11-06 | Built the offline foundation with authentication, local storage, and Convex synchronization. Added keyboard-driven todo outlines, reusable synced collections, and the initial offline rich-text note editor. | 4 |
| 2026-11-07 | Fixed note rendering shifts, undo behavior that could erase saved content, and blocked app-update reloads. Added regression tests and simplified note synchronization. | 0.5 |
| 2026-11-11 | Added synced habit tracking, Helix-style rich-text editing, tables and task lists. Improved the interface and added regression tests and production-build configuration. | 3.5 |
| 2026-11-15 | Worked on task checkpoint/history implementation, including content-addressed history trees, checkpoint storage, and tests. | 1 |
| 2026-11-16 | Added offline history caching and viewing, refined browser tests and the Changes page, and integrated the work into Garage. | 1.5 |
| 2026-11-17 | Added the offline iOS todo companion and improved task interactions. Built offline journals, multiple named journals, and trash/restore behavior. Fixed navigation and sync-related behavior. | 4.5 |
| 2026-11-18 | Set up the project repository and work log with AI assistance; reviewed OS2’s data model, created and reviewed an ERD, and explored offline synchronization and checkpoint-storage design alternatives. | 1.5 |
| 2026-11-19 | Reviewed and refined the offline data model; added journal conflict preservation and journal checkpoints, per-record confirmed storage, merging of unsent edits, local history-cache cleanup, and receipt retention. Presented OS2 to classmate Vin and exchanged project feedback (about 40 minutes, included in this day’s total). | 3 |
| 2026-11-20 | Completed the data modeling and system design interviews with TA Andrew (30 minutes total) and reviewed classmates’ project designs (about 15 minutes total). All 45 minutes count toward collaboration and are included once in the project total. | 0.75 |
| 2026-11-23 | Presented OS2 in class and listened to classmates’ project presentations. One hour of collaboration, plus three hours working toward the journal images/offline uploads, journal metadata, MCP connections, and settings changes later committed in Garage as [`62c1cff`](https://github.com/bgub/garage/commit/62c1cffd1a6a5fb6ac0a768831c78f62bd76daa1). | 4 |
| **Total** | | **24.25** |

The Nov. 6–17 hours are retrospective estimates, allocated from my estimated 15 hours of personal project work using Git history to reconstruct the activities. They are not measured session durations. Nov. 11 is the commit date for a batch of work that may span earlier sessions. Earlier work bundled into later commits is counted only once. Unattended AI execution time is not counted.

The Nov. 19 total is my retrospective estimate of 3 hours, including approximately 40 minutes collaborating with Vin; that collaboration is not added again to the total. The Nov. 20 entry records my reported 30 minutes of interviews and approximately 15 minutes of peer reviews. The Nov. 23 entry includes one hour presenting and listening to classmates in class plus three additional hours of project work, reported on Nov. 25. The additional hours are not classified as collaboration. Their activity description is reconstructed from the subsequent Nov. 24 commit batch (`62c1cff`); no commits were timestamped Nov. 23 in the available local Git history, so the exact allocation of individual changes to Monday is inferred rather than established by Git. The three-hour duration and Monday date are my reported time, not estimates from commit volume. Recorded collaboration so far: approximately 2 hours 25 minutes of the required 3 hours (40 minutes with Vin + 30 minutes with Andrew + 15 minutes of peer reviews + 60 minutes in class). Presentation preparation has not been separately itemized; no extra preparation hours have been added beyond the reported totals.
