# Validator Pass

A 10-minute exercise to install a lifelong habit: validate your HTML before you trust it, especially before adding CSS on top of it.

## Steps

1. Open the [W3C Markup Validator](https://validator.w3.org/).
2. Choose "Validate by File Upload" and upload one of your `.html` files (or use "Validate by Direct Input" and paste the code).
3. Read the errors and warnings it reports. Don't panic at the count — some are trivial, some matter a lot.
4. Fix them one at a time, starting from the top (early errors sometimes cause a cascade of later false-positives).
5. Re-validate until you get a clean pass.

## What to actually pay attention to

- **Errors** — real problems: unclosed tags, invalid nesting (e.g. a `<div>` inside a `<p>`), duplicate `id`s, missing required attributes.
- **Warnings** — often stylistic or about using the wrong element for the job (e.g. using `<b>` instead of `<strong>`). Worth reading, not always worth panicking over.

## Why this matters right before CSS

Once CSS is layered on, a structural bug can *look* completely fine visually while still being broken underneath (invalid nesting, an unclosed tag that the browser silently "fixes" for you in a way you didn't intend). Validating now, while the page is still bare, means you're fixing real structure — not chasing a visual bug that's actually a structural one in disguise, three weeks from now.

## Habit to build

Run every one of your capstone project's pages (folder 06) through the validator before considering it "done." Aim for zero errors. A couple of stylistic warnings are fine to discuss and leave, if you can explain why.
