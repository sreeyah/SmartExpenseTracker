# Smart Expense Tracker

A modern personal finance tracker built with Node.js, Express, and SQLite. It includes transaction tracking, category management, dashboard summaries, export support, and professional reports.

## Features
- Add, edit, and delete expenses and income entries
- Manage custom categories
- Filter transactions by date range and search text
- Dashboard summary with balance, income, expense totals, and transaction count
- Category breakdown report and chart
- Export all data as JSON
- Responsive user interface with clean layout

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Open your browser at `http://localhost:4000`

## Project Structure
- `server.js` - Express server and API routes
- `db.js` - SQLite initialization and schema setup
- `public/` - Static frontend files
- `data/tracker.db` - SQLite database file created automatically

## API Endpoints
- `GET /api/expenses` - list transactions
- `POST /api/expenses` - add a transaction
- `PUT /api/expenses/:id` - update a transaction
- `DELETE /api/expenses/:id` - remove a transaction
- `GET /api/categories` - get category list
- `POST /api/categories` - add new category
- `GET /api/overview` - dashboard summary
- `GET /api/report/categories` - category totals
- `GET /api/export` - download JSON export

## Notes
- The app initializes with default categories.
- Data is persisted locally with SQLite in `data/tracker.db`.
- Use the export button to save your complete transaction history.
## Screenshots Output
<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/f19503ee-7d54-4ee1-82b0-3fd3f6755677" />

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/f1e5b229-7180-47d9-9627-69571e3d44b0" />

