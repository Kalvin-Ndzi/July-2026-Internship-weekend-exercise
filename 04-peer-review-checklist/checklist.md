# Peer Review Checklist

This activity is meant to help you practice noticing HTML problems in someone else's work. You are not trying to be harsh or perfect — you are helping each other learn.

## How to do it

1. Swap files with a classmate.
2. Open their page and read it as if you are visiting it for the first time.
3. Go through the checklist below.
4. Mark each item as "yes" or "no".
5. If you mark something as "no", write one short sentence explaining why.

That explanation is the most important part. A checkmark by itself does not teach much.

## Structure

- [ ] Starts with `<!DOCTYPE html>` and `<html lang="...">`
- [ ] Has exactly one `<h1>`
- [ ] Headings go in order with no skipped levels (h1 → h2 → h3, not h1 → h3)
- [ ] Uses `<header>`, `<main>`, and `<footer>` instead of generic `<div>` containers for page sections
- [ ] Does not use `<div>` where a more specific semantic tag would fit better

## Images

- [ ] Every `<img>` has an `alt` attribute
- [ ] The `alt` text actually describes the image clearly (not just "image" or the filename)

## Lists and tables

- [ ] Lists use `<ul>`/`<ol>`/`<li>` instead of paragraphs or line breaks pretending to be a list
- [ ] `<ol>` is used only when the order truly matters
- [ ] Tables (if present) are used for real tabular data, not for page layout

## Links and navigation

- [ ] `<nav>` is used for navigation menus
- [ ] Every link's text makes sense on its own (not "click here")
- [ ] Anchor links (`href="#..."`) jump to the correct place

## Forms (if present)

- [ ] Every `<input>` has a `<label>` with a matching `for`/`id` pair
- [ ] Input types match their purpose (`email`, `tel`, `number`, etc.)
- [ ] The form can be used without a mouse by tabbing through it

## One final reflection

**What is one thing on this page that you did not understand at first, and did it turn out to be a real mistake or just a confusing choice?**

Write down whichever answer is true. Both are useful.
