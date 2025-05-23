---
layout: default_dl
parent: Design Document
title: Final Updates
nav_order: 13
---
# Final Updates

As you finish your project, you should update your design document with some new sections: `Updated Design`, `Final Features`, and `Lessons Learned`.

## Updated Design
You **must** update your class diagram from [Phase 3](doc_phase3#diagrams) to reflect the actual classes, methods, and relationships in your final implementation of your project. Note that you **should not** remove your old diagrams; instead, add a new section in your document and put your new diagrams.
  - Add any new classes you created during development
  - Remove classes that were planned but not implemented
  - Update method signatures that changed
  - Correct relationships/associations between classes

You may also opt to update other diagrams (ex: Sequence/Flow Chart Diagrams) you made in the project, but this is not required.

## Final Features

Create a table of your expected "core features" (the ones you created from the [Core Features tab in Phase 1](doc_phase1#project-scope--features) of your Design Document) and a second column of your actual features implemented. This second column may include stretch features if you were able to implement those.

Example:

| Expected Core Features | Actual Features Implemented |
|----------------------|---------------------------|
| User registration & login | ✅ Complete registration and secure login with password hashing |
| Basic ride request & acceptance | ✅ Implemented with real-time location updates |
| In-app payments & fare estimation | ⚠️ Partially implemented - fare estimation works but payment is mocked |
| Ride scheduling & multi-stop trips | ❌ Not implemented - ran out of time |
| Driver & passenger ratings | ✅ Full rating system with comment features added |
| Real-time traffic-based routing | ✅ Implemented using Google Maps API integration |
| Emergency SOS button | ✅ Added with direct police contact functionality |

_Note that there may be more rows in one column depending on your implemented features._


## Lessons Learned

Using your original "Learning Targets and Goals" section from [Phase 1](doc_phase1#learning-targets-and-challenge-goals), copy those to a new table, and add a second column that is a summary of your actual lessons learned (pulled from your Task List spreadsheet). Summarize your lessons learned in this table. 

Example:

| Original Learning Targets/Goals | Actual Lessons Learned |
|-------------------------------|----------------------|
| Learn GPS and mapping APIs | Successfully integrated Google Maps API but discovered the complexity of handling location updates in real-time. Event-driven programming was essential for this functionality. |
| Master concurrent programming | Implemented multi-threading for background location tracking and ride matching. Learned that proper synchronization is crucial to avoid race conditions when updating shared ride data. |
| Develop secure authentication | Implemented secure password storage with bcrypt and token-based authentication. Discovered that security requires constant vigilance and that robust error handling is essential. |
| Learn payment gateway integration | Created a mock payment system but learned about PCI compliance requirements. Realized that third-party payment processors are the safer option for handling sensitive financial data. |
| Implement real-time data synchronization | Used Firebase for real-time updates between riders and drivers. Learned that designing proper data structures upfront is critical for efficient real-time applications. |

_Note that there may be more rows in one column depending on the number of lessons learned._

Both you and your partner should also write a paragraph on your individual learnings from this project. Here are some sample questions to get you started, but you can choose to answer different ones:
- What were some unexpected setbacks? Were you able to overcome them?
- Is there any skills or concepts you hope to continue developing?
- Were there issues with balancing your work across tasks? Did you have to pivot at some points?


Proofread your document for grammatical and syntactical errors, and submit your final document to Schoology before the deadline.