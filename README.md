# Murugan Temple of St. Louis — Mobile App Proposal

A management presentation proposing an intuitive iOS and Android app for the
[Murugan Temple of St. Louis](https://murugantempleofstlouis.org/), published as a static site for
GitHub Pages.

> **Discussion document.** Every app screen in this repository is a **conceptual design**. No app
> exists, nothing has been approved or purchased, no vendor or payment provider has been selected,
> and the temple has not endorsed this proposal. All sample data is labelled as such.

## What's here

| Path | Contents |
|---|---|
| `index.html` | The presentation — 12 slides plus two appendices, with speaker notes behind a toggle on each slide, and a gallery of every conceptual app screen. |
| `slides/` | Rendered PNG of every slide at 150 dpi. |
| `screens/` | High-resolution conceptual app screens (1254 × 2742, transparent background). |
| `downloads/` | Editable PowerPoint and PDF versions of the deck. |
| `executive-summary.html` · `Executive-Summary.md` | Brief executive summary, source appendix and the full list of assumptions requiring temple validation. |
| `leadership-decisions.html` · `Leadership-Decisions-One-Page.md` | One-page list of the decisions the board is asked to make. |
| `speaker-notes.html` · `Speaker-Notes.md` | All speaker notes in one document, sized for a 12–15 minute talk. |

## Publishing to GitHub Pages

1. Push this repository to GitHub (see below).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Save. The site appears at `https://<your-username>.github.io/murugan-temple-stlouis/` within a minute or two.

A `.nojekyll` file is included so GitHub Pages serves the folders as-is rather than running Jekyll.

## The proposal in short

An app organised around five tabs — Home, Events, Services, Donate, More — that brings together
the temple's schedule, family RSVPs, pooja and abhishekam sponsorships, private priest service
requests, giving, volunteering, live content and timely notifications, while keeping those four
kinds of request clearly separate from one another.

The ask is **not** a production build. It is approval for a short discovery phase, interviews with
priests, administrators, volunteers, donors, families and seniors, validation of temple policies
and constraints, a clickable prototype, and a limited pilot on one recurring pooja and one major
festival.

## Commitments carried through the design

- Every action has a route that is not the app — telephone the office, or ask a volunteer.
- Crowd status is an estimate entered by a person, labelled as an estimate, with no continuous location tracking at any stage.
- Status is never conveyed by colour alone; each state carries a word and an icon.
- Notification permission is requested after a relevant action, never on first launch, and categories are individually controllable.
- No temple photograph, logo or devotional image is reproduced. All visuals are original.

## Sources

All temple pages were reviewed in September 2026; the full list is in the executive summary.
Tirumala Tirupati Devasthanams material was consulted only as a reference for transferable
patterns — service discovery, booking and confirmation, donations, live content, visitor guidance
and FAQs. Its scale, branding and operating model are not proposed here.
