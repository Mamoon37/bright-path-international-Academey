# BrightPath International Academy - Three-Page Website

A Training Academy website for Web Technologies, Assignment #2.

| File | Purpose | CSS method |
| --- | --- | --- |
| `index.html` | Home: introduction and courses | Inline |
| `information.html` | Schedule, fees, audio, video | Embedded |
| `registration.html` | Student registration form | External (`style.css`) |

Live site: _add your GitHub Pages URL here_
Repository: _add your GitHub repository URL here_

## Short Explanation

CSS (Cascading Style Sheets) controls how HTML looks. It separates content from presentation, so one stylesheet can restyle many pages, pages stay consistent, and the HTML stays clean and easier to maintain.

In the rule `h2 { color: #12304a; }` from `information.html`, `h2` is the selector, `color` is the property and `#12304a` is the value.

Inline CSS uses a `style` attribute on one element (used on `index.html`); it is quick but hard to reuse. Embedded CSS sits in a `<style>` element in the head (used on `information.html`) and applies to one page. External CSS lives in a separate `.css` file linked with `<link>` (used on `registration.html`) and can style a whole site.

CSS1 (1996) introduced basic fonts, colours and margins. CSS2 and CSS2.1 added positioning, media types and tables, with 2.1 fixing errors. Modern CSS is split into modules such as Flexbox, Grid, Selectors and Media Queries, which develop and are released independently.

Browser support matters because browsers can render features differently, and users should have a working page whichever they use. I tested this site in Google Chrome and Mozilla Firefox.

Semantic HTML example: `<nav>` clearly states that its content is navigation. Non-semantic example: `<div class="layout">` only groups content and says nothing about its meaning.

## Testing Notes

Add your results here after testing:

- **Validation:** W3C Markup Validation Service, one screenshot per page in `/screenshots`.
- **Form tests:** empty required fields, invalid email, password shorter than 8 characters.
- **Browsers:** Chrome ____ / Firefox ____ (record any differences).
