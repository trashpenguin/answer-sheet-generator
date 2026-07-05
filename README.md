# Answer Sheet Generator

A single-file, self-contained HTML tool for generating printable, highly customizable exam answer sheets (built for DepEd Philippines high school use, but works for any school).

**Live demo:** https://trashpenguin.github.io/answer-sheet-generator/

## Features
- Customizable header text (region/division, school name, test title, subject, quarter)
- Toggle student fields: Name, LRN, Grade & Section, Date, Teacher, Score box
- Section-based answer formats — e.g. items 1–10 as True/False, 11–30 as Multiple Choice, with independent column counts and section headings
- Simple mode for a single uniform format across all items
- Bubble style: round shade-in bubbles or boxed letters
- Adjustable density (row spacing/font size) and column count to control page length and save paper
- Half-page mode: prints two identical sheets per page with a cut line, so one sheet of paper yields two answer sheets
- Paper size: Letter, A4, or Legal
- Built-in DepEd and school (Cataingan National High School) logos, both toggleable
- Upload your own school logo to replace the default, right in the browser (no server, no re-upload needed each session)

## Usage

### Online
Open the live demo link above in any browser — no setup needed.

### Locally
1. Download `index.html` (or `deped_answer_sheet.html`) from this repo.
2. Open it in any browser.
3. Adjust the settings in the control panel — the preview updates live.
4. Click **Print / Save as PDF**. The control panel automatically hides itself on the printed page.

No installation, build step, or server required — it's a single static HTML file.

## Files
- `index.html` — served by GitHub Pages at the live demo URL
- `deped_answer_sheet.html` — identical copy, kept under its original filename for direct download

## Hosting
Deployed with GitHub Pages from the `main` branch, root path.
