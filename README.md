# Markup

A review tool for HTML prototypes. Reviewers click a component to pin a comment or a sticky note for developers, reply in threads, and mark items done.

## Features

- **Four ways to add a POC:** paste HTML, upload a ZIP folder (CSS, JS, images and fonts are folded into one page, and large images are re-encoded to WebP), upload a screenshot, or link a live URL.
- **Comments anchored to elements:** hover a component to highlight it, click to pin. The anchor is a CSS path, so pins follow the element when the page scrolls or resizes.
- **Comments stay on their screen:** each comment remembers the screen it was left on — which tabs and pills were selected, plus the text of its element. Clicking a comment navigates the prototype back to that screen.
- **Sticky notes** for developer handover, shown directly on the prototype.
- **Progress tracking:** a resolved-percentage ring, open/resolved/notes counts, a progress bar per prototype, and per-reviewer totals.
- **Filter by reviewer:** click an avatar to see only that person's comments.
- **Full view** with a floating composer. Keyboard shortcuts: `C` comment, `N` note, `A` annotations, `F` full view, `1`–`4` viewport width, `Esc` back out.

## Files

| File | What it is |
|---|---|
| `index.html` | Standalone version — open it in a browser. Runs in preview mode: comments stay in that tab. |
| `markup-artifact.html` | Source for the hosted Claude Artifact, where comments, files and reviewer identities are shared. |

## Run locally

```bash
open index.html
```

Shared comments, ZIP/screenshot storage and reviewer names only work in the hosted Artifact version; the standalone page is for trying it out.
