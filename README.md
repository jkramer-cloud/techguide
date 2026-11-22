# TechGuide v1.9 — Google Apps quick filters

Upload **all eight release files** into the existing `techguide` GitHub Pages repository root, replacing files with matching names. This is a cumulative v1.9 update built on v1.8; no PlayForge website changes are necessary.

## What's new
- Clicking **Google apps** in Explore Help now shows large, accessible quick-filter buttons for All Google Apps, Classroom, Drive, Docs, Slides, Sheets, Forms, and Other questions (including Meet and Drawings).
- The buttons filter existing student help guides directly in the center workspace; there are no external Google website redirects. Classroom and Drive entries remain in their original main help categories too.
- The app picker and search work together. Changing the app clears an old search to avoid misleading zero-result screens. The selected app remains active when returning from an individual guide.
- Spanish button labels and guide-availability counts are supported. Mobile screens use a compact two-column layout. All existing help categories, guides, Adobe Visual Studio, safety rules, and accessibility controls remain.
- Offline service-worker cache bumped to **v1.9** to avoid stale site code.

## Version 1.8 features preserved

- 61 original simplified interface diagrams used in 222 steps across 75 English guides. The diagrams highlight controls and describe the expected result. They are not screenshots of the actual school software; labels and layouts may vary.
- Classroom submission walkthroughs show the class tile, Classwork, assignment details, Your work, attaching files, Turn in and submission status. An optional jump skips navigation when the student already has the assignment open.
- Width-aware layout displays the current instruction and its illustration together on wide screens; narrower devices use a single column with navigation controls above the diagram. The instruction stays at the top instead of automatically scrolling away.
- Targeted recognition for student phrasing relating to submissions, layers, text outlines, exports, screenshots, downloads and sound. Ambiguous device/app questions offer a choice. The existing refusal rules run before the targeted recognition.
- All 902 English and 175 Spanish guides preserved verbatim. The new step-specific diagrams are English-only; existing Spanish walkthroughs and visual studio remain available. The previous 165 shortcut entries and accessibility functions remain in place.
- Previous v1.8 offline cache supported.


## Verification and limitations
- Confirmed all embedded guides, knowledge data files and built-in diagrams from v1.8 are preserved. Button filters are navigational only; they do not certify Google UI layouts.
- Test using the hosted GitHub Pages site after uploading all eight files. Actual school sign-in and web app compatibility are not simulated; screenshots and diagrams remain simplified examples.
- The app retains the existing v1.8 classroom-pilot and Spanish-translation coverage limitations.
