# TechGuide v2.0 — Student Question Recognition and Adobe Workspace Recovery

Cumulative v1.9 preservation release. Added natural-language student symptom routing and Adobe Window > Workspace > Reset Essentials recovery instructions for Photoshop and Illustrator. Preserved 902 English guides, all Google app filters, and prior illustrations. Added three translated Spanish recovery guides, bringing Spanish guide count to 178. Regression review: 58 sample question prompts matched expected primary guides; 258 sampled legacy title/alias searches retained their top-five matching, with no drops. Desktop and mobile simulated Chromium smoke checks passed. Actual school Adobe/Chromebook verification and broader student pilots remain necessary. No external AI or student chat storage was added.

---

# TechGuide v0.7 — Visual Studio

Cumulative offline-first classroom technology help desk for PlayForge. Development release only; no repository or public deployment until at least v1.0 and school review.

## Quick start
Extract the entire ZIP into one folder and open `index.html` in Chrome where local files are permitted. All guides and the matching engine are embedded. Hosted offline caching requires an initial successful HTTPS or localhost visit and browser permission. No login, AI API, external fonts, analytics or saved chat histories.

## v0.7 changes
- New Visual Studio view; the original help desk remains the default. Switching views preserves the chat.
- Five connector illustrations with approved guide links: USB-A, USB-C, HDMI, DisplayPort, and 3.5 mm audio.
- Two clickable simplified keyboard layouts and 21 shortcut cards, filterable by selected key and device/application.
- 25 original Adobe tool illustrations with searchable Photoshop and Illustrator filters.
- Eight interactive concept demonstrations: layers, masks, fill/stroke, anchors, combining shapes, clipping, artboard export and selections.
- Inline visual reference cards for selected relevant guides; opens the matching studio section and links back to guided help.
- All illustration SVGs, code and database remain embedded in index.html. No new network dependencies, accounts or device permissions. The service worker cache version has been advanced.
- The 902 knowledge records are byte-for-byte identical to v0.6; matching engine and safety rules are retained. The new visual cards are supplementary, not additional troubleshooting records. Illustrations are schematics rather than screenshots, and keyboard layouts and tool shortcuts may vary.

### v0.7 verification
- Browser-rendered desktop and mobile at 1440 and 390 pixels; no JavaScript errors during test.
- Tested both device keyboards, selected-key filtering, all five port cards, app filtering and search for 25 Adobe tool cards, all eight interactive demonstrations and every demonstration state, studio-to-chat guide links, inline chat illustration links, homework refusal and normal step progression.
- Direct file navigation is blocked in the test browser; tests render the embedded HTML in Chromium. Hosted offline cache and actual school Chromebook and Windows compatibility remain unverified. No Adobe application was launched during testing.

## v0.6 changes (retained)
- 188 new Illustrator guides, bringing Illustrator to 200 and the complete database to 902.
- 376 new recognition phrases and 376 instructional steps; totals 1,968 aliases (including any repeated strings) and 2,447 steps.
- Nine Illustrator subcategories; two additional quick fixes and improved Illustrator typo and app-name recognition.
- Preserves all 714 earlier IDs, titles, steps, explanations and aliases. Adds organizational subcategories to 12 earlier Illustrator entries.
- New restrictions for Generative Shape Fill, Text to Vector Graphic, Generative Recolor and related generated-art requests.
- Windows desktop Illustrator is the reference platform. App-level view, artwork and document controls are permitted; administrative settings, software installation, school-policy workarounds and generation of student work are not.

## Database counts
| Category | Guides |
|---|---:|
| Chromebook | 131 |
| Windows & devices | 146 |
| Google Classroom | 43 |
| Drive & files | 51 |
| Google apps | 154 |
| Browser & safety | 7 |
| Photoshop | 168 |
| Illustrator | 200 |
| PlayForge | 2 |
| Total | 902 |

## Validation
- Chromium rendered the embedded app with no page errors; desktop and mobile layout, Illustrator filter, next-step progression, escalation, and generative-request refusal tested successfully.
- All 376 new aliases ranked their intended guide first with an explicit Illustrator prefix. This verifies matching, not every possible natural-language question.
- Compared 1,591 unique prior guide/alias pairs against v0.5: no previously top-five match fell outside the top five, and no existing safety classification changed.
- Direct file navigation was blocked by the test environment; real school-device compatibility and hosted service-worker installation/offline reload remain unverified. Illustrator itself was not run; menu labels vary by installed version. Review content before student rollout.

## Safety and privacy
Fixed instructions only. No generation of homework, images or code; no protected system settings, installations, security changes or administrative tools. Escalate unsafe hardware and unapproved actions to staff. Only adjust student-owned artwork and permitted app document/view controls. Student messages are held in memory until reset or close. Server and network logs are outside this application. `knowledge.json` is a review copy; changing it alone does not replace the embedded runtime database.

## Illustrator reference documentation
- https://helpx.adobe.com/illustrator/desktop/get-started/learn-the-basics/illustrator-tools-reference.html
- https://helpx.adobe.com/illustrator/desktop/get-started/preferences-and-settings/default-keyboard-shortcuts-for-illustrator.html
- https://helpx.adobe.com/illustrator/desktop/design-with-text/edit-format-text/create-type-on-a-path.html
- https://helpx.adobe.com/illustrator/desktop/manage-objects/reshape-transform-objects/combine-objects-using-pathfinder-effects.html
- https://helpx.adobe.com/illustrator/desktop/draw-shapes-and-paths/learn-drawing-basics/drawing-modes-overview.html
- https://helpx.adobe.com/illustrator/desktop/save-and-export/export-files-to-different-formats/export-artwork-from-illustrator.html
- https://helpx.adobe.com/illustrator/desktop/save-and-export/export-files-to-different-formats/export-artboards-and-assets-for-screens.html

## Next releases
v0.8 Spanish and accessibility; v0.9 teacher customization; v1.0 final verification and release.

## Earlier content references
- https://helpx.adobe.com/photoshop/desktop/troubleshoot/tool-feature-issues/fix-unexpected-tool-behavior-in-photoshop.html
- https://helpx.adobe.com/photoshop/desktop/create-masks/layer-masks/add-layer-masks.html
- https://helpx.adobe.com/photoshop/desktop/create-manage-layers/create-layer-compositions/non-destructive-editing-techniques.html
- https://helpx.adobe.com/photoshop/desktop/repair-retouch/clean-restore-images/healing-brush-tool.html
- https://helpx.adobe.com/photoshop/desktop/create-masks/layer-masks/save-and-load-selections.html

- https://support.google.com/edu/classroom/answer/6020285
- https://support.google.com/edu/classroom/answer/9073815
- https://support.google.com/drive/answer/2375091
- https://support.google.com/drive/answer/2424384
- https://support.google.com/drive/answer/2375012
- https://support.google.com/docs/answer/6199477
- https://support.google.com/docs/answer/6282736

## v0.8 — Español and accessibility (pilot)

- The original 902 English guides remain unchanged. 108 of those guides now have reviewed-by-design, fixed Spanish text (not independently bilingual-reviewed). `knowledge-es.json` is the editable translation source; the app embeds the same data so a local HTML file can run without fetching JSON. Spanish matching searches only translated guides; switch back to English for the full library. Some Visual Studio labels, tool explanations and shortcut descriptions are still in English. Visual links without Spanish coverage explicitly offer English or teacher help.
- English and Español are always visible. Switching language starts a new chat, so old instructions do not appear mixed with new ones. The app stores only language and accessibility preferences in localStorage where supported, not chats or identities.
- Accessibility: three text sizes, high contrast, focus on current answer (toggle off to restore earlier messages), reduced motion, slower read aloud, explicit read and stop buttons. These change only TechGuide, not operating system or school settings. Speech is opt-in, reads the current assistant response only, and selects a local voice for the current language. It never chooses a remote voice. If a local voice is absent, it displays a message. Actual voice availability depends on the device.
- Spanish and English restricted requests and urgent hardware issues receive fixed refusal or teacher referral responses. No new administrator procedures, generators, external services, or student accounts.
- Test status: Chromium desktop and 390px mobile viewport, browser language toggles, Spanish search and sample guided answers, restricted/homework and danger responses, Visual Studio navigation and all eight demo cards, accessibility controls, and missing-local-voice behavior. Test environment blocks file navigation, so HTML was loaded directly into the browser; hosted service worker caching and actual school device speech/compatibility remain pending. Translation terminology should receive bilingual staff review before deployment.
- Do not publish to GitHub or PlayForge until at least v1.0. Next: teacher customization, classroom help content and review workflow.

## v1.2
Rewrote Classroom (43) and Drive & files (51) English guides; updated 10 Spanish guides. Existing guide IDs retained.

## v1.3
Rewrote all 131 Chromebook English guides and all 21 existing Chromebook Spanish guides. Added contextual alternatives to 16 English guides. No new guide IDs. Teacher Workshop discontinued.

## v1.4
Rewrote 146 English Windows and peripheral guides, 18 Spanish guides; 18 English topics with contextual links. Previous topics unchanged.

## v1.5
Revised 168 Photoshop guides and 17 Spanish counterparts. 15 English alternate-path groups. Earlier guides preserved.

## v1.6
Revised all 200 Illustrator English guides and 18 existing Spanish counterparts. Added contextual alternatives to 16 English guides. Earlier guides preserved.

## v1.7
Rewrote remaining 163 English guides (154 Google applications, 7 browser/safety, 2 PlayForge) and their 20 existing Spanish counterparts. All 902 English guide IDs retained, all earlier content unchanged. Added 26 English alternate-path groups.

## v1.8 — Visual walkthroughs
Preserved all 902 English and 175 Spanish guide records. Added 61 referenced step-specific original visual examples covering 222 steps in 75 English guides. Improved targeted student phrasing and navigation. No Teacher Workshop. See README for verification limits.
