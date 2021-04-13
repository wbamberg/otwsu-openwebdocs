# Open Web Docs

---

## About me

* Will Bamberg
* Technical writer/documentation engineer
* I've worked at:
    * Mozilla (on MDN)
    * Element (on Matrix)
* Now Open Web Docs (on MDN, again)

---

## What is Open Web Docs?

* People and organizations fund the Open Web Docs project, which is then able to hire full-time writers, who create and maintain open web documentation.
* For now, but not necessarily forever, this is focused on MDN.

---

## Early days of MDN

* Early on, MDN didn't differentiate much between:
    * "open web technology" (JS, CSS, HTML)
    * "Mozilla technology" (XUL, XPCOM)

[MDC homepage in 2008](https://web.archive.org/web/20080907231611/https://developer.mozilla.org/en)

---

## MDN as a standard reference

* 2012-2015: webplatform.org did not get traction
* MDN became seen as the standard reference for the Web
* Commitment from the MDN team to be independent

---

## Product Advisory Board

* The MDN Product Advisory Board formed in 2018
* Initial members: W3C, Google, Microsoft, Samsung
* Formal input into MDN content and platform strategy
* Acknowledged that MDN provides independent documentation of web standards
* No direct financial commitment to MDN from PAB members

[MDN Product Advisory Board](https://developer.mozilla.org/en-US/docs/MDN/MDN_Product_Advisory_Board)

---

## 2020 and Open Web Docs

* With the Mozilla layoffs in August 2020, PAB members decided it was time to create an organization to create and maintain web docs that would be independent of any one company
* This organization is Open Web Docs

---

## Who is in Open Web Docs?

* Full-time employees are currently:
    * Florian Scholz
    * Will Bamberg
* Both are technical writers with lots of experience of working on documentation infrastructure, and of working on MDN!
* We will be hiring! 2 people this year is our plan.

---

## What do we do? (1)

* Working on MDN at the moment. But not necessarily limited to MDN in the future.
* Close working relationship with Mozilla, but an independent roadmap

---

## What do we do? (2)

* Day-to-day maintenance of MDN content: fixing docs and reviewing PRs
* Bigger content and infrastructure projects:
   * Machine-readable specification URLs (in collaboration with Mike Smith from the W3C)
   * Markdown conversion (in collaboration with Mozilla)
* Collaborate with and guide people who want to make bigger content contributions

---

## How are we funded?

* Big and small donations from companies and individuals
* Our fiscal host is [Open Collective](https://opencollective.com/open-web-docs) and all our finances are open

---

## How do we decide what to work on?

* Anyone can file [issues](https://github.com/openwebdocs/project/issues) for OWD projects.
* We assess them using a set of [public criteria](https://github.com/openwebdocs/project/blob/main/steering-committee/prioritization-criteria.md)
* We have a [Steering Committee](https://github.com/openwebdocs/project/blob/main/steering-committee/membership-expectations.md) that helps us prioritize work.

---

## Markdown on MDN (1)

* Currently MDN is authored in [raw HTML](https://raw.githubusercontent.com/mdn/content/main/files/en-us/web/javascript/reference/global_objects/array/slice/index.html)
* This is painful and error-prone to edit, so we want to use Markdown instead
* But MDN has all kinds of HTML-soup items in it that will not survive Markdown conversion:
    * lots of CSS classes, some obsolete, some still used
    * inline styles
    * complex tables that Markdown table syntax can't handle
* And MDN is huge: ~10,000 pages

---

## Markdown on MDN (2)

* The plan: convert just the JS docs (~1000 pages) for the first attempt
* Figure out:
    * Which problematic HTML features we're using
    * Which of these features we can live without
    * Where we will have to extend GFM to support these features
* Design a conversion process that implements these choices

---

## The future: dreaming of structured content

* The browser-compat-data project liberated content from an HTML-soup prison
* What if we did this for other aspects of the docs?
* Let writers specify data as data
* Have MDN build it into web pages
* Enable other applications to integrate content: other sites, editors, devtools...

---

* These slides: https://github.com/wbamberg/otwsu-openwebdocs
* Questions?
