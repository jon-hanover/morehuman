# Working on amorehumanfuture.org

## Ship changes live by default

Unless Jon says otherwise in the request, every change goes live:

1. Commit the work on the session's development branch and push it.
2. Merge it into the default branch, `claude/happy-pasteur-dapleu`, and push that too. GitHub Pages builds the live site from `docs/` on that branch.
3. Confirm the live site updated (fetch https://amorehumanfuture.org and compare it to `docs/index.html`; Pages usually takes a minute or two).

No pull request is needed for this. Hold back from merging only when Jon asks to preview first or keep a change on a branch.

## Layout notes

- `docs/index.html` is the whole page (HTML, CSS and the background video script).
- Check mobile changes at phone widths (320 to 430px) as well as desktop.
