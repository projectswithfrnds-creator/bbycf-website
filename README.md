# BBYCF Website

Primary static website for Body Bend Yoga Community Foundation at `bbycf.org`.

## Current production design

The root `index.html` is Chris's approved BBYCF redesign prototype, transferred from the Vercel prototype into this GitHub Pages repository.

Included live sections:

- Homepage with Ripple Seed visual system and Bohemian/earth-tone styling
- Scholarship, program, partner, donate, contact, impact, events, and signup anchors
- `/funders.html` standalone funders page
- Branded signup form that submits to Drew's Google Form through a hidden iframe
- Custom domain retained through `CNAME` (`bbycf.org`)

## Archived prior site

The previous repository website was not deleted. It has been moved to:

`archive/original-site-2026-07-13/`

That archive includes the old pages, stylesheet, and original image folder for reference or restoration.

## Compatibility routes

The former top-level pages now redirect to the relevant section of the new single-page design:

- `/about.html` -> `/#about`
- `/contact.html` -> `/#contact`
- `/donate.html` -> `/#donate`
- `/partner.html` -> `/#partner`

## Editing notes

This is a static site. Most styling and behavior currently live inline in `index.html`, because the approved prototype was built as a self-contained static page. Keep secrets, form-owner credentials, and raw client materials out of the repo.
