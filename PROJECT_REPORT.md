# SpendWise: Personal Expense Analysis Dashboard

## 1. Project Overview

SpendWise is a responsive, browser-based personal expense tracking and analysis dashboard. The prototype is intended to demonstrate how a simple web application can help users record expenses, group transactions into categories, set a monthly budget, and review spending patterns.

The first version is implemented as a static website using HTML, CSS, and vanilla JavaScript. It does not require a server, database, Python installation, API key, or external JavaScript library.

## 2. Background and Rationale

Managing day-to-day spending can be difficult when purchases are recorded inconsistently or not reviewed regularly. A straightforward expense tracker can help users organise transactions and view their recorded spending in one place. A browser-based solution is suitable for an undergraduate project because it can demonstrate form handling, data validation, calculations, visualisation, responsive design, and client-side persistence without requiring complex infrastructure.

The need described here is the project's motivation, not a claim that a formal user study has already validated the problem. User research and usability testing would be required to establish how well the application addresses users' needs.

## 3. Problem Statement

Students and other individuals may find it difficult to keep track of everyday expenses, understand which categories account for most of their recorded spending, and compare expenses against a monthly budget. SpendWise addresses this problem by providing a simple interface for entering expenses, organising them into categories, reviewing monthly summaries, and monitoring budget usage.

## 4. Aim

To design and implement a beginner-friendly, responsive web application that supports personal expense recording and basic spending analysis through a dashboard.

## 5. Objectives

1. Create an accessible and responsive dashboard interface.
2. Allow users to add and delete expense transactions.
3. Categorise expenses into predefined groups.
4. Calculate monthly totals, transaction counts, daily averages, and remaining budget.
5. Display spending by category and daily spending in a chart.
6. Provide month, search, and category filters.
7. Enable CSV export of transactions for the selected month.
8. Preserve data in browser local storage.
9. Test core interactions and document known limitations.

## 6. Proposed Solution and Scope

SpendWise contains a dashboard with summary cards, a daily spending chart, category summaries, and a budget progress indicator. Users can add an expense by entering a name, amount, category, and date. They can search and filter transactions, delete entries, choose a month, adjust the budget, and export a CSV file.

The initial version includes fictional sample transactions to make the dashboard understandable on first launch. Sample entries are marked in the transaction list, and the interface discloses that the figures are demonstration data.

### In scope

- One user working in one browser.
- Manual entry and deletion of expenses.
- Predefined expense categories.
- Monthly summaries and budget tracking.
- Local storage and CSV export.
- Responsive interface and manual testing.

### Out of scope

- Bank-account connections or payment processing.
- Cloud synchronisation or multi-user accounts.
- Automated receipt scanning.
- Verified financial advice or recommendations.
- A backend database or real-time external data.

## 7. Intended Users

The intended users include students and individuals who want a lightweight way to record personal expenses. This is a proposed audience; no customer interviews, surveys, or market validation are claimed in this report.

## 8. Methodology

The project follows a simple iterative development approach:

1. **Requirements identification:** Define the core actions: record, categorise, summarise, filter, and export expenses.
2. **Interface design:** Organise the dashboard into summary cards, charts, category breakdowns, budget information, and transaction history.
3. **Implementation:** Use HTML for structure, CSS for styling and responsive layout, and JavaScript for validation, calculations, chart rendering, filtering, local storage, and CSV generation.
4. **Data handling:** Use fictional starter entries for demonstration and browser local storage for user-created entries.
5. **Testing:** Manually test common user flows, invalid inputs, filtering, deletion, export, responsiveness, and persistence.
6. **Deployment:** Publish the static site using GitHub Pages if required.

No experimental results, user feedback, or measured financial outcomes are claimed at this stage. Any such claims should only be added after the relevant tests or study have been conducted and documented.

## 9. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure, forms, buttons, tables, and semantic sections |
| CSS3 | Layout, typography, colour, responsive design, and focus states |
| Vanilla JavaScript | Validation, calculations, event handling, chart drawing, filters, and CSV export |
| Browser local storage | Saving transactions and budget in the current browser |
| GitHub Pages | Optional static website hosting |

## 10. Project Deliverables

- `index.html`: the working single-file website.
- `README.md`: setup, feature, and deployment instructions.
- `PROJECT_REPORT.md`: this project report.
- `TESTING_CHECKLIST.md`: manual test cases and expected results.
- `SpendWise_Lean_Canvas_and_Concept_Note.pdf`: proposed business/value canvas and concept note.
- `SpendWise_Project_Presentation.pptx`: editable project presentation.

## 11. Expected Outcomes

The expected outcome is a working static website through which a user can enter expenses, view monthly summaries, compare categories, track a chosen budget, and export recorded transactions. The project should also demonstrate foundational web-development skills, including responsive layout, form validation, client-side state, simple data visualisation, and documentation.

These are expected functional outcomes, not results of a completed formal evaluation. A manual test record should be completed before making claims about reliability or usability.

## 12. Testing Plan

Manual testing should cover:

- Correct page loading and display of sample data.
- Add-expense form validation.
- Updating summary values after adding and deleting expenses.
- Month selection and transaction filtering.
- Budget updates and budget-status changes.
- Category summary and daily chart rendering.
- CSV export.
- Local-storage persistence after reload.
- Responsive layout and keyboard focus.
- Deployment and access through the published GitHub Pages URL.

The detailed checklist and observed results should be maintained in `TESTING_CHECKLIST.md`.

## 13. Limitations

1. Data is entered manually and may be incomplete or inaccurate.
2. Browser local storage is tied to the browser and device; it does not provide cross-device synchronisation.
3. Clearing browser data may delete stored transactions.
4. There is no authentication, server-side backup, or multi-user support.
5. The included starter transactions are fictional examples.
6. The chart and summaries describe only the entries stored in the application.
7. The prototype is not a substitute for professional financial advice.
8. Local storage should not be treated as a secure vault for sensitive financial records.

## 14. Ethical Considerations and Risks

The application should explain where data is stored and avoid misleading users into believing it connects to banks. Users should be advised not to enter confidential financial information into the prototype. If the project is extended to collect real user data, it should minimise data collection, obtain appropriate consent, provide a clear privacy notice, protect stored information, and follow applicable legal and institutional requirements.

Budget indicators should be presented neutrally. The application should not shame users for their spending or claim that one budget is appropriate for everyone.

## 15. Future Enhancements

Potential future features include recurring transactions, savings goals, custom categories, downloadable monthly reports, optional import of a user-selected CSV, and improved accessibility testing. Secure accounts and cross-device synchronisation would require a backend, authentication, access controls, secure data handling, and additional operational costs. Bank integrations would require a suitable authorised provider, user consent, security review, and compliance with applicable requirements.

These are possible extensions rather than features of the current implementation.

## 16. Conclusion

SpendWise demonstrates how HTML, CSS, and vanilla JavaScript can be combined to create a responsive personal expense analysis dashboard. Its manual-entry workflow, monthly summaries, category analysis, budget tracking, and CSV export provide a practical undergraduate web-development project. The current version is deliberately limited to a local browser prototype, with fictional starter data and no bank connection. Further testing and user feedback would be needed before drawing conclusions about usability or real-world effectiveness.
