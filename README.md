# CNA Training Institute enrollment demo

A self-contained, single-file demo of a CNA school enrollment platform. Built as the asset we send when a cold-email prospect replies "yes, show me".

## Open it

Open index.html in any modern browser. No server, build step, or network connection is needed. Everything runs from the one file.

## What to try

The page walks through five screens, shown in the progress bar at the top:

1. Program and cohort: pick the day, evening, or weekend schedule. Start dates and seats left update the selection.
2. Registration: review the $100 fee, fill the non-functional card form, and select Pay $100 and continue.
3. Documents: upload any file to simulate a document. Use Admin review to approve or reject a document with a note; rejected files show the note and can be re-uploaded.
4. Agreement: type a name, sign, and see the signed confirmation.
5. Owner dashboard: filter the roster by cohort, check documents and payment status, and select Start a new demo to reset.

## Demo behavior

- All people, cohorts, payments, and documents are fake sample data.
- Nothing is sent, saved, or charged. Uploads only keep the selected file name in memory.
- No CDN, web fonts, images, or external requests. System fonts and inline CSS/JS only.
- Resetting the demo clears all state and returns to step 1.

## Files

- index.html: the complete demo (HTML, CSS, and JavaScript in one file).
- README.md: this note.

## Verification

Opened and walked through in headless Google Chrome: all 46 interaction checks passed with no console or page errors. Also checked at a 390 px mobile viewport; every screen fits with no horizontal page overflow (the dashboard table scrolls inside its panel). Source is 580 lines.
