# RouteLedger — Bus Fees Management Software

A responsive, browser-based bus/transport fee management starter app for schools. Built with plain HTML, CSS and JavaScript so it can be hosted free on **GitHub Pages**.

## Features

- Dashboard: registered students, total collected, outstanding dues and current-month collections
- Student records: student/admission ID, class, guardian contact, bus route, monthly fee and number of assigned fee months
- Fee payments: receipt number, date, fee months, method and notes
- Outstanding balance calculation and due-student list
- Routes and buses: route name, vehicle number, driver and description
- Search/filter students and search payment history
- Export student and payment data to CSV
- Responsive layout for desktop and mobile
- Local browser storage; no server or API key required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add routes, then students, then record payments.

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `bus-fees-management`.
2. Upload `index.html`, `styles.css`, `app.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. Wait for the published URL to appear in the Pages section.

## Important limitations

- **This is a front-end starter app, not a secure multi-user school system.** Data stays in the current browser's local storage and is not automatically shared with other staff, computers, or phones.
- Clearing browser data can erase saved records. Export CSV backups regularly.
- Do not enter sensitive information into a public demo.
- For real school use, add authentication, a server-side database, permissions, automated backups, and an audit log before storing real student records.
- The app calculates assigned fee total as `monthly fee × fee months`, then subtracts recorded payments. It does not automatically create invoices or assign individual months.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- `localStorage`
- GitHub Pages

## License

MIT — you may use, modify and distribute this starter project. Add a `LICENSE` file if you want to formally include the MIT license text.
