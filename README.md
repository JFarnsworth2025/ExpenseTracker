# ExpenseTracker

A Python desktop expense tracker for Pariven, built with PySide6.

Author: Jacob  
Version: 0.0.1

## Current status

Project foundation only. The desktop interface and expense management are
not implemented yet.

## Development setup

Use Python 3.10 or newer. From the project folder in PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

The future application entry point is `main.py`. It currently exits without
opening a window.

## Planned features

- Add, view, edit, and delete expenses.
- Spending totals, category summaries, and filters.
- Local JSON storage.
- Monthly net pay, budgets, and charts comparing spending with remaining income.

Features will be added incrementally. Work hours, overtime estimates, and bank
connections are deferred.
