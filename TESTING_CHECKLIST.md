# SpendWise Manual Testing Checklist

Use this checklist before demonstrating the project or deploying it. Mark each case Pass or Fail and record any notes. Do not mark a test as passed until you have actually performed it.

| ID | Test | Steps | Expected result | Result / notes |
|---|---|---|---|---|
| T01 | Open website | Open `index.html` in a modern browser. | Dashboard loads without a blank page or visible error. | Not tested |
| T02 | Sample data | Inspect summary cards and transaction list. | Fictional sample transactions and summary figures appear. | Not tested |
| T03 | Add valid expense | Add a named expense with positive amount, category, and today or earlier date. | Modal closes, entry appears, and summary figures update. | Not tested |
| T04 | Required name | Try to submit without an expense name. | Browser/form validation prevents submission. | Not tested |
| T05 | Invalid amount | Try zero, a negative amount, or an amount above the allowed maximum. | Invalid amount is rejected. | Not tested |
| T06 | Future date | Select a future date and submit. | A friendly validation message appears; no entry is saved. | Not tested |
| T07 | Category breakdown | Add expenses in two different categories. | Category summary reflects the amounts for the selected month. | Not tested |
| T08 | Budget update | Change the monthly budget. | Remaining budget, usage percentage, progress bar, and status update. | Not tested |
| T09 | Budget warning | Set a budget lower than the month's total expenses. | Dashboard indicates the budget has been reached or exceeded. | Not tested |
| T10 | Month filter | Select another month. | Summary, chart, category list, and transactions reflect that month. | Not tested |
| T11 | Search | Enter a word in the transaction search field. | Only matching transactions remain visible. | Not tested |
| T12 | Category filter | Choose one category. | Only transactions from that category are shown. | Not tested |
| T13 | Delete transaction | Click Delete and confirm. | Transaction is removed and summary values recalculate. | Not tested |
| T14 | Cancel deletion | Click Delete and cancel the confirmation. | Transaction remains unchanged. | Not tested |
| T15 | CSV export | Select a month and click Export CSV. | A CSV file downloads containing the selected month's transactions. | Not tested |
| T16 | Local persistence | Add an expense, reload the page in the same browser, and inspect it. | Saved expense and budget remain available. | Not tested |
| T17 | Reset view | Change month/search/category and click Reset view. | Month and filters return to defaults; saved transactions are not deleted. | Not tested |
| T18 | Modal keyboard close | Open the expense dialog and press Escape. | Dialog closes and focus returns to the Add expense button. | Not tested |
| T19 | Mobile layout | Resize to a narrow mobile viewport. | Cards stack and content remains usable without page-wide horizontal scrolling. | Not tested |
| T20 | Desktop layout | View at a typical desktop width. | Sidebar, dashboard cards, charts, and table are laid out correctly. | Not tested |
| T21 | Keyboard access | Use Tab and Enter to navigate controls. | Focus is visible and interactive controls can be reached. | Not tested |
| T22 | GitHub Pages | Open the published URL after deployment completes. | Website is accessible at the expected URL and main features work. | Not tested |

## Test environment

- Device / OS: ______________________________
- Browser and version: ______________________
- Test date: ________________________________
- Tester: ___________________________________

## Notes

- The starter transactions are fictional demonstration data.
- Local storage is specific to the current browser/device and may be removed if browser data is cleared.
- A completed GitHub Actions workflow does not by itself confirm that the published site is reachable. Open the published URL and test it.
