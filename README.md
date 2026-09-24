\# BrightPath Learning Centre — Website



\## Project description

BrightPath Learning Centre is a tutoring service offering after-school maths, science and English programmes for primary and secondary students. This website targets parents/guardians researching and enrolling their children in tutoring, and prospective students checking programme details.



\## Pages

\- index.html — Home

\- about.html — About / tutors / mission

\- programmes.html — Programmes and pricing

\- events.html — Gallery and upcoming events

\- contact.html — Enrolment form and location



\## Technologies used

HTML5, basic CSS3, Git, GitHub, GitHub Pages.



\## Live site

https://yyediyannah-ai.github.io/is229-a2-yediyannahyuwom/



\## Repository

https://github.com/yyediyannah-ai/is229-a2-yediyannahyuwom



\## Validation

All 5 pages (index.html, about.html, programmes.html, events.html, contact.html) were tested using the W3C Markup Validator (https://validator.w3.org/nu/) on their live GitHub Pages URLs on 3 September 2026. All pages passed with no errors or warnings.



\## Form Submission Note

The enrolment form on contact.html is built with correct HTML5 structure, labelled fields, appropriate input types, and validation attributes (required, minlength, pattern). It does not actually submit data anywhere, since GitHub Pages is a static host with no backend server to receive form submissions. Attempting to submit will show a "405 Not Allowed" page, which is expected behaviour for a static site and outside the scope of this assessment. Client-side HTML5 validation (e.g. blocking empty required fields or invalid email/phone formats) works correctly before this occurs.



\## AI Use Declaration

I used Claude (AI) to guide me through the site structure and to generate HTML and CSS code. Most of this code was pasted into Notepad, with some sections typed out directly, then edited and adjusted by me. I also used AI for step-by-step instructions on using cmd and Git to commit and push my work to GitHub. Throughout the project, I watched YouTube videos and reviewed my lecture notes to properly understand the HTML elements, form validation attributes, and semantic structure I had used, so I could explain and account for my own code.



\## Assessment 3 — Responsive Redesign



This repository has been extended from Assessment 2 into a fully responsive website as

required by the Assessment 3 specification. The site was rebuilt using hand-written HTML5

and CSS3 — no CSS frameworks, themes, or page builders were used.



\### What changed from Assessment 2

\- Added an external, organised stylesheet (`css/base.css`) built around CSS custom

&#x20; properties for colour, typography and spacing.

\- Rebuilt the navigation as a responsive component that wraps/stacks on mobile

&#x20; (under 768px) and displays horizontally on tablet and desktop.

\- Applied CSS Grid to the programme cards on `programmes.html` and the photo gallery on

&#x20; `events.html`.

\- Applied Flexbox to the tutor bios on `about.html`, the "Why Families Choose Us" / "Quick

&#x20; Facts" layout on `index.html`, and the enrolment form / location layout on `contact.html`.

\- Added mobile-first media queries at 768px and 1024px breakpoints, with real structural

&#x20; changes at each breakpoint rather than simple shrinking.

\- Added visible focus states (`:focus`) on all links, buttons and form fields for keyboard

&#x20; accessibility.

\- Styled all call-to-action buttons and the enrolment form consistently using shared

&#x20; `.btn` and form styles.



\### Responsive breakpoints

| Breakpoint | Width | Layout behaviour |

|---|---|---|

| Mobile | 0–767px | Single column, wrapped/stacked navigation |

| Tablet | 768–1023px | 2-column grids where applicable |

| Desktop | 1024px+ | Full multi-column grids, horizontal navigation |



\### Technologies used

HTML5, CSS3 (Flexbox, Grid, custom properties, media queries), Git/GitHub, GitHub Pages.



\### Live links

\- \*\*GitHub Repository:\*\* https://github.com/yyediyannah-ai/is229-a2-yediyannahyuwom

\- \*\*Live Website:\*\* https://yyediyannah-ai.github.io/is229-a2-yediyannahyuwom/



\### Testing evidence

\- \*\*HTML validation:\*\* All 5 pages passed the W3C Nu Html Checker (validator.w3.org/nu)

&#x20; with no errors.

\- \*\*CSS validation:\*\* Both stylesheets (`css/base.css`, `css/styles.css`) passed the W3C

&#x20; CSS Validator (jigsaw.w3.org/css-validator) with no errors.

\- \*\*Responsive testing:\*\* Verified at mobile (375px), tablet (768px) and desktop (1200px)

&#x20; viewport widths using Chrome DevTools device mode, tested directly on the live

&#x20; GitHub Pages site.

\- \*\*Screenshots:\*\* See `/screenshots` folder — 15 images covering all 5 pages

&#x20; (index, about, programmes, events, contact) across all 3 breakpoints.

\- \*\*Keyboard accessibility:\*\* Verified visible focus states by tabbing through

&#x20; navigation, buttons and the enrolment form.



\### AI Use Declaration — Assessment 3

This assignment was completed as an extension of Assessment 2, per the Assessment 3

specification. AI assistance (Claude, Anthropic) was used during development in the

following ways:

\- Guidance on structuring a mobile-first CSS approach using custom properties, Flexbox

&#x20; and Grid.

\- Drafting starter CSS (`css/base.css`) and explaining how to integrate it into existing

&#x20; HTML files without breaking the Assessment 2 submission.

\- Step-by-step troubleshooting support, including diagnosing a CSS specificity conflict

&#x20; between the original stylesheet and the new base stylesheet, and resolving browser

&#x20; caching issues encountered during local testing.

\- All final HTML/CSS decisions, page content, and implementation were reviewed, edited

&#x20; and applied by the student. All Assessment 2 content and structure was preserved and

&#x20; extended, not replaced.



\### Git history and Assessment 2 preservation

Work was carried out on a separate `assessment-3` branch to preserve the original

Assessment 2 submission, then merged into `main` once complete. The exact state of the

repository at Assessment 2 submission is preserved at the Git tag

`assessment-2-submission` for reference. Commits reflect the staged process: base

stylesheet → responsive navigation → Flexbox layouts → Grid layouts → page-by-page

rollout → screenshots → final merge.

