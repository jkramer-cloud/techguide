# TechGuide v1.8 — Visual walkthroughs

Upload all eight files directly into the existing `techguide` GitHub Pages repository root. No PlayForge update or Teacher Workshop needed.

## What's new
- 61 original simplified interface diagrams used in 222 steps across 75 English guides. The diagrams highlight controls and describe the expected result. They are not screenshots of the actual school software; labels and layouts may vary.
- Classroom submission walkthroughs show the class tile, Classwork, assignment details, Your work, attaching files, Turn in and submission status. An optional jump skips navigation when the student already has the assignment open.
- Width-aware layout displays the current instruction and its illustration together on wide screens; narrower devices use a single column with navigation controls above the diagram. The instruction stays at the top instead of automatically scrolling away.
- Targeted recognition for student phrasing relating to submissions, layers, text outlines, exports, screenshots, downloads and sound. Ambiguous device/app questions offer a choice. The existing refusal rules run before the targeted recognition.
- All 902 English and 175 Spanish guides preserved verbatim. The new step-specific diagrams are English-only; existing Spanish walkthroughs and visual studio remain available. The previous 165 shortcut entries and accessibility functions remain in place.
- Offline cache version updated to v1.8.

## Verification and limitations
- Checked all guide IDs, nonempty steps, alternative references, embedded English JSON and visual mappings. Database files match v1.7 byte for byte.
- Chromium content-loaded tests exercised Classroom navigation, missing layers clarification, Illustrator PNG export, screenshot routing, refusals, Spanish guide selection, Visual Studio and mobile width. Direct file navigation was blocked by the test browser's administrator policy; hosted service-worker caching and actual school account/software compatibility are not verified. No external AI or new online assets.
- Diagrams are simplified instructional examples, not live screenshots. This is a classroom pilot, not a certification of each of the 1,077 language-specific guides. Spanish translation coverage is still partial.
