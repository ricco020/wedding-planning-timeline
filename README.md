# Wedding planning timeline calculator

Free, single-file calculator that turns a wedding date into a dated planning checklist. Enter the wedding date and the day you start planning. It:

- gives every task (venue, photographer, save-the-dates, invitations, marriage license, final head count, thank-you notes...) a real date,
- squeezes the classic 12-month timeline in the same order when the engagement is shorter, without moving any task later than its latest sensible date,
- or keeps the classic dates and moves the late ones to your start date (second mode),
- flags the tasks that are already tight,
- exports the checklist to your calendar (.ics, one all-day event per task) or to a spreadsheet (CSV).

Use it online: https://ricco020.github.io/wedding-planning-timeline/

Lead times are common planning conventions, not survey data. The scheduling was checked against an independent Python implementation on 300 random cases (both modes, 1 to 800 days of planning): 0 difference. The .ics output parses with the Python `icalendar` library.

Printable version (budget sheet, vendor contacts, guest list with RSVP, day-of timeline): https://tidysheets.shop/p/wedding-planner-checklist-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
