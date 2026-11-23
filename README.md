# TechGuide v2.0 — Student Question Recognition & Adobe Workspace Recovery

This cumulative update builds directly on v1.9 and keeps **all 902 original English guides**, Google Apps quick filters, classroom walkthroughs, 61 original illustrations, Adobe Visual Studio, keyboard shortcuts, accessibility settings and offline operation.

## What's new
- Adobe toolbar recovery: Photoshop **Window > Workspace > Essentials > Reset Essentials**; Illustrator **Window > Workspace > Essentials > Reset Essentials**, with alternative names noted for version differences. Includes fallback Window > Tools / Toolbars > Advanced and the Tab shortcut.
- Adds natural-language aliases for missing toolbars, missing layers, Classroom hand-in and attachment questions, forgotten screenshots, and classroom vocabulary (including the taught Photoshop “Japan flag” layer-mask and “half circle” adjustment shortcuts).
- New prioritized, app-aware question routes for missing Adobe tools, missing Classroom assignments, lost attachments, screenshot files, sound, cursor movement, text outlines, keyboard lettering, and other student descriptions. When app/device is uncertain, the app offers choices rather than jumping to the wrong guide.
- Preserves existing homework/refusal and device-safety checks *before* new matching.
- English guides remain **902**; Spanish guides increase from **175 to 178**, translating the Photoshop toolbar, Photoshop panels and Illustrator panels recovery guides. Existing Spanish guide content is retained except two updated Adobe recovery walkthroughs.
- Service worker cache updated to **v2.0**; existing student preferences and classroom settings remain compatible.

## Install
Upload all eight files in this ZIP into the existing `techguide` GitHub repository root, replacing the files with matching names. Do not delete your project or change the PlayForge landing page. When using GitHub Pages, reload once online to obtain the new offline cache. The `knowledge.json` and `knowledge-es.json` files are teacher review copies; editing them without rebuilding `index.html` does **not** update the embedded app.

## Scope and verification
- Matching is fixed-guide retrieval, **not generative AI** and not a web search.
- Adobe menu labels can vary by version; the reset affects workspace layout, not saved artwork. It can replace a student's custom panel arrangement.
- No student accounts, AI service, chat history logging or new network calls were added.
- Automated recognition and browser smoke tests were performed for this development ZIP. Run a short pilot on actual school Chromebooks and Adobe-equipped Windows devices before a wider rollout.
- Reference: https://helpx.adobe.com/photoshop/desktop/troubleshoot/tool-feature-issues/missing-tools.html and https://helpx.adobe.com/illustrator/using/customizing-workspace.html
