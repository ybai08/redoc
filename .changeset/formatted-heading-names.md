---
"redoc": patch
---

Fixed sidebar names and section ids for description headings that contain inline formatting: `## Header with **bold**` is now listed as "Header with bold" (id `…/header-with-bold`) instead of being cut off at the first bold, italic or code span.
