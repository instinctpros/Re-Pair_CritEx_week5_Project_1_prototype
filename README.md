# RE:PAIR — Prototype 01

An illustrated manual for reclaiming your attention, by Krystal Joy Brown.

## Open in a browser

Open `index.html` from this download. Keep `style.css` and `sketch.js` alongside it. No installation, database, or external script is required.

## Use in the p5.js Web Editor

1. Create a new sketch.
2. Replace the contents of the editor's `index.html`, `style.css`, and `sketch.js` with the matching files in this download.
3. Press Play. Expand the preview for the three-column desktop layout. Narrow previews intentionally show the mobile sequence.
4. Save the sketch in your account to get a shareable editor/preview link.

This prototype uses HTML, CSS, JavaScript, and SVG. It does not use the p5 drawing API; the editor can host the three files without it. Replacing index.html removes the editor's default p5 imports, so a separate p5 canvas is not created. We can add p5 artwork in a later iteration.

## What is implemented

- A clear entry point and six linked sections.
- Downward diagonal NOTICE → REVEAL → REPAIR layouts on desktop.
- A gently offset vertical layout on small screens.
- Scroll-triggered fades and soft ghosting of previous stages.
- Introductory text fades and a faint branching background metaphor.
- Answer-dependent reveals, adjustable exposure illustration, purchase checklist, and work reflection fields.
- Editable SVG instruction drawings and verified interview excerpts.
- Session-only repair choices, research links, and print styles.
- Keyboard focus styles and reduced-motion support.

## Research and limits

The exposure illustration calculates minutes × assumed posts per minute. Six is an illustrative default, not an empirically established Instagram average. It is not a measurement of advertising impressions or persuasion.

Sources are linked in the manual. Interview excerpts were checked against the transcripts supplied for this project. The speakers' comments are presented as interview perspectives, not general scientific findings. No full transcripts or unrelated personal conversation are included in the source bundle.

No answers are sent or saved by the application. Refreshing clears the page state. The hosted Site itself can have access controls independent of this client-only prototype.

## Edit

`style.css`: color, spacing, diagonal offsets, type sizes, animation.

`sketch.js`: questions, choices, response logic, interview excerpts, SVG drawings.

`index.html`: cover, contents, ending, research notes.

`process-blog-draft.md`: editable first-person process documentation. It describes the prototype, not completed user testing.

## Verification

JavaScript syntax, HTML references, responsive CSS structure, excerpt text, and package contents were checked. Browser visual QA was unavailable in the build environment. This is the first prototype for review and critique; its pacing and layout should be assessed in the user's browser.

The print option makes a reading copy. A physical accordion-fold edition and demographic personalization have not yet been designed.
