# Job Hunting Tools

Free, editable tools to help you run a job search without losing track of where
everything stands. Right now this folder holds one thing: an Excel job-application
tracker.

**Take it, open it, and make it yours.** Rename sheets, add or delete columns,
change the stages, rip out what you don't need. It's a starting point, not a
prescription — there's no wrong way to use it.

---

## `job_tracker_enhanced_template.xlsx`

A multi-sheet Excel workbook for tracking applications from "applied" through
"offer," with a dashboard and funnel stats that update themselves as you fill in
the main list.

New to it? Open the **📖 How to Use** tab first — it's the leftmost sheet and walks
through everything below right inside the file.

### What's inside

| Sheet | What it's for |
|---|---|
| **📖 How to Use** | A built-in guide — how to get started, what each tab does, and how the automatic parts work. The first thing you see when you open the file. |
| **📊 Dashboard** | At-a-glance pipeline summary — counts per stage, total applications, active (non-rejected) count, and response rate. Pulls from the other sheets automatically. |
| **📋 All Applications** | The main log. One row per application: company, role, date applied, a column for each interview stage, offer, status, notes, and the job link. This is the sheet you'll live in. |
| **💰 Salary Comparison** | Compare offers and postings side by side — salary low/high/midpoint, remote/hybrid/in-office, benefits, training budget, and an averages row. |
| **📈 Stats** | The application funnel — how many applications reached each stage, and each stage as a percentage of total applied. Feeds the dashboard. |
| **Companies contacted** | A light CRM for outreach: who you messaged, their role, the date, and whether they replied. |
| **Apply to these** | A quick shortlist of postings to get to — company, position, link. |
| **Goal companies** | Your dream-employer list, with career-site links and space for your own notes and a verdict. |
| **Target list tabs** | A few spare tabs (Target list 1, Target list 2, and an example themed tab) for grouping targets however you like — by specialty, by team, by funding stage, by anything. Rename or delete them freely. |

### How the automatic parts work

Two sheets do work for you, so it's worth knowing how:

- The **Stats** sheet counts your applications by matching the **Status** column
  (column J) on **All Applications** against each stage name. So the numbers only
  add up if the words you type in Status match the stage labels — `Applied`,
  `Phone Screen`, `1st Interview`, `2nd Interview`, `3rd Interview`,
  `4th Interview`, `Ghosted`, `Offer`, `Cancelled`, `Rejected`. Use a dropdown
  (Data → Data Validation) if you want to keep them consistent.
- The **Dashboard** reads straight from Stats, so once Status is filled in, the
  summary and response rate update on their own. An empty tracker shows `0%` rather
  than an error, so you can start from scratch safely.

If you rename a stage, change it in both the Status column and the Stats sheet's
Stage list so the counts keep matching. If you'd rather not deal with the formulas
at all, you can delete the Dashboard and Stats sheets and just use All Applications
as a plain list — nothing else depends on them.

### Getting started

1. Open the file in Excel, Google Sheets, or LibreOffice Calc.
2. Read the **📖 How to Use** tab (leftmost) if you want the full tour.
3. Start logging in **📋 All Applications** — one row per application.
4. Keep the **Status** column current; the Dashboard and Stats follow along.
5. Add companies you're eyeing to **Apply to these** or **Goal companies**.
6. Edit anything. Seriously — it's yours now.

> **Compatibility note.** The dashboard and stats use ordinary spreadsheet formulas
> (`COUNTIF`, `SUM`, `AVERAGE`) that work in Excel, Google Sheets, and LibreOffice.
> If you import into Google Sheets and a total looks off, click the cell and check
> the formula recalculated — a quick edit-and-enter usually refreshes it.

---

## A note on your own data

This is a personal tracker — the moment you start filling it in, it holds names,
companies, and salary details about your search. If you ever fork it, copy it, or
share your filled-in version, remember that all of that travels with the file.
Keep your working copy private and share only the blank template.
