# SpendWise — Personal Expense Analysis Dashboard

SpendWise is a beginner-friendly, responsive personal expense tracking website built with **HTML, CSS, and vanilla JavaScript**. It helps users record expenses, review spending by category, set a monthly budget, and export a monthly transaction list as a CSV file.

## Features

- Dashboard cards for total expenses, remaining budget, transaction count, and daily average.
- Add and delete expense transactions.
- Categories: Food, Transport, Education, Shopping, Health, Bills, Entertainment, and Other.
- Monthly filter and category/search filters for transactions.
- Spending-by-category summary and a daily spending bar chart.
- Monthly budget progress indicator.
- CSV export for the selected month.
- Browser local storage to preserve data between visits in the same browser.
- Responsive layout for desktop, tablet, and mobile screens.
- Clear notice explaining the sample data and local-storage limitations.

## Technology used

- **HTML5** for structure and semantic elements.
- **CSS3** for layout, styling, and responsive behaviour.
- **Vanilla JavaScript** for transaction handling, calculations, filtering, charts, validation, and CSV export.
- **Browser local storage** for client-side persistence.
- **GitHub Pages** for optional static hosting.

No Python, database, backend, API key, or external JavaScript library is required.

## How to run locally

1. Download `index.html`.
2. Save it in a folder on your computer, for example `SpendWise`.
3. Double-click `index.html`.
4. Open it in a modern browser such as Chrome, Edge, or Firefox.
5. Add a test expense and check that the dashboard updates.

The site can run directly from the file. For a more realistic web-server test, you can use the VS Code Live Server extension, but it is optional.

## Important data and privacy notes

- The starter transactions are fictional examples for demonstrating the interface.
- Entries are stored in local storage in the current browser on the current device.
- Data does not automatically sync across browsers or devices.
- Clearing browser site data may remove saved transactions.
- This prototype does not connect to bank accounts or financial institutions.
- SpendWise is an educational project and is not professional financial advice.
- Avoid entering sensitive or confidential financial information into this demonstration.

## GitHub Pages deployment

1. Sign in to GitHub and create a repository, for example `spendwise-dashboard`.
2. Upload `index.html` to the **root** of the repository. Ensure the filename is exactly `index.html`.
3. Open the repository's **Settings** tab.
4. Select **Pages** in the sidebar.
5. Under the build and deployment section, choose **Deploy from a branch** if that option is available.
6. Select the branch you are using, usually `main`, and choose the `/ (root)` folder.
7. Save the settings and wait for the Pages deployment to finish.
8. Open the URL shown on the Pages settings screen. It commonly resembles `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

A successful GitHub Actions workflow indicates that the workflow completed; it does not, by itself, prove that the website is reachable at the expected URL. Open the published URL and test the page directly.

### Troubleshooting a 404

- Confirm the file is named `index.html` (not `index.html.txt`).
- Confirm `index.html` is in the selected publishing folder.
- Confirm Pages is publishing the correct branch and folder.
- Check the Actions tab and Pages settings for deployment errors.
- Wait a few minutes after the first deployment, then reload the exact URL displayed by GitHub Pages.
- If the repository name is part of the URL, make sure it is included.

## Suggested manual tests

- Confirm all summary cards appear.
- Add a valid expense and verify totals update.
- Try an empty name, zero/negative amount, and future date; the form should reject invalid input.
- Change the month and confirm that the summaries and transactions change.
- Change the budget and verify the budget status updates.
- Search and filter transactions.
- Delete an expense and confirm it disappears.
- Export the selected month's transactions to CSV.
- Resize the browser to test mobile and desktop layouts.
- Reload the page and verify that entries persist in the same browser.

See `TESTING_CHECKLIST.md` for a more complete test record.

## Project scope and future enhancements

The current version is a static, single-user prototype. Future work could include a secure backend, user accounts, cross-device synchronisation, recurring transactions, savings goals, and richer reports. Those features would require additional design, security, and testing; they are not included in this version.
