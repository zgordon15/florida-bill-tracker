# Florida Bill Tracker

Florida Bill Tracker is a personal, self-hosted financial management application designed to help users organize bills, monitor account balances, and track payments.

## Features

- Track one-time and recurring bills.
- Monitor checking, savings, investment, and debt accounts.
- View upcoming bills and projected balances.
- Match bill payments with imported bank transactions.
- Manage multiple users with separate financial information.
- Access the application securely through a private network.

## Technology

- Python and Flask
- SQLite database
- Docker
- Plaid API for financial account connectivity
- Tailscale for private remote access

## Plaid Integration

Florida Bill Tracker integrates with Plaid to retrieve authorized financial account information, including balances and transactions.

The application currently uses Plaid Sandbox for development and testing. Production connectivity is being evaluated for personal use.

## Security and Privacy

The application is self-hosted and is not publicly accessible. Financial records and application credentials are not stored in this public repository.

This repository currently serves as a public project overview rather than a distribution of the application's source code.

## Project Status

Active personal development project.
