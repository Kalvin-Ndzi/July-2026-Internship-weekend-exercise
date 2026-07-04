# Peer Review Checklist

Swap files with a classmate (ideally, their blueprint page from folder 02). Go through this checklist on *their* page and write a one-line explanation for anything you mark "no" — not just a checkmark, an explanation. That's the part that actually builds understanding.

## Structure

- [ ] Starts with `<!DOCTYPE html>` and `<html lang="...">`
- [ ] Has exactly one `<h1>`
- [ ] Headings go in order with no skipped levels (h1 → h2 → h3, not h1 → h3)
- [ ] Uses `<header>`, `<main>`, `<footer>` (not `<div class="header">` etc.)
- [ ] No `<div>` used where a semantic tag would fit better

## Images

- [ ] Every `<img>` has an `alt` attribute
- [ ] The `alt` text actually describes what the image conveys (not "image" or the filename)

## Lists and tables

- [ ] Lists use `<ul>`/`<ol>`/`<li>` — not paragraphs or line breaks pretending to be a list
- [ ] `<ol>` is used only where order genuinely matters
- [ ] Tables (if present) are used for real tabular data, not page layout

## Links and navigation

- [ ] `<nav>` is used for navigation menus
- [ ] Every link's destination text makes sense out of context (not "click here")
- [ ] Anchor links (`href="#..."`) actually jump to the right place — test them

## Forms (if present)

- [ ] Every `<input>` has a `<label>` with a matching `for`/`id` pair — test by clicking each label
- [ ] Input types match their purpose (`email`, `tel`, `number`, not everything as `text`)
- [ ] Form is fully usable with only the `Tab` key, no mouse

## The one open-ended question

**What's one thing about this page you genuinely didn't understand why they built it that way — and did asking them clear it up, or reveal an actual mistake?**

Write down whichever it turns out to be. Both outcomes are useful.
